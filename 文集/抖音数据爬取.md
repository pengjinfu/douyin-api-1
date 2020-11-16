# 抖音数据爬取

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

<a name="i38qO"></a>
# 前言
在抖音APP中根据关键词爬取响应视频的具体信息，主要包括视频标题、作者ID、视频url地址以及点赞数等。
<a name="kIqbu"></a>
# 1 需要用到的工具

1. 安卓模拟器<br />
1. fiddler <br />
1. mituproxy(mitmdump)<br />
1. python3.7<br />
1. Auto.js<br />
<a name="zaUrK"></a>
# 2 环境准备
在PC端安装安卓模拟器，模拟器很多，可随便选一个款就可以，我用的是雷电模拟器，模拟器一般都是自带root的。模拟器安装好后，然后进行一下配置 。<br />首先在命令窗口中输入ipconfig获取本机IP（注意：如果电脑连接的是无线网，IP就会根据的你无线地址变化）<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/97322/1605509782858-a6ff451f-fc69-4f3a-b3d1-4c845e0bed6f.png#align=left&display=inline&height=722&margin=%5Bobject%20Object%5D&name=image.png&originHeight=722&originWidth=1464&size=169042&status=done&style=none&width=1464)<br />然后在设置模拟器代理（IP 要和上面的一致，不一致后面会导致APP不能上网）<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/97322/1605509836295-431509cb-5b51-456a-a129-bbcf9f34d7eb.png#align=left&display=inline&height=600&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1356&originWidth=882&size=207234&status=done&style=none&width=390)<br /> <br />安装fiddler，具体安装步骤参考度娘，本项目中fiddler主要是用来抓包查看抖音的数据格式。对fiddler进行一下设置<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/97322/1605509866727-7be7963c-5901-4a02-9b6e-f0f8ef348672.png#align=left&display=inline&height=281&margin=%5Bobject%20Object%5D&name=image.png&originHeight=712&originWidth=1470&size=420870&status=done&style=none&width=581)<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/97322/1605509883028-264c7e83-4d22-46df-bde0-8129767bb810.png#align=left&display=inline&height=303&margin=%5Bobject%20Object%5D&name=image.png&originHeight=662&originWidth=1072&size=112398&status=done&style=none&width=490)<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/97322/1605509908596-8a536010-7868-4736-bdd6-b571b25fc351.png#align=left&display=inline&height=300&margin=%5Bobject%20Object%5D&name=image.png&originHeight=648&originWidth=1072&size=129801&status=done&style=none&width=496)<br />接下来安装fiddler证书，在模拟器中的浏览器中输入本机IP和端口号，下载并安装证书<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/97322/1605509936511-d2c8dbb9-2e82-4c10-9cfb-a016d6ce8aee.png#align=left&display=inline&height=340&margin=%5Bobject%20Object%5D&name=image.png&originHeight=664&originWidth=884&size=182833&status=done&style=none&width=452)<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/97322/1605509957809-d6bbc74b-17f3-4c3c-83ac-faaaa68c0b4c.png#align=left&display=inline&height=558&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1346&originWidth=890&size=204727&status=done&style=none&width=369)<br />然后打开模拟器设置，开启桥接模式，不然后面会出现响应内容为空。<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/97322/1605509987623-5c3aa90c-7ffa-4005-8091-92bb3c5f5d02.png#align=left&display=inline&height=418&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1248&originWidth=1338&size=410516&status=done&style=none&width=448)<br />完成以上配置后，在命令行中输入mitmdump -p +端口号就可以启动服务了（注意：此时要关闭fiddler，不然会产生端口冲突）<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/97322/1605510008075-cc6f3537-0971-4e34-96b9-e8fa610e2e06.png#align=left&display=inline&height=249&margin=%5Bobject%20Object%5D&name=image.png&originHeight=716&originWidth=1458&size=147627&status=done&style=none&width=507)<br />为了是抖音能正常访问网络，还需要安装xposed框架的JustTrustMe组件<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/97322/1605510045494-a0c49e5b-0322-4015-baee-c6c113e67acb.png#align=left&display=inline&height=539&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1304&originWidth=890&size=186559&status=done&style=none&width=368)<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/97322/1605510065971-473b0b9d-374d-4b0a-b7cd-b68d17a5ac8a.png#align=left&display=inline&height=266&margin=%5Bobject%20Object%5D&name=image.png&originHeight=452&originWidth=884&size=85003&status=done&style=none&width=521)
<a name="cLHZU"></a>
# 3 数据获取
使用fiddler对抖音数据进行抓包，打开fiddler和抖音，向上滑动，获取更多视频，此时在fiddler中也会出现跟多的文件。找到POST请求中对抓到的数据进行分析，得到请求地址和数据格式。<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/97322/1605510093815-4cc213d5-9289-4f7c-b7ca-ee850fa88644.png#align=left&display=inline&height=296&margin=%5Bobject%20Object%5D&name=image.png&originHeight=686&originWidth=1474&size=1242507&status=done&style=none&width=636)<br />知道url地址和数据格式之后，编写python程序，使用mitmdump抓包，当滑动屏幕就可以解析出数据。代码如下：
```python
import json
import pandas as pd 
import csv
import jsonpath
 
#函数名必须这样写 这是mitmdump规则
def response(flow):
    #下面这个网址是通过fiddler获取到的 但是有些数据我们无法解密，所以需要用mitmdump捕获数据包然后做分析
    if 'api.amemv.com/aweme/v1/search/item' in flow.request.url:   
        #将json数据转换为python对象
        text = flow.response.text
        data_json = json.loads(text)     
        #解析数据
        for vedio in data_json.get('aweme_list'):       
            #构建有个空字典
            vedio_info={}
            #使用join去掉列表输出时存在的[]，元素名前加*也是为了去掉输出数据带的''
            #获取作者名字
            author_list = [str(i) for i in jsonpath.jsonpath(vedio,'$..nickname')]
            vedio_info['author_name'] = ''.join(*author_list)
            #获取视频的评论数
            comment_list = [str(i) for i in jsonpath.jsonpath(vedio,'$..comment_count')]
            vedio_info['comment'] = ''.join(*comment_list)
            #获取视频的点赞数
            digg_list = [str(i) for i in jsonpath.jsonpath(vedio,'$..digg_count')]
            vedio_info['digg'] = ''.join(*digg_list)
            
            #获取作者的ID         
            vedio_info['author_id'] = vedio['author_user_id']
            #获取视频的标题
            vedio_info['vedio_title'] = vedio['desc']
            #获取视频的url地址
            vedio_info['vedio_url'] = vedio['share_url'] 
            
            #打印视频的详细信息                      
            print(vedio_info)
                                                                                
            name_info = vedio_info['author_name'] 
            comment_info = vedio_info['comment']
            digg_info = vedio_info['digg']
            author_info = vedio_info['author_id']
            title_info = vedio_info['vedio_title']
            url_info = vedio_info['vedio_url']    
                                                
            
            #newline的作用是防止每次插入都有空行 
            with open("food.csv", "a+", encoding='utf8',newline='') as csvfile:
                writer = csv.writer(csvfile)
                #以读的方式打开csv 用csv.reader方式判断是否存在标题。
                with open("food.csv", "r", encoding='utf8',newline='') as f:
                    reader = csv.reader(f)
                    if not [row for row in reader]:
                        #先写入每一列的标题
                        writer.writerow(["name","author_id","comment_num","digg_num", "vedio_title", "vedio_url"])
                        #再写入每一列的内容
                        writer.writerows([[name_info,author_info,comment_info,digg_info,title_info,url_info]])
                    else:
                        writer.writerows([[name_info,author_info,comment_info,digg_info,title_info,url_info]])
```
关闭fiddler，在命令窗口进入到.py文件的路径中，使用命令mitmdump -p 8888 -s douyin_vedio.py 回车运行，手动滑动屏幕就可以不断解析出更多的数据。<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/97322/1605510143000-be70edde-9e55-4a17-83b2-4d4046e31433.png#align=left&display=inline&height=326&margin=%5Bobject%20Object%5D&name=image.png&originHeight=730&originWidth=1468&size=220317&status=done&style=none&width=656)<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/97322/1605510176740-3bda33a9-aacf-4361-b95e-34fb0e7680b4.png#align=left&display=inline&height=323&margin=%5Bobject%20Object%5D&name=image.png&originHeight=710&originWidth=1458&size=419561&status=done&style=none&width=664)<br />可以看到，上面已经得到了我们需要的内容，然后将数据存入到csv文件中。<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/97322/1605510189371-51e11dca-899e-475c-a0f0-01f5bf1af36d.png#align=left&display=inline&height=368&margin=%5Bobject%20Object%5D&name=image.png&originHeight=804&originWidth=1476&size=967270&status=done&style=none&width=675)
<a name="aKqgs"></a>
# 4 自动滑屏
如果数据量很大，手动滑动屏幕很麻烦，我们可以只用Appium进行自动化操作，实现包括打开抖音和自动滑屏等功能，我这里使用一个稍微简单的方法（实现功能就可以，手动狗头），使用Auto.js，编一些一个自动滑屏的脚本就可以实现自动滑屏了。要搞一下骚操作的话还是用Appium吧。<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/97322/1605510215842-a2249a59-3574-4943-a23d-18b3ebbdca9c.png#align=left&display=inline&height=475&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1338&originWidth=1170&size=222429&status=done&style=none&width=415)<br />自动滑屏脚本，很简单<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/97322/1605510253936-d7f1b05e-d1e7-4d2f-9d87-b2bfca85f305.png#align=left&display=inline&height=229&margin=%5Bobject%20Object%5D&name=image.png&originHeight=412&originWidth=1048&size=144983&status=done&style=none&width=582)<br />

```python
while(true){
    Swipe(device.width/2,1300,device.width/2,300,2000);
    sleep(2000)}
```
打开Auto.js悬浮按钮，在抖音中运行自动滑屏脚本就可以了（注意：在Auto.js的设置中打开音量上键关闭停止所有脚本，不然会一致滑屏就无法正常使用模拟器了）<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/97322/1605510266656-99baf6ec-3a84-4ac9-bf28-737a142d8e03.png#align=left&display=inline&height=490&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1352&originWidth=1062&size=501375&status=done&style=none&width=385)<br />打开脚本后就可以看到视频在自动的滑动了。
<a name="Sqf9o"></a>
# 5 总结
大神们请略过，像我这种初学爬虫的弟弟，还是需要更多的耐心去学习。安装各种软件、配置环境和编写程序都会遇到各种各样的问题，重启可以解决百分之八九十的电脑故障问题，找度娘也可以解决你绝大多的问题，不管遇到什么问题就找度娘吧（看病除外）。<br />

