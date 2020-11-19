# 抖音榜单Api：热点榜

## 抖音视频Api、抖音直播Api、抖音评论采集、抖音弹幕采集、抖音爬虫、抖音去水印、抖音视频下载、抖音视频解析
## 抖音直播数据、抖音数据采集、抖音直播监控

#### TiToData：专业的短视频数据采集、处理平台。
> 更多信息请联系： [TiToData](https://www.titodata.com/about?from=douyinbangdan)
```
海量数据采集
每天为客户采集5亿条数据
覆盖主流平台：TikTok，Zynn，YouTube，抖音，快手，1688，小红书，拼多多，淘宝，美团，饿了么，淘宝，微博

```


## 抖音榜单：热点榜

### 请求Api
```http
http://主机地址/douyin/board/hot?token=xxx

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


### 

### 返回示例
```json

{
  "code": 200,
  "data": {
    "ad_search_list": null,
    "data": {
      "active_time": "2020-09-14 23:20:13",
      "recommend_list": null,
      "share_info": {
        "share_link_desc": "我在看抖音热榜，发现最火的内容，赶快来看！戳这里>>",
        "share_title": "我在看抖音热榜，发现最火的内容，赶快来看！",
        "share_url": "https://www.iesdouyin.com/share/billboard/?id=0"
      },
      "trending_desc": "实时上升热点",
      "trending_list": [
        {
          "group_id": "6871001533455996173",
          "label": 0,
          "related_words": null,
          "sentence_id": "0xc04d280e90",
          "video_count": 1,
          "word": "美警察追捕搞错地址砸错门",
          "word_cover": {
            "uri": "tos-cn-p-0015/ce4cba031210468f95bb6a3c9f192193_1600067077",
            "url_list": [
              "https://p26-dy.byteimg.com/img/tos-cn-p-0015/ce4cba031210468f95bb6a3c9f192193_1600067077~noop.jpeg?from=3218412987",
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/ce4cba031210468f95bb6a3c9f192193_1600067077~noop.jpeg?from=3218412987",
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/ce4cba031210468f95bb6a3c9f192193_1600067077~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 3
        },
        {
          "group_id": "6870862304994874632",
          "label": 0,
          "related_words": null,
          "sentence_id": "0xc04d280f20",
          "video_count": 2,
          "word": "男子好心救援被困房车反遭拒绝",
          "word_cover": {
            "uri": "tos-cn-p-0015/bc0610a7f6934b5f92575ca90a129338",
            "url_list": [
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/bc0610a7f6934b5f92575ca90a129338~noop.jpeg?from=3218412987",
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/bc0610a7f6934b5f92575ca90a129338~noop.jpeg?from=3218412987",
              "https://p26-dy.byteimg.com/img/tos-cn-p-0015/bc0610a7f6934b5f92575ca90a129338~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 3
        },
        {
          "group_id": "6870335832144712972",
          "label": 0,
          "related_words": null,
          "sentence_id": "0xc04d280fb0",
          "video_count": 1,
          "word": "这就是街舞3决赛夜神秘嘉宾",
          "word_cover": {
            "uri": "tos-cn-p-0015/4ded911d77ff4072855bbd2698931c33",
            "url_list": [
              "https://p26-dy.byteimg.com/img/tos-cn-p-0015/4ded911d77ff4072855bbd2698931c33~noop.jpeg?from=3218412987",
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/4ded911d77ff4072855bbd2698931c33~noop.jpeg?from=3218412987",
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/4ded911d77ff4072855bbd2698931c33~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 3
        },
        {
          "group_id": "6870978388007621901",
          "label": 0,
          "related_words": null,
          "sentence_id": "0xc04d281040",
          "video_count": 1,
          "word": "近1000家景区实行免费打折政策",
          "word_cover": {
            "uri": "tos-cn-p-0015/2ec676a6778441a0aa84b3b9ed97f38e",
            "url_list": [
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/2ec676a6778441a0aa84b3b9ed97f38e~noop.jpeg?from=3218412987",
              "https://p9-dy.byteimg.com/img/tos-cn-p-0015/2ec676a6778441a0aa84b3b9ed97f38e~noop.jpeg?from=3218412987",
              "https://p26-dy.byteimg.com/img/tos-cn-p-0015/2ec676a6778441a0aa84b3b9ed97f38e~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 3
        },
        {
          "group_id": "6870948419101463816",
          "label": 0,
          "related_words": null,
          "sentence_id": "0xc04d2810d0",
          "video_count": 1,
          "word": "焦作举办第三季度消防比武竞赛",
          "word_cover": {
            "uri": "tos-cn-p-0015/9cbc76a4e79a4df5ae47390d68a61367_1600069460",
            "url_list": [
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/9cbc76a4e79a4df5ae47390d68a61367_1600069460~noop.jpeg?from=3218412987",
              "https://p26-dy.byteimg.com/img/tos-cn-p-0015/9cbc76a4e79a4df5ae47390d68a61367_1600069460~noop.jpeg?from=3218412987",
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/9cbc76a4e79a4df5ae47390d68a61367_1600069460~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 3
        }
      ],
      "word_list": [
        {
          "can_extend_detail": false,
          "challenge_id": "",
          "event_time": 1599993150,
          "group_id": "6870421703589549319",
          "hot_value": 8782523,
          "label": 5,
          "position": 1,
          "related_words": null,
          "sentence_id": "123223",
          "video_count": 3,
          "word": "李心艾回应胖了",
          "word_cover": {
            "uri": "tos-cn-p-0015/7004540786d54652932bd083ceaf5048_1599992729",
            "url_list": [
              "https://p9-dy.byteimg.com/img/tos-cn-p-0015/7004540786d54652932bd083ceaf5048_1599992729~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/7004540786d54652932bd083ceaf5048_1599992729~noop.jpeg?from=3218412987",
              "https://p26-dy.byteimg.com/img/tos-cn-p-0015/7004540786d54652932bd083ceaf5048_1599992729~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1600073839,
          "group_id": "6727600448598971661",
          "hot_value": 8671307,
          "label": 0,
          "position": 2,
          "related_words": null,
          "sentence_id": "123795",
          "video_count": 4,
          "word": "我喜欢你定档",
          "word_cover": {
            "uri": "tos-cn-p-0015/a74429fb1595415182651b508ea4a3ff",
            "url_list": [
              "https://p26-dy.byteimg.com/img/tos-cn-p-0015/a74429fb1595415182651b508ea4a3ff~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/a74429fb1595415182651b508ea4a3ff~noop.jpeg?from=3218412987",
              "https://p9-dy.byteimg.com/img/tos-cn-p-0015/a74429fb1595415182651b508ea4a3ff~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "can_extend_detail": true,
          "challenge_id": "",
          "event_time": 1600052975,
          "group_id": "6860030767771178248",
          "hot_value": 7701067,
          "label": 3,
          "position": 3,
          "related_words": null,
          "sentence_id": "123319",
          "video_count": 12,
          "word": "首部抗疫题材电视剧",
          "word_cover": {
            "uri": "tos-cn-p-0015/9bdb877e31b444c78bdb58cbc96c3a45_1599996711",
            "url_list": [
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/9bdb877e31b444c78bdb58cbc96c3a45_1599996711~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/9bdb877e31b444c78bdb58cbc96c3a45_1599996711~noop.jpeg?from=3218412987",
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/9bdb877e31b444c78bdb58cbc96c3a45_1599996711~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1600072448,
          "group_id": "6870335999172564235",
          "hot_value": 7401707,
          "label": 3,
          "position": 4,
          "related_words": null,
          "sentence_id": "123734",
          "video_count": 1,
          "word": "孙弈秋成为八卦中心",
          "word_cover": {
            "uri": "tos-cn-p-0015/8b047893604f48ac8c8bf78ff8374908_1599968744",
            "url_list": [
              "https://p26-dy.byteimg.com/img/tos-cn-p-0015/8b047893604f48ac8c8bf78ff8374908_1599968744~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/8b047893604f48ac8c8bf78ff8374908_1599968744~noop.jpeg?from=3218412987",
              "https://p9-dy.byteimg.com/img/tos-cn-p-0015/8b047893604f48ac8c8bf78ff8374908_1599968744~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1600059643,
          "group_id": "6870707109018391821",
          "hot_value": 7296853,
          "label": 0,
          "position": 5,
          "related_words": null,
          "sentence_id": "123397",
          "video_count": 4,
          "word": "李汶翰多位前任发文",
          "word_cover": {
            "uri": "tos-cn-p-0015/7f61e9689d684674bee88e48adcef7d5",
            "url_list": [
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/7f61e9689d684674bee88e48adcef7d5~noop.jpeg?from=3218412987",
              "https://p9-dy.byteimg.com/img/tos-cn-p-0015/7f61e9689d684674bee88e48adcef7d5~noop.jpeg?from=3218412987",
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/7f61e9689d684674bee88e48adcef7d5~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1599966564,
          "group_id": "6870331092336235788",
          "hot_value": 7056523,
          "label": 3,
          "position": 6,
          "related_words": null,
          "sentence_id": "122868",
          "video_count": 5,
          "word": "baby版画画的baby",
          "word_cover": {
            "uri": "tos-cn-p-0015/76753804057944a98f062c31057f2e1c",
            "url_list": [
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/76753804057944a98f062c31057f2e1c~noop.jpeg?from=3218412987",
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/76753804057944a98f062c31057f2e1c~noop.jpeg?from=3218412987",
              "https://p9-dy.byteimg.com/img/tos-cn-p-0015/76753804057944a98f062c31057f2e1c~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1600072613,
          "group_id": "6870924357356918030",
          "hot_value": 6839907,
          "label": 3,
          "position": 7,
          "related_words": null,
          "sentence_id": "123740",
          "video_count": 5,
          "word": "易烊千玺 上线吧华彩少年",
          "word_cover": {
            "uri": "tos-cn-p-0015/2248cad113624bc282f3ca7a219e6b0d",
            "url_list": [
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/2248cad113624bc282f3ca7a219e6b0d~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/2248cad113624bc282f3ca7a219e6b0d~noop.jpeg?from=3218412987",
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/2248cad113624bc282f3ca7a219e6b0d~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1599974176,
          "group_id": "6870331056583742731",
          "hot_value": 6814765,
          "label": 3,
          "position": 8,
          "related_words": null,
          "sentence_id": "122969",
          "video_count": 1,
          "word": "清华大学新生高考分数大揭秘",
          "word_cover": {
            "uri": "tos-cn-p-0015/370a784972e942ea8cc90467bd374f37_1599909904",
            "url_list": [
              "https://p9-dy.byteimg.com/img/tos-cn-p-0015/370a784972e942ea8cc90467bd374f37_1599909904~noop.jpeg?from=3218412987",
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/370a784972e942ea8cc90467bd374f37_1599909904~noop.jpeg?from=3218412987",
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/370a784972e942ea8cc90467bd374f37_1599909904~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1599971320,
          "group_id": "6870476162008519943",
          "hot_value": 6726356,
          "label": 3,
          "position": 9,
          "related_words": null,
          "sentence_id": "122958",
          "video_count": 1,
          "word": "焉栩嘉 不要老是给我过度修图",
          "word_cover": {
            "uri": "tos-cn-p-0015/e34b2f2f19c24d59bff9301400666291",
            "url_list": [
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/e34b2f2f19c24d59bff9301400666291~noop.jpeg?from=3218412987",
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/e34b2f2f19c24d59bff9301400666291~noop.jpeg?from=3218412987",
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/e34b2f2f19c24d59bff9301400666291~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "can_extend_detail": true,
          "challenge_id": "",
          "event_time": 1599966613,
          "group_id": "6870442454777910535",
          "hot_value": 6573571,
          "label": 3,
          "position": 10,
          "related_words": null,
          "sentence_id": "122869",
          "video_count": 2,
          "word": "沈梦辰回应耍大牌",
          "word_cover": {
            "uri": "tos-cn-p-0015/30d048da398348abbf0ac681de64f083_1599968701",
            "url_list": [
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/30d048da398348abbf0ac681de64f083_1599968701~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/30d048da398348abbf0ac681de64f083_1599968701~noop.jpeg?from=3218412987",
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/30d048da398348abbf0ac681de64f083_1599968701~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1599965906,
          "group_id": "6870336347548734733",
          "hot_value": 6543468,
          "label": 3,
          "position": 11,
          "related_words": null,
          "sentence_id": "122851",
          "video_count": 2,
          "word": "王源用糖画写自己名字",
          "word_cover": {
            "uri": "tos-cn-p-0015/ea0118927bff4a7ba12a7a534f91a34e_1599907291",
            "url_list": [
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/ea0118927bff4a7ba12a7a534f91a34e_1599907291~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/ea0118927bff4a7ba12a7a534f91a34e_1599907291~noop.jpeg?from=3218412987",
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/ea0118927bff4a7ba12a7a534f91a34e_1599907291~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1599979626,
          "group_id": "6659696456422659331",
          "hot_value": 6347707,
          "label": 3,
          "position": 12,
          "related_words": null,
          "sentence_id": "123041",
          "video_count": 1,
          "word": "药水哥复活",
          "word_cover": {
            "uri": "tos-cn-p-0015/42b8f2397aee405a9b328c30e70149c9",
            "url_list": [
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/42b8f2397aee405a9b328c30e70149c9~noop.jpeg?from=3218412987",
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/42b8f2397aee405a9b328c30e70149c9~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/42b8f2397aee405a9b328c30e70149c9~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1600073934,
          "group_id": "6870328194958365960",
          "hot_value": 6288708,
          "label": 0,
          "position": 13,
          "related_words": null,
          "sentence_id": "123802",
          "video_count": 1,
          "word": "angelababy豌豆公主封面",
          "word_cover": {
            "uri": "tos-cn-p-0015/b3e26a8eb00a41af85345c4e7272eccc",
            "url_list": [
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/b3e26a8eb00a41af85345c4e7272eccc~noop.jpeg?from=3218412987",
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/b3e26a8eb00a41af85345c4e7272eccc~noop.jpeg?from=3218412987",
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/b3e26a8eb00a41af85345c4e7272eccc~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1599982818,
          "group_id": "6870500058912593166",
          "hot_value": 6205586,
          "label": 3,
          "position": 14,
          "related_words": null,
          "sentence_id": "123087",
          "video_count": 4,
          "word": "灰尘男友拆穿渣男套路",
          "word_cover": {
            "uri": "tos-cn-p-0015/837b61054bc04c6681dcf4f84e7c46a0",
            "url_list": [
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/837b61054bc04c6681dcf4f84e7c46a0~noop.jpeg?from=3218412987",
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/837b61054bc04c6681dcf4f84e7c46a0~noop.jpeg?from=3218412987",
              "https://p26-dy.byteimg.com/img/tos-cn-p-0015/837b61054bc04c6681dcf4f84e7c46a0~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1600074246,
          "group_id": "6870619476136662286",
          "hot_value": 6134166,
          "label": 0,
          "position": 15,
          "related_words": null,
          "sentence_id": "123824",
          "video_count": 1,
          "word": "吴亦凡问郑爽为什么来潮流节目",
          "word_cover": {
            "uri": "tos-cn-p-0015/720796fff13b46938b4a0eaf8809a202",
            "url_list": [
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/720796fff13b46938b4a0eaf8809a202~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/720796fff13b46938b4a0eaf8809a202~noop.jpeg?from=3218412987",
              "https://p26-dy.byteimg.com/img/tos-cn-p-0015/720796fff13b46938b4a0eaf8809a202~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "can_extend_detail": false,
          "challenge_id": "",
          "event_time": 1599966679,
          "group_id": "6860889202301605133",
          "hot_value": 6126526,
          "label": 0,
          "position": 16,
          "related_words": null,
          "sentence_id": "122872",
          "video_count": 4,
          "word": "花木兰票房破亿",
          "word_cover": {
            "uri": "tos-cn-p-0015/d1f51e9391c24242aa8a0a55e73b5c43",
            "url_list": [
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/d1f51e9391c24242aa8a0a55e73b5c43~noop.jpeg?from=3218412987",
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/d1f51e9391c24242aa8a0a55e73b5c43~noop.jpeg?from=3218412987",
              "https://p26-dy.byteimg.com/img/tos-cn-p-0015/d1f51e9391c24242aa8a0a55e73b5c43~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1599965927,
          "group_id": "6609600988099695875",
          "hot_value": 5983398,
          "label": 0,
          "position": 17,
          "related_words": null,
          "sentence_id": "122852",
          "video_count": 2,
          "word": "汪苏泷 岁月神偷",
          "word_cover": {
            "uri": "tos-cn-p-0015/36b08a5cbda3482a8f9425b5508ae2c9_1599915555",
            "url_list": [
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/36b08a5cbda3482a8f9425b5508ae2c9_1599915555~noop.jpeg?from=3218412987",
              "https://p26-dy.byteimg.com/img/tos-cn-p-0015/36b08a5cbda3482a8f9425b5508ae2c9_1599915555~noop.jpeg?from=3218412987",
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/36b08a5cbda3482a8f9425b5508ae2c9_1599915555~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1599983883,
          "group_id": "6858427128623404299",
          "hot_value": 5976594,
          "label": 0,
          "position": 18,
          "related_words": null,
          "sentence_id": "123123",
          "video_count": 5,
          "word": "成毅泡澡花絮",
          "word_cover": {
            "uri": "tos-cn-p-0015/27896bc102384484b2e5eeac4f90a119_1599980810",
            "url_list": [
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/27896bc102384484b2e5eeac4f90a119_1599980810~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/27896bc102384484b2e5eeac4f90a119_1599980810~noop.jpeg?from=3218412987",
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/27896bc102384484b2e5eeac4f90a119_1599980810~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1600070245,
          "group_id": "6870886729080100104",
          "hot_value": 5962279,
          "label": 0,
          "position": 19,
          "related_words": null,
          "sentence_id": "123672",
          "video_count": 12,
          "word": "爱的变装秀",
          "word_cover": {
            "uri": "tos-cn-p-0015/790310c0f8224eb4a01f0da5ad1d3206",
            "url_list": [
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/790310c0f8224eb4a01f0da5ad1d3206~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/790310c0f8224eb4a01f0da5ad1d3206~noop.jpeg?from=3218412987",
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/790310c0f8224eb4a01f0da5ad1d3206~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1600056018,
          "group_id": "6841788195126908167",
          "hot_value": 5843330,
          "label": 0,
          "position": 20,
          "related_words": null,
          "sentence_id": "123387",
          "video_count": 119,
          "word": "爱的恰恰舞挑战赛",
          "word_cover": {
            "uri": "tos-cn-p-0015/d0f3dc2180cf44c291e9bf31490b3aec_1599820890",
            "url_list": [
              "https://p9-dy.byteimg.com/img/tos-cn-p-0015/d0f3dc2180cf44c291e9bf31490b3aec_1599820890~noop.jpeg?from=3218412987",
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/d0f3dc2180cf44c291e9bf31490b3aec_1599820890~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/d0f3dc2180cf44c291e9bf31490b3aec_1599820890~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1600054593,
          "group_id": "6652444292411299076",
          "hot_value": 5669350,
          "label": 0,
          "position": 21,
          "related_words": null,
          "sentence_id": "123372",
          "video_count": 3,
          "word": "易烊千玺狗啃刘海",
          "word_cover": {
            "uri": "tos-cn-p-0015/df94a8ff3be642248f83491dc6642fac_1599999787",
            "url_list": [
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/df94a8ff3be642248f83491dc6642fac_1599999787~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/df94a8ff3be642248f83491dc6642fac_1599999787~noop.jpeg?from=3218412987",
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/df94a8ff3be642248f83491dc6642fac_1599999787~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "can_extend_detail": true,
          "challenge_id": "",
          "event_time": 1600053563,
          "group_id": "6574875508830377220",
          "hot_value": 5623356,
          "label": 0,
          "position": 22,
          "related_words": null,
          "sentence_id": "123345",
          "video_count": 1,
          "word": "李现腹肌",
          "word_cover": {
            "uri": "tos-cn-p-0015/6bb725902b06478580fe6947f2548cf8_1600013737",
            "url_list": [
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/6bb725902b06478580fe6947f2548cf8_1600013737~noop.jpeg?from=3218412987",
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/6bb725902b06478580fe6947f2548cf8_1600013737~noop.jpeg?from=3218412987",
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/6bb725902b06478580fe6947f2548cf8_1600013737~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1599963782,
          "group_id": "6870336295757337864",
          "hot_value": 5577403,
          "label": 0,
          "position": 23,
          "related_words": null,
          "sentence_id": "122789",
          "video_count": 4,
          "word": "王源黑色印花西装",
          "word_cover": {
            "uri": "tos-cn-p-0015/54b4f6e2d0194921a9b609710038e5c7",
            "url_list": [
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/54b4f6e2d0194921a9b609710038e5c7~noop.jpeg?from=3218412987",
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/54b4f6e2d0194921a9b609710038e5c7~noop.jpeg?from=3218412987",
              "https://p26-dy.byteimg.com/img/tos-cn-p-0015/54b4f6e2d0194921a9b609710038e5c7~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1600072970,
          "group_id": "6870331250763339011",
          "hot_value": 5566264,
          "label": 0,
          "position": 24,
          "related_words": null,
          "sentence_id": "123753",
          "video_count": 1,
          "word": "男子持刀追砍第三者",
          "word_cover": {
            "uri": "tos-cn-p-0015/621b187ec8f14be999812c4696d401e2",
            "url_list": [
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/621b187ec8f14be999812c4696d401e2~noop.jpeg?from=3218412987",
              "https://p26-dy.byteimg.com/img/tos-cn-p-0015/621b187ec8f14be999812c4696d401e2~noop.jpeg?from=3218412987",
              "https://p9-dy.byteimg.com/img/tos-cn-p-0015/621b187ec8f14be999812c4696d401e2~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "can_extend_detail": true,
          "challenge_id": "",
          "event_time": 1600051372,
          "group_id": "6870827714577241351",
          "hot_value": 5553958,
          "label": 0,
          "position": 25,
          "related_words": null,
          "sentence_id": "123293",
          "video_count": 2,
          "word": "内马尔控诉对手种族歧视",
          "word_cover": {
            "uri": "tos-cn-p-0015/ce44110ea6cb49c39e43af12f029e9a8_1600050167",
            "url_list": [
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/ce44110ea6cb49c39e43af12f029e9a8_1600050167~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/ce44110ea6cb49c39e43af12f029e9a8_1600050167~noop.jpeg?from=3218412987",
              "https://p9-dy.byteimg.com/img/tos-cn-p-0015/ce44110ea6cb49c39e43af12f029e9a8_1600050167~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "can_extend_detail": false,
          "challenge_id": "",
          "event_time": 1599963079,
          "group_id": "6870336445996619015",
          "hot_value": 5464887,
          "label": 0,
          "position": 26,
          "related_words": null,
          "sentence_id": "122774",
          "video_count": 2,
          "word": "王一博被苏恋雅吓到",
          "word_cover": {
            "uri": "tos-cn-p-0015/a4b34ce273fd40f4a0e9d04322fc78ec",
            "url_list": [
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/a4b34ce273fd40f4a0e9d04322fc78ec~noop.jpeg?from=3218412987",
              "https://p26-dy.byteimg.com/img/tos-cn-p-0015/a4b34ce273fd40f4a0e9d04322fc78ec~noop.jpeg?from=3218412987",
              "https://p9-dy.byteimg.com/img/tos-cn-p-0015/a4b34ce273fd40f4a0e9d04322fc78ec~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1600058775,
          "group_id": "6870333235470341380",
          "hot_value": 5226055,
          "label": 0,
          "position": 27,
          "related_words": null,
          "sentence_id": "123396",
          "video_count": 10,
          "word": "重启第二季听雷小队",
          "word_cover": {
            "uri": "tos-cn-p-0015/e23c141d08f84568abe5c3eeb62b07c2_1600006421",
            "url_list": [
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/e23c141d08f84568abe5c3eeb62b07c2_1600006421~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/e23c141d08f84568abe5c3eeb62b07c2_1600006421~noop.jpeg?from=3218412987",
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/e23c141d08f84568abe5c3eeb62b07c2_1600006421~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1600053440,
          "group_id": "6870809749081822472",
          "hot_value": 5179834,
          "label": 0,
          "position": 28,
          "related_words": null,
          "sentence_id": "123343",
          "video_count": 1,
          "word": "虞书欣翻不过去跟头",
          "word_cover": {
            "uri": "tos-cn-p-0015/76db0fbdb51a4efe9656ca0d1a422359",
            "url_list": [
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/76db0fbdb51a4efe9656ca0d1a422359~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/76db0fbdb51a4efe9656ca0d1a422359~noop.jpeg?from=3218412987",
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/76db0fbdb51a4efe9656ca0d1a422359~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "can_extend_detail": true,
          "challenge_id": "",
          "event_time": 1599966193,
          "group_id": "6870334153968473358",
          "hot_value": 5032159,
          "label": 0,
          "position": 29,
          "related_words": null,
          "sentence_id": "122858",
          "video_count": 2,
          "word": "朴树 以后不会再当老师了",
          "word_cover": {
            "uri": "tos-cn-p-0015/31393cc4f33846afae6c4fed9054ecfa",
            "url_list": [
              "https://p9-dy.byteimg.com/img/tos-cn-p-0015/31393cc4f33846afae6c4fed9054ecfa~noop.jpeg?from=3218412987",
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/31393cc4f33846afae6c4fed9054ecfa~noop.jpeg?from=3218412987",
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/31393cc4f33846afae6c4fed9054ecfa~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "can_extend_detail": true,
          "challenge_id": "",
          "event_time": 1600071593,
          "group_id": "6867533249142248716",
          "hot_value": 5024375,
          "label": 0,
          "position": 30,
          "related_words": null,
          "sentence_id": "123704",
          "video_count": 1,
          "word": "药水哥放弃复活",
          "word_cover": {
            "uri": "tos-cn-p-0015/65f883d60a9744d4a3e94b65e6dbcc98_1599987799",
            "url_list": [
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/65f883d60a9744d4a3e94b65e6dbcc98_1599987799~noop.jpeg?from=3218412987",
              "https://p9-dy.byteimg.com/img/tos-cn-p-0015/65f883d60a9744d4a3e94b65e6dbcc98_1599987799~noop.jpeg?from=3218412987",
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/65f883d60a9744d4a3e94b65e6dbcc98_1599987799~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1600052903,
          "group_id": "6870733658765677837",
          "hot_value": 5018390,
          "label": 0,
          "position": 31,
          "related_words": null,
          "sentence_id": "123317",
          "video_count": 1,
          "word": "雷佳音贾乃亮唱迪丽热巴",
          "word_cover": {
            "uri": "tos-cn-p-0015/70f96bb807e84cf58991ddbaab6282b0",
            "url_list": [
              "https://p9-dy.byteimg.com/img/tos-cn-p-0015/70f96bb807e84cf58991ddbaab6282b0~noop.jpeg?from=3218412987",
              "https://p26-dy.byteimg.com/img/tos-cn-p-0015/70f96bb807e84cf58991ddbaab6282b0~noop.jpeg?from=3218412987",
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/70f96bb807e84cf58991ddbaab6282b0~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1600069302,
          "group_id": "6783609234119464199",
          "hot_value": 4847371,
          "label": 0,
          "position": 32,
          "related_words": null,
          "sentence_id": "123644",
          "video_count": 5,
          "word": "李现出演夺冠",
          "word_cover": {
            "uri": "tos-cn-p-0015/d24485e5b1e04589a6abe44f90120c87_1600063590",
            "url_list": [
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/d24485e5b1e04589a6abe44f90120c87_1600063590~noop.jpeg?from=3218412987",
              "https://p26-dy.byteimg.com/img/tos-cn-p-0015/d24485e5b1e04589a6abe44f90120c87_1600063590~noop.jpeg?from=3218412987",
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/d24485e5b1e04589a6abe44f90120c87_1600063590~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "can_extend_detail": true,
          "challenge_id": "",
          "event_time": 1600067149,
          "group_id": "6870836252841923847",
          "hot_value": 4833962,
          "label": 0,
          "position": 33,
          "related_words": null,
          "sentence_id": "123589",
          "video_count": 1,
          "word": "向佐回应没陪郭碧婷待产",
          "word_cover": {
            "uri": "tos-cn-p-0015/5f79be2db31f437eb3afd6b427c2f477",
            "url_list": [
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/5f79be2db31f437eb3afd6b427c2f477~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/5f79be2db31f437eb3afd6b427c2f477~noop.jpeg?from=3218412987",
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/5f79be2db31f437eb3afd6b427c2f477~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "can_extend_detail": false,
          "challenge_id": "",
          "event_time": 1600063930,
          "group_id": "6870322401289704716",
          "hot_value": 4832308,
          "label": 0,
          "position": 34,
          "related_words": null,
          "sentence_id": "123486",
          "video_count": 1,
          "word": "黄子韬爸爸追悼会",
          "word_cover": {
            "uri": "tos-cn-p-0015/73f135bd1ab34f3d9fb3c292b5f3c7a2",
            "url_list": [
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/73f135bd1ab34f3d9fb3c292b5f3c7a2~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/73f135bd1ab34f3d9fb3c292b5f3c7a2~noop.jpeg?from=3218412987",
              "https://p26-dy.byteimg.com/img/tos-cn-p-0015/73f135bd1ab34f3d9fb3c292b5f3c7a2~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1599975389,
          "group_id": "6870332313344005390",
          "hot_value": 4805388,
          "label": 0,
          "position": 35,
          "related_words": null,
          "sentence_id": "122992",
          "video_count": 22,
          "word": "军训比舞大赛",
          "word_cover": {
            "uri": "tos-cn-p-0015/d4aa875f10724caf9f5d13db36a36bfe",
            "url_list": [
              "https://p9-dy.byteimg.com/img/tos-cn-p-0015/d4aa875f10724caf9f5d13db36a36bfe~noop.jpeg?from=3218412987",
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/d4aa875f10724caf9f5d13db36a36bfe~noop.jpeg?from=3218412987",
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/d4aa875f10724caf9f5d13db36a36bfe~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "can_extend_detail": true,
          "challenge_id": "",
          "event_time": 1600051218,
          "group_id": "6712063427679884547",
          "hot_value": 4690803,
          "label": 0,
          "position": 36,
          "related_words": null,
          "sentence_id": "123290",
          "video_count": 21,
          "word": "掘金19分逆转",
          "word_cover": {
            "uri": "tos-cn-p-0015/5a68e409a2f94c7db4dfb12bd6c5eb13",
            "url_list": [
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/5a68e409a2f94c7db4dfb12bd6c5eb13~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/5a68e409a2f94c7db4dfb12bd6c5eb13~noop.jpeg?from=3218412987",
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/5a68e409a2f94c7db4dfb12bd6c5eb13~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "can_extend_detail": false,
          "challenge_id": "",
          "event_time": 1599964420,
          "group_id": "6870404418421576968",
          "hot_value": 4530540,
          "label": 0,
          "position": 37,
          "related_words": null,
          "sentence_id": "122806",
          "video_count": 3,
          "word": "告白失败大喊王俊凯来了",
          "word_cover": {
            "uri": "tos-cn-p-0015/a2cd04057d1c470d9ba9d5a60993fdec",
            "url_list": [
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/a2cd04057d1c470d9ba9d5a60993fdec~noop.jpeg?from=3218412987",
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/a2cd04057d1c470d9ba9d5a60993fdec~noop.jpeg?from=3218412987",
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/a2cd04057d1c470d9ba9d5a60993fdec~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1600066948,
          "group_id": "6870833998140314893",
          "hot_value": 3913637,
          "label": 0,
          "position": 38,
          "related_words": null,
          "sentence_id": "123574",
          "video_count": 1,
          "word": "夫妻捡来聋哑流浪汉照顾26年",
          "word_cover": {
            "uri": "tos-cn-p-0015/426027a06b5e4e9788902cc4ece6c39e_1600054111",
            "url_list": [
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/426027a06b5e4e9788902cc4ece6c39e_1600054111~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/426027a06b5e4e9788902cc4ece6c39e_1600054111~noop.jpeg?from=3218412987",
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/426027a06b5e4e9788902cc4ece6c39e_1600054111~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1600075288,
          "group_id": "6870335475686118667",
          "hot_value": 3863977,
          "label": 0,
          "position": 39,
          "related_words": null,
          "sentence_id": "123843",
          "video_count": 1,
          "word": "孙兴慜寄语武磊",
          "word_cover": {
            "uri": "tos-cn-p-0015/ba1d00fbfe304da1893e495c57fe08cf",
            "url_list": [
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/ba1d00fbfe304da1893e495c57fe08cf~noop.jpeg?from=3218412987",
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/ba1d00fbfe304da1893e495c57fe08cf~noop.jpeg?from=3218412987",
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/ba1d00fbfe304da1893e495c57fe08cf~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1600067089,
          "group_id": "6870335781849847044",
          "hot_value": 3804432,
          "label": 0,
          "position": 40,
          "related_words": null,
          "sentence_id": "123584",
          "video_count": 1,
          "word": "老人吃50个饺子老板分文未收",
          "word_cover": {
            "uri": "tos-cn-p-0015/75af1cb60e6440bc94a27179e10aba53",
            "url_list": [
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/75af1cb60e6440bc94a27179e10aba53~noop.jpeg?from=3218412987",
              "https://p9-dy.byteimg.com/img/tos-cn-p-0015/75af1cb60e6440bc94a27179e10aba53~noop.jpeg?from=3218412987",
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/75af1cb60e6440bc94a27179e10aba53~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "can_extend_detail": true,
          "challenge_id": "",
          "event_time": 1599969867,
          "group_id": "6858016893794522375",
          "hot_value": 3803367,
          "label": 0,
          "position": 41,
          "related_words": null,
          "sentence_id": "122922",
          "video_count": 24,
          "word": "重启第二季开播",
          "word_cover": {
            "uri": "tos-cn-p-0015/dbb567abd0b9475a9094221a398b4125",
            "url_list": [
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/dbb567abd0b9475a9094221a398b4125~noop.jpeg?from=3218412987",
              "https://p26-dy.byteimg.com/img/tos-cn-p-0015/dbb567abd0b9475a9094221a398b4125~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/dbb567abd0b9475a9094221a398b4125~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1600073260,
          "group_id": "6870939234296894728",
          "hot_value": 3748050,
          "label": 0,
          "position": 42,
          "related_words": null,
          "sentence_id": "123761",
          "video_count": 1,
          "word": "郑爽说自己是新人",
          "word_cover": {
            "uri": "tos-cn-p-0015/148828fd578b474cba7dc16e973299a3",
            "url_list": [
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/148828fd578b474cba7dc16e973299a3~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/148828fd578b474cba7dc16e973299a3~noop.jpeg?from=3218412987",
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/148828fd578b474cba7dc16e973299a3~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "can_extend_detail": true,
          "challenge_id": "",
          "event_time": 1600072657,
          "group_id": "6870867818461336840",
          "hot_value": 3714452,
          "label": 0,
          "position": 43,
          "related_words": null,
          "sentence_id": "123741",
          "video_count": 3,
          "word": "吴亦凡雕金玉面口罩",
          "word_cover": {
            "uri": "tos-cn-p-0015/baad04124d794cfb9a850f462b75bddd",
            "url_list": [
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/baad04124d794cfb9a850f462b75bddd~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/baad04124d794cfb9a850f462b75bddd~noop.jpeg?from=3218412987",
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/baad04124d794cfb9a850f462b75bddd~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "can_extend_detail": true,
          "challenge_id": "",
          "event_time": 1600051039,
          "group_id": "6870329912952706316",
          "hot_value": 3656293,
          "label": 0,
          "position": 44,
          "related_words": null,
          "sentence_id": "123287",
          "video_count": 2,
          "word": "西班牙人3-0阿尔瓦塞特",
          "word_cover": {
            "uri": "tos-cn-p-0000/88a28bae20c246578d321778fc569885",
            "url_list": [
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0000/88a28bae20c246578d321778fc569885~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0000/88a28bae20c246578d321778fc569885~noop.jpeg?from=3218412987",
              "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0000/88a28bae20c246578d321778fc569885~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1600010998,
          "group_id": "6870759860377212174",
          "hot_value": 3604162,
          "label": 5,
          "position": 45,
          "related_words": null,
          "room_count": 0,
          "sentence_id": "123267",
          "video_count": 5,
          "word": "村支书雇凶杀人受害者儿子发声",
          "word_cover": {
            "uri": "tos-cn-p-0015/7c36637b9109463086ce9dfd440ea0db",
            "url_list": [
              "https://p9-dy.byteimg.com/img/tos-cn-p-0015/7c36637b9109463086ce9dfd440ea0db~noop.jpeg?from=3218412987",
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/7c36637b9109463086ce9dfd440ea0db~noop.jpeg?from=3218412987",
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/7c36637b9109463086ce9dfd440ea0db~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "can_extend_detail": true,
          "challenge_id": "",
          "event_time": 1600068809,
          "group_id": "6870891347928536334",
          "hot_value": 3575625,
          "label": 0,
          "position": 46,
          "related_words": null,
          "sentence_id": "123635",
          "video_count": 1,
          "word": "交警你好 我可以超速一下吗",
          "word_cover": {
            "uri": "tos-cn-p-0015/5092da09a116491b9e9673a339dddd97_1599991310",
            "url_list": [
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/5092da09a116491b9e9673a339dddd97_1599991310~noop.jpeg?from=3218412987",
              "https://p26-dy.byteimg.com/img/tos-cn-p-0015/5092da09a116491b9e9673a339dddd97_1599991310~noop.jpeg?from=3218412987",
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/5092da09a116491b9e9673a339dddd97_1599991310~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1600064522,
          "group_id": "6870867789567366414",
          "hot_value": 3558183,
          "label": 1,
          "position": 47,
          "related_words": null,
          "sentence_id": "123496",
          "video_count": 18,
          "word": "我与冲浪只差个自拍杆",
          "word_cover": {
            "uri": "tos-cn-p-0015/73d42be9b0cd4cd5b3952d8d03e9f9f4",
            "url_list": [
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/73d42be9b0cd4cd5b3952d8d03e9f9f4~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/73d42be9b0cd4cd5b3952d8d03e9f9f4~noop.jpeg?from=3218412987",
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/73d42be9b0cd4cd5b3952d8d03e9f9f4~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "can_extend_detail": true,
          "challenge_id": "",
          "event_time": 1600073772,
          "group_id": "6870556008473957640",
          "hot_value": 3459750,
          "label": 0,
          "position": 48,
          "related_words": null,
          "sentence_id": "123788",
          "video_count": 1,
          "word": "拼多多取消iPhone12预约页面",
          "word_cover": {
            "uri": "tos-cn-p-0015/73c690076f0042e2abc1c8520fdc2673_1600067811",
            "url_list": [
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/73c690076f0042e2abc1c8520fdc2673_1600067811~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/73c690076f0042e2abc1c8520fdc2673_1600067811~noop.jpeg?from=3218412987",
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/73c690076f0042e2abc1c8520fdc2673_1600067811~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "can_extend_detail": true,
          "challenge_id": "",
          "event_time": 1600070292,
          "group_id": "6870847798889174286",
          "hot_value": 3421434,
          "label": 0,
          "position": 49,
          "related_words": null,
          "sentence_id": "123674",
          "video_count": 6,
          "word": "成都出台房产新政15条",
          "word_cover": {
            "uri": "tos-cn-p-0015/7dc4cccb8e5c42b5997b56270237ccef_1600059706",
            "url_list": [
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/7dc4cccb8e5c42b5997b56270237ccef_1600059706~noop.jpeg?from=3218412987",
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/7dc4cccb8e5c42b5997b56270237ccef_1600059706~noop.jpeg?from=3218412987",
              "https://p26-dy.byteimg.com/img/tos-cn-p-0015/7dc4cccb8e5c42b5997b56270237ccef_1600059706~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        },
        {
          "challenge_id": "",
          "event_time": 1600077890,
          "group_id": "6872193892844360971",
          "hot_value": 3409690,
          "label": 0,
          "position": 50,
          "related_words": null,
          "sentence_id": "123879",
          "video_count": 2,
          "word": "钟美美上GQ封面",
          "word_cover": {
            "uri": "tos-cn-p-0015/02ea9569c3894f93827aea37103adb9d",
            "url_list": [
              "https://p3-dy-ipv6.byteimg.com/img/tos-cn-p-0015/02ea9569c3894f93827aea37103adb9d~noop.jpeg?from=3218412987",
              "https://p1-dy-ipv6.byteimg.com/img/tos-cn-p-0015/02ea9569c3894f93827aea37103adb9d~noop.jpeg?from=3218412987",
              "https://p29-dy.byteimg.com/img/tos-cn-p-0015/02ea9569c3894f93827aea37103adb9d~noop.jpeg?from=3218412987"
            ]
          },
          "word_type": 1
        }
      ]
    },
    "extra": {
      "fatal_item_ids": [
      ],
      "logid": "202009142327000101980582070932F9A4",
      "now": 1600097220000
    },
    "log_pb": {
      "impr_id": "202009142327000101980582070932F9A4"
    },
    "status_code": 0
  },
  "msg": "success"
}
```


