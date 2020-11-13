# 抖音Api：搜索、用户、视频、直播、带货、话题、推荐、榜单


## 抖音视频Api、抖音直播Api、抖音评论采集、抖音弹幕采集、抖音爬虫、抖音去水印、抖音视频下载、抖音视频解析
## 抖音直播数据、抖音数据采集、抖音直播监控

---

#### TiToData：专业的短视频数据采集、处理平台。
#### 更多信息请联系： [TiToData](https://www.titodata.com/about?from=douyinapi)

```
海量数据采集
每天为客户采集5亿条数据
覆盖主流平台：TikTok，Zynn，YouTube，抖音，快手，1688，小红书，拼多多，淘宝，美团，饿了么，淘宝，微博
联系vx：ifuxing123
```



# 接口列表：

## 搜索

- 关键词搜索用户
- 关键词搜索话题
- 关键词搜索视频
- 关键词搜索音乐
- 关键词搜索直播
- 关键词搜索地址
- 关键词搜索商品
- 关键词综合搜索

## 用户

- 用户信息
- 用户视频列表
- 用户直播信息
- 用户商品橱窗
- 用户粉丝列表
- 用户关注列表
- 用户喜欢列表

## 视频

- 视频详情
- 视频评论列表
- 视频带货商品列表
- 视频评论的回复列表

## <a href="https://github.com/Video-Hub/douyin-live" target="_blank">直播</a>

- 直播间信息
- 直播间 弹幕、关注、送礼、点赞 实时查询
- 直播间带货商品列表
- 直播间开播查询
- 直播间在线观众
- 直播间随机推荐

## 带货

- 带货商品查询
- 带货同款商品视频列表
- 带货视频随机推荐

## 话题

- 话题详情
- 话题视频列表

## 推荐

- 首页视频推荐
- 热门话题推荐

## 榜单

- 明星榜
- 热点榜
- 直播榜
- 今日最热视频榜
- 人气好物榜


# 视频列表接口示例如下：
更多接口文档请联系客服获取：[TiToData](https://www.titodata.com/about?from=douyinapi)

### 请求地址


```http
GET http://api2.titodata.com/api/video/lists
```


### 请求参数
| 名称 | 必填 | 类型 | 说明 |
| :--- | :--- | :--- | :--- |
| token | 是 | string | 登录令牌 |
| create_time_start | 否 | int | 视频发布时间戳，开始时间 |
| create_time_end | 否 | int | 视频发布时间戳，结束时间 |
| author_id | 否 | int | 作者id |
| sort_field | 否 | string | 排序字段，默认digg_count，可选项：digg_count、comment_count、share_count |
| sort | 否 | string | 排序，默认desc，可选项：desc、asc |
| page | 否 | int | 默认第1页，最大100页 |
| page_size | 否 | int | 默认20条，最大100条每页 |
| min_digg_count | 否 | int | 最小点赞数 |
| min_comment_count | 否 | int | 最小评论数 |
| min_share_count | 否 | int | 最小分享数 |
| min_duration | 否 | int | 最小时长，毫秒为单位 |




### 返回参数

```json
{
    "code": 200,
    "msg": "成功",
    "data": {
        "total": 5000,
        "per_page": 1,
        "current_page": 1,
        "last_page": 100,
        "data": [
            {
                "user_id": 104255897823,	//作者id
                "vid": 6865534331515964679,	//视频id
                "user_nickname": "人民日报",	//作者昵称
                "user_avatar": "https:\/\/p3-dy-ipv6.byteimg.com\/aweme\/100x100\/30ed2000aad26be101cad.jpeg?from=4010531038",	//作者头像
                "desc": "珍贵视频！9年前袁隆平院士和钟南山院士的同台。今天袁老90岁生日，生日快乐，也愿两位都健康快乐！",	//视频描述
                "uri": "v0200fd60000bt3ke2te6v18nvs8q5q0",	//视频资源定位id
                "cover": "http:\/\/p3-dy-ipv6.byteimg.com\/large\/tos-cn-p-0015\/e6240ccea8a84ff5a77b514ccdf00bc7_1598506787.webp?from=2563711402_large",	//视频封面
                "play_addr_mark": "https:\/\/aweme.snssdk.com\/aweme\/v1\/playwm?video_id=v0200fd60000bt3ke2te6v18nvs8q5q0",	//视频播放地址，带水印
                "duration": 23840,	//视频时长，毫秒
                "digg_count": 12119790,	//点赞数
                "comment_count": 315139,	//评论数
                "share_count": 76000,	//分享数
                "create_time": "2020-08-27 13:39:41",	//时间发布时间
                "category": "政企",	//分类，26个分类
                "tag": "社会"	//标签，可选项：搞笑、生活、社会
            }
        ]
    }
}
```
![](https://visitor-badge.laobi.icu/badge?page_id=Video-Hub.douyin-api)
