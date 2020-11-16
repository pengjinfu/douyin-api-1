# 从抖音app爬取数据


## 抖音视频Api、抖音直播Api、抖音评论采集、抖音弹幕采集、抖音爬虫、抖音去水印、抖音视频下载、抖音视频解析
## 抖音直播数据、抖音数据采集、抖音直播监控

#### TiToData：专业的短视频数据采集、处理平台。
> 更多信息请联系： [TiToData](https://www.titodata.com/about?from=shipinapi)
```
海量数据采集
每天为客户采集5亿条数据
覆盖主流平台：TikTok，Zynn，YouTube，抖音，快手，1688，小红书，拼多多，淘宝，美团，饿了么，淘宝，微博

```

# 以下为正文

背景介绍
---
当下最火的短视频app莫过于抖音了，作为时下短视频平台的龙头，抖音吸引了大量的流量，并产生了与之相应的产业链，所以针对抖音app的爬虫需求也与日俱增，但抖音app的反爬虫策略比较复杂，非静态接口数据加入了动态秘钥变化，其中URL的as、cp、mas、X-***变量随时间动态变化，很难攻破其中的算法，同时怀疑加了私钥。因此，本工程旨在提供物理爬虫的方式，以期从不同角度躲避抖音的反爬虫策略，从而获取所需的爬虫数据。

爬虫需求
---
根据指定的抖音号爬取其关注的抖音号，包括字段uid，short_id，unique_id，nick_name。

环境配置
-------
* 安卓SDK，配置好adb环境变量
* Fiddler抓包软件
* Python 3.x，配置好Python环境变量，同时安装好opencv python版本
* 手机和电脑均在同一局域网
* 一台性能较好的安卓手机，不建议采用安卓模拟器，除非安卓模拟器运行非常流畅，但是一般都很卡

预处理步骤
-------
安卓截屏工具截取所需要的关键信息（建议使用系统截屏工具），例如：![图片](https://raw.githubusercontent.com/li-phone/DouyinCrawler/master/src/res/following.png)

操作步骤
-------
1. 进入开发者选项，打开安卓调试模式，允许电脑对设备进行调试，同时用数据线连接手机
2. 修改安卓手机网络设置选项，设置网络代理，网络代理指向Fiddler，并且安装好Fiddler证书
3. 打开Fiddler，在FiddlerScript脚本下找到OnBeforeResponse函数，修改成下述代码，可以不设置过滤
    ```
    public static var main_uid = '';
    static function OnBeforeResponse(oSession: Session) {        
        if (m_Hide304s && oSession.responseCode == 304) {
            oSession["ui-hide"] = "true";
        }
        if (oSession.fullUrl.Contains("/aweme/v1/aweme/post/?")){
            oSession.utilDecodeResponse();
            var str = oSession.oRequest.headers.RequestPath;
            var idx = str.IndexOf('user_id=');
            str = str.Substring(idx);
            var arr = str.Split('&');
            str = arr[0];
            main_uid = str;
            oSession.SaveResponseBody("F:\\duekiller\\2\\douyin\\data\\"+main_uid+"-"+Date.parse(new Date())+"-"+oSession.id+"-aweme_v1_aweme_post_body.txt");
        }
        if (oSession.fullUrl.Contains("/aweme/v1/user/following/list/?")){
            oSession.utilDecodeResponse();
            oSession.SaveResponseBody("F:\\duekiller\\2\\douyin\\data\\"+main_uid+"-"+Date.parse(new Date())+"-"+oSession.id+"-aweme_v1_user_following_list_body.txt");
        }
    }
    ```
4. 解锁手机，保持唤醒状态
5. 运行douyinscript.py
6. 爬虫完毕之后，运行get_douyin_uid.py整理所爬取的数据

爬虫结果
-------
```
uid,short_id,unique_id,nickname
60678995364,580442956,,神奇的眺眺
55310167624,31102346,,ʚ无邪ɞ͜✿҉
62366362462,212305348,,我在校正这个世界
64625244328,68438776,,哈哈and暄暄妈妈
94744555076,578138868,,小野不听话
106481830682,1725691070,,猿_人
4551343909,0,jiaowolaobo,叫我老伯
98526627908,1492721626,,万物30秒
...
```

总结
-------
本工程历时四天四夜，从URL分析，到apk逆向分析，再到物理模拟，前两项均失败了，后一项终于提供了一套解决方案，但物理模拟有天然的不足，其环境配置复杂，设备性能要求较高，同时爬取的速度较慢，识别率不高，但似乎没有更好的解决方案了，所以接下来还需要提高其不足之处。
  
