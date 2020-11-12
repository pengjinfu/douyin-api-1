# 抖音直播监控Api：开播查询


### TiToData：专业的短视频数据采集、处理平台。
> 更多信息请联系： [TiToData](https://www.titodata.com/about?from=zhiboapi)
> 海量数据采集
> 每天为客户采集5亿条数据
> 覆盖主流平台：TikTok，Zynn，YouTube，抖音，快手，1688，小红书，拼多多，淘宝，美团，饿了么，淘宝，微博




### 请求Api
```http
http://主机地址/douyin/liveroom/status?token=xxx&room_id=6843198199583378191,6872323400263797518
```

### 

### 请求方式
```http
GET
```

### 

### 参数
| 字段 | 类型 | 说明 |
| --- | --- | --- |
| token | string | 接口授权码 |
| room_id | int | 直播间id |


### 

### 返回示例
```json

{
  "code": 200,
  "data": {
    "data": [
      {
        "alive": false,
        "room_id": 6843198199583378191
      },
      {
        "alive": true,
        "room_id": 6872323400263797518
      }
    ],
    "extra": {
      "now": 1600096174925
    },
    "status_code": 0
  },
  "msg": "success"
}
```
