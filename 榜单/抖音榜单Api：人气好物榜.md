# 抖音榜单Api：人气好物榜

## 抖音视频Api、抖音直播Api、抖音评论采集、抖音弹幕采集、抖音爬虫、抖音去水印、抖音视频下载、抖音视频解析
## 抖音直播数据、抖音数据采集、抖音直播监控

#### TiToData：专业的短视频数据采集、处理平台。
> 更多信息请联系： [TiToData](https://www.titodata.com/about?from=douyinbangdan)
```
海量数据采集
每天为客户采集5亿条数据
覆盖主流平台：TikTok，Zynn，YouTube，抖音，快手，1688，小红书，拼多多，淘宝，美团，饿了么，淘宝，微博

```


## 抖音榜单：人气好物榜

### 请求Api
```http
http://主机地址/douyin/board/goods?token=xxx

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
    "code": 0,
    "data": {
      "rank_list": [
        {
          "author": {
            "avatar": "https://p9-dy.byteimg.com/aweme/100x100/2e1960006db158c85c09d.jpeg?from=4010531038",
            "id": 628520101353603,
            "name": "吃货阿诗",
            "shop_url": "snssdk1128://goods/shop/?uid=628520101353603"
          },
          "goods": {
            "commodity_type": 4,
            "cover": "temai/FtQ4bmyLdVsmHi2u95w8uR_HQimSwww800-800",
            "detail_url": "",
            "id": "3434519033431626431",
            "market_price": 4290,
            "price": 3690,
            "product_id": "3434318250152965428",
            "sales": 29270,
            "score": 75539,
            "title": "【7件套】广东晨爽牌肠粉送工具套装家用装蒸盘酱汁专用拉肠粉",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6871774430327033096",
          "item_img": "tos-cn-p-0015/25b39d8a7b6c4d02b018c0137c54cd98_1599959699",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6871774430327033096"
        },
        {
          "author": {
            "avatar": "https://p29-dy.byteimg.com/aweme/100x100/310ec000271943dfe24f0.jpeg?from=4010531038",
            "id": 2150298885563934,
            "name": "骆王宇",
            "shop_url": "snssdk1128://goods/shop/?uid=2150298885563934"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FuL8Q80_5Chj_9GLo6oG1xMqxUYY.jpg",
            "detail_url": "",
            "id": "62704449428700",
            "market_price": 19800,
            "price": 12800,
            "product_id": "627044494287",
            "sales": 37999,
            "score": 68374,
            "title": "【骆王宇推荐】米蓓尔修护固态闪释冻干面膜女熬夜补水舒缓敏感肌",
            "up_or_down": -1
          },
          "is_recommended": 0,
          "item_id": "6871137170531355918",
          "item_img": "tos-cn-p-0015/392a9fc2c8514501ad7c1e46624a9fc6_1599811314",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6871137170531355918"
        },
        {
          "author": {
            "avatar": "https://p3-dy-ipv6.byteimg.com/img/tos-cn-avt-0015/0aa0f475c73557a8b9636a8c440373a6~c5_100x100.jpeg?from=4010531038",
            "id": 102107524550,
            "name": "GGhouse郭郭定制",
            "shop_url": "snssdk1128://goods/shop/?uid=102107524550"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/Fr3YHqQQckfMZkYoEt-oaX31ZBXJ.jpg",
            "detail_url": "",
            "id": "62662038108600",
            "market_price": 15990,
            "price": 15990,
            "product_id": "626620381086",
            "sales": 0,
            "score": 68317,
            "title": "郭郭定制秋装2020年新款针织连衣裙女长袖polo裙百搭显瘦中长裙",
            "up_or_down": -1
          },
          "is_recommended": 0,
          "item_id": "6871104250806619405",
          "item_img": "tos-cn-p-0015/bd7959760dbe45a49a2cca949ddf38e7_1599803631",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6871104250806619405"
        },
        {
          "author": {
            "avatar": "https://p3-dy-ipv6.byteimg.com/aweme/100x100/26ea600058d1ab528a0ab.jpeg?from=4010531038",
            "id": 60734144586,
            "name": "常熟歌维尚女装",
            "shop_url": "snssdk1128://goods/shop/?uid=60734144586"
          },
          "goods": {
            "commodity_type": 4,
            "cover": "temai/FqwBajNSpzMMy1emDml6MuesPVdjwww800-800",
            "detail_url": "",
            "id": "3433918899748490589",
            "market_price": 10000,
            "price": 2900,
            "product_id": "3433918706483391412",
            "sales": 41000,
            "score": 31215,
            "title": "【欢枝】抽绳V领上衣【均码85-145斤】",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6870194522601671950",
          "item_img": "tos-cn-p-0015/fcd1ce1ccd7747d79910cc57955d04c0_1599591838",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6870194522601671950"
        },
        {
          "author": {
            "avatar": "https://p29-dy.byteimg.com/aweme/100x100/3152e0002371d5b604412.jpeg?from=4010531038",
            "id": 2326200557505672,
            "name": "陈彦妃",
            "shop_url": "snssdk1128://goods/shop/?uid=2326200557505672"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FgkV-nRhxBU6u1hscNilyUultlaT.jpg",
            "detail_url": "",
            "id": "61111189038200",
            "market_price": 17990,
            "price": 17900,
            "product_id": "611111890382",
            "sales": 304111,
            "score": 30104,
            "title": "花西子蚕丝蜜粉饼/干粉粉饼定妆控油持久防水遮瑕散粉饼干皮油皮",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6846287662807026951",
          "item_img": "tos-cn-p-0015/0ce02c55bca64774a6da719bc98b8515_1594025585",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6846287662807026951"
        },
        {
          "author": {
            "avatar": "https://p6-dy-ipv6.byteimg.com/aweme/100x100/312380003046df6de1859.jpeg?from=4010531038",
            "id": 523011370006941,
            "name": "小盟主（直播中）",
            "shop_url": "snssdk1128://goods/shop/?uid=523011370006941"
          },
          "goods": {
            "commodity_type": 4,
            "cover": "temai/Fo-x23fhxh9KGvzM4U930YXfZTpYwww1000-1000",
            "detail_url": "",
            "id": "3424208708526309488",
            "market_price": 2880,
            "price": 1980,
            "product_id": "3423279825354361006",
            "sales": 59951,
            "score": 29195,
            "title": "椒巴客花椒手工锅巴休闲零食大米膨化食品小吃158g*3袋",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6871168653899877640",
          "item_img": "tos-cn-p-0015/00a54bd810074be694afeee26fdb4b06_1599818657",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6871168653899877640"
        },
        {
          "author": {
            "avatar": "https://p9-dy.byteimg.com/aweme/100x100/31bbd00010b501dba524b.jpeg?from=4010531038",
            "id": 97361807561,
            "name": "一只河豚揪",
            "shop_url": "snssdk1128://goods/shop/?uid=97361807561"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/Fl5Ahacz0S1UQ0x90_Vnq5ZxRjda.jpg",
            "detail_url": "",
            "id": "3298849346171315712",
            "market_price": 6990,
            "price": 6900,
            "product_id": "563422855497",
            "sales": 303717,
            "score": 27917,
            "title": "花西子极细三角眉笔/持久防水防汗初学者不容易脱色晕染超细网红",
            "up_or_down": 18
          },
          "is_recommended": 0,
          "item_id": "6807699850528869640",
          "item_img": "tos-cn-p-0015/a71dad20efb140ae9ccaa09b435ef102_1585041141",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6807699850528869640"
        },
        {
          "author": {
            "avatar": "https://p29-dy.byteimg.com/aweme/100x100/1ca7f00020e00069b2ad1.jpeg?from=4010531038",
            "id": 105859714629,
            "name": "中源果农",
            "shop_url": "snssdk1128://goods/shop/?uid=105859714629"
          },
          "goods": {
            "commodity_type": 6,
            "cover": "temai/Foddc6av1m1VHvnxooy7kmrfbKYJwww800-800",
            "detail_url": "",
            "id": "3432738780191294451",
            "market_price": 6980,
            "price": 3750,
            "product_id": "3432738780191294451",
            "sales": 35555,
            "score": 27619,
            "title": "【中源果农】陕西翠香猕猴桃  20/24/30个装 催熟食用 坏果包赔",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6871554613074529551",
          "item_img": "tos-cn-p-0015/dc019fe5f1b948daa2266a3a6bc014dd_1599908487",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6871554613074529551"
        },
        {
          "author": {
            "avatar": "https://p6-dy-ipv6.byteimg.com/aweme/100x100/3152e0002371d5b604412.jpeg?from=4010531038",
            "id": 2326200557505672,
            "name": "陈彦妃",
            "shop_url": "snssdk1128://goods/shop/?uid=2326200557505672"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FhenM0zH4lzOjfJoLu3Ps4VGf_7o.jpg",
            "detail_url": "",
            "id": "60055810901300",
            "market_price": 11900,
            "price": 6990,
            "product_id": "600558109013",
            "sales": 295511,
            "score": 27160,
            "title": "完美日记白胖子氨基酸卸妆水女眼唇脸三合一温和深层清洁正品平价",
            "up_or_down": 23
          },
          "is_recommended": 0,
          "item_id": "6864488763788168461",
          "item_img": "tos-cn-p-0015/e2a9f32091b940648a57d9a027fbe20a_1598263356",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6864488763788168461"
        },
        {
          "author": {
            "avatar": "https://p6-dy-ipv6.byteimg.com/aweme/100x100/55280012ec5c73482380.jpeg?from=4010531038",
            "id": 57843733637,
            "name": "Uni颖儿",
            "shop_url": "snssdk1128://goods/shop/?uid=57843733637"
          },
          "goods": {
            "commodity_type": 6,
            "cover": "temai/b6f68b2f3d3453c568d6db7998c77decwww800-800",
            "detail_url": "",
            "id": "3435009707759278875",
            "market_price": 5900,
            "price": 4900,
            "product_id": "3435009707759278875",
            "sales": 5365,
            "score": 27115,
            "title": "Uni颖儿 尔木萄隔离霜",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6870429486249200911",
          "item_img": "tos-cn-p-0015/01fe38c273c74d2fb8d872f73a982f05_1599646531",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6870429486249200911"
        },
        {
          "author": {
            "avatar": "https://p6-dy-ipv6.byteimg.com/aweme/100x100/2d08f000102554f684a0f.jpeg?from=4010531038",
            "id": 1516972701915476,
            "name": "阿纯是质量测评家",
            "shop_url": "snssdk1128://goods/shop/?uid=1516972701915476"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FiWIhxEIb9gNAQbg1uzm4qvP5yeU.jpg",
            "detail_url": "",
            "id": "3325384002018382958",
            "market_price": 12800,
            "price": 5990,
            "product_id": "581333547897",
            "sales": 215200,
            "score": 24824,
            "title": "PRAMY/柏瑞美定妆喷雾持久定妆保湿补水控油不脱妆快速定妆便携带",
            "up_or_down": 12
          },
          "is_recommended": 0,
          "item_id": "6763908165575789827",
          "item_img": "tos-cn-p-0015/1f985958853b4bbf92327077f5b297ca_1574845107",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6763908165575789827"
        },
        {
          "author": {
            "avatar": "https://p3-dy-ipv6.byteimg.com/aweme/100x100/3152e0002371d5b604412.jpeg?from=4010531038",
            "id": 2326200557505672,
            "name": "陈彦妃",
            "shop_url": "snssdk1128://goods/shop/?uid=2326200557505672"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/Fvejhrzd_-Ff9-UUw-zqoJ-MzlWM.jpg",
            "detail_url": "",
            "id": "61116446943400",
            "market_price": 7990,
            "price": 6900,
            "product_id": "611164469434",
            "sales": 203540,
            "score": 24043,
            "title": "小奥汀睫毛膏 浓密防水纤长卷翘持久不晕染不脱妆加长女彩色奥丁",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6801773147491175694",
          "item_img": "tos-cn-p-0015/616ebf9118ca49bcae9229254d99e29e_1583661267",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6801773147491175694"
        },
        {
          "author": {
            "avatar": "https://p3-dy-ipv6.byteimg.com/aweme/100x100/fa3d0007be21cbf0c524.jpeg?from=4010531038",
            "id": 91931984198,
            "name": "大脸妹张张",
            "shop_url": "snssdk1128://goods/shop/?uid=91931984198"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FiKjUBRgdRrgPkvjdxWe0WeCU2gH.jpg",
            "detail_url": "",
            "id": "3318548473511588839",
            "market_price": 16800,
            "price": 13800,
            "product_id": "559145345945",
            "sales": 227541,
            "score": 24023,
            "title": "日本进口redearth红地球养肤粉底液草本精华持久遮瑕轻薄裸妆正品",
            "up_or_down": 21
          },
          "is_recommended": 0,
          "item_id": "6855205078920449287",
          "item_img": "tos-cn-p-0015/3b94134ea1a64d83ac2856b412555fb3_1596101829",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6855205078920449287"
        },
        {
          "author": {
            "avatar": "https://p3-dy-ipv6.byteimg.com/aweme/100x100/3152e0002371d5b604412.jpeg?from=4010531038",
            "id": 2326200557505672,
            "name": "陈彦妃",
            "shop_url": "snssdk1128://goods/shop/?uid=2326200557505672"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FuoWDRtbpe0cZdJ-Fmphaaa7MyEc.jpg",
            "detail_url": "",
            "id": "62503306948500",
            "market_price": 12900,
            "price": 12900,
            "product_id": "625033069485",
            "sales": 12355,
            "score": 22008,
            "title": "潘婷胶囊护发精油小彩蛋显色改善毛躁卷发烫染修复损伤免洗精华",
            "up_or_down": -9
          },
          "is_recommended": 0,
          "item_id": "6870416621064752388",
          "item_img": "tos-cn-p-0015/bf23153bb1494d9eb3b7ff3c25bdda82_1599643590",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6870416621064752388"
        },
        {
          "author": {
            "avatar": "https://p9-dy.byteimg.com/aweme/100x100/30fe80008903733453517.jpeg?from=4010531038",
            "id": 59034758325,
            "name": "蓝蓝是个小胖子（八点直播）",
            "shop_url": "snssdk1128://goods/shop/?uid=59034758325"
          },
          "goods": {
            "commodity_type": 4,
            "cover": "temai/ecb489d35a5c7b74d1bb70d036afaefe4bde3146www800-800",
            "detail_url": "",
            "id": "3434785866915166943",
            "market_price": 15800,
            "price": 7900,
            "product_id": "3433905387898846882",
            "sales": 2980,
            "score": 21452,
            "title": "大码女装直筒牛仔裤2020年新款秋季200斤胖妹妹mm遮胯显瘦裤子潮",
            "up_or_down": -2
          },
          "is_recommended": 0,
          "item_id": "6871451403454385416",
          "item_img": "tos-cn-p-0015/7f9f5e2e40954a208d7db2c63fb8c119_1599884457",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6871451403454385416"
        },
        {
          "author": {
            "avatar": "https://p3-dy-ipv6.byteimg.com/aweme/100x100/20aed0004b99dfce0b1c2.jpeg?from=4010531038",
            "id": 97713144206,
            "name": "素野君露台园艺",
            "shop_url": "snssdk1128://goods/shop/?uid=97713144206"
          },
          "goods": {
            "commodity_type": 4,
            "cover": "temai/FpFUH69hmywwzGJzWw1FWLwi0SYowww800-800",
            "detail_url": "",
            "id": "3435091793165864726",
            "market_price": 5990,
            "price": 2990,
            "product_id": "3434137215209499594",
            "sales": 8150,
            "score": 21264,
            "title": "香雪兰（小苍兰）盆栽",
            "up_or_down": 13
          },
          "is_recommended": 0,
          "item_id": "6871470690894204171",
          "item_img": "tos-cn-p-0015/8e967eff4c9744c09508196842942571_1599888947",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6871470690894204171"
        },
        {
          "author": {
            "avatar": "https://p6-dy-ipv6.byteimg.com/aweme/100x100/2f76c000014cd0edaf636.jpeg?from=4010531038",
            "id": 101441411841,
            "name": "唐心蛋🥚",
            "shop_url": "snssdk1128://goods/shop/?uid=101441411841"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FiempnqtrP9Ac3gjtzsk0GRRqGwm.jpg",
            "detail_url": "",
            "id": "61826649540800",
            "market_price": 23800,
            "price": 11900,
            "product_id": "618266495408",
            "sales": 26893,
            "score": 20886,
            "title": "泰国Mistine蜜丝婷蓝盾粉底液干油皮遮瑕持久保湿控油粉底学生女",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6868095266948467979",
          "item_img": "tos-cn-p-0015/97c99cb54376425b8dd29b081519db55_1599103066",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6868095266948467979"
        },
        {
          "author": {
            "avatar": "https://p29-dy.byteimg.com/aweme/100x100/3156d0000c6904ec9b268.jpeg?from=4010531038",
            "id": 93389153804,
            "name": "老爸评测",
            "shop_url": "snssdk1128://goods/shop/?uid=93389153804"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FgR5ECr3JCx1cVEPApwKyVQ3yziT.jpg",
            "detail_url": "",
            "id": "62479393757500",
            "market_price": 7900,
            "price": 7100,
            "product_id": "624793937575",
            "sales": 20332,
            "score": 20685,
            "title": "工厂发货-老爸评测薄荷海盐清洁面膜100ml清洁毛孔涂抹式泥膜",
            "up_or_down": -11
          },
          "is_recommended": 0,
          "item_id": "6870838136931437831",
          "item_img": "tos-cn-p-0015/9d1bdd6e4d2e4e9ebfc83f3c27ab2c66_1599741688",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6870838136931437831"
        },
        {
          "author": {
            "avatar": "https://p26-dy.byteimg.com/aweme/100x100/2d08f000102554f684a0f.jpeg?from=4010531038",
            "id": 1516972701915476,
            "name": "阿纯是质量测评家",
            "shop_url": "snssdk1128://goods/shop/?uid=1516972701915476"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FjQvThvCqEf849X80OTW9dk3szCH.jpg",
            "detail_url": "",
            "id": "3311571994923957819",
            "market_price": 59800,
            "price": 19800,
            "product_id": "576223028007",
            "sales": 81659,
            "score": 20348,
            "title": "明星同款 冰希黎幻彩鎏金女士香水持久淡香自然清新学生少女",
            "up_or_down": 3
          },
          "is_recommended": 0,
          "item_id": "6790556879211728131",
          "item_img": "tos-cn-p-0015/652f6be6a16f4f7b91740be0467aced6_1581049740",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6790556879211728131"
        },
        {
          "author": {
            "avatar": "https://p26-dy.byteimg.com/aweme/100x100/31aeb0004dc2dbad7b526.jpeg?from=4010531038",
            "id": 55979450230,
            "name": "侯小西",
            "shop_url": "snssdk1128://goods/shop/?uid=55979450230"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FsT_iRSZfmKLJDILKqJPW7UhG-jY.jpg",
            "detail_url": "",
            "id": "61420438580900",
            "market_price": 92930,
            "price": 69900,
            "product_id": "614204385809",
            "sales": 36744,
            "score": 19763,
            "title": "花西子x杜鹃定制东方佳人妆奁彩妆套装化妆品全套组合",
            "up_or_down": -3
          },
          "is_recommended": 0,
          "item_id": "6813556445880077583",
          "item_img": "tos-cn-p-0015/e0b44846f3ca412198bdc5d6de59b4ec_1586404736",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6813556445880077583"
        },
        {
          "author": {
            "avatar": "https://p9-dy.byteimg.com/img/tos-cn-avt-0015/1674333200881679~c5_100x100.jpeg?from=4010531038",
            "id": 98372493335,
            "name": "哈哈妈妈",
            "shop_url": "snssdk1128://goods/shop/?uid=98372493335"
          },
          "goods": {
            "commodity_type": 4,
            "cover": "temai/48a35f482434728f33ada3fa27e5fedewww610-606",
            "detail_url": "",
            "id": "3425970757656806386",
            "market_price": 59900,
            "price": 29900,
            "product_id": "3425958929174271868",
            "sales": 248,
            "score": 19649,
            "title": "【主播福利减50】宝宝摇篮床多功能折叠新生儿儿童床可移动婴儿床",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6868894333085437184",
          "item_img": "tos-cn-p-0015/e16ed0b7e7234ff9a7305718ce7be2a4_1599289094",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6868894333085437184"
        },
        {
          "author": {
            "avatar": "https://p3-dy-ipv6.byteimg.com/aweme/100x100/2f54a000457bb967f265b.jpeg?from=4010531038",
            "id": 905593202154171,
            "name": "我是张凯毅",
            "shop_url": "snssdk1128://goods/shop/?uid=905593202154171"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/Fn7rgUakzD67ePHDfSYOfyZgsXja.jpg",
            "detail_url": "",
            "id": "61357506316600",
            "market_price": 19900,
            "price": 13900,
            "product_id": "613575063166",
            "sales": 2443,
            "score": 19505,
            "title": "Mixx氨基酸洗面奶男女玻色因抗老洁面乳温和控油淡纹洁颜蜜200ml",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6871855793575185678",
          "item_img": "tos-cn-p-0015/e369e000afcc47efa60d15be0de3dfd4_1599978722",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6871855793575185678"
        },
        {
          "author": {
            "avatar": "https://p9-dy.byteimg.com/aweme/100x100/1b5660003cd57dc8438f3.jpeg?from=4010531038",
            "id": 94284217764,
            "name": "Gabby",
            "shop_url": "snssdk1128://goods/shop/?uid=94284217764"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/Fqq4jaeCKybdcQYQOWpOMsw7WXs6.jpg",
            "detail_url": "",
            "id": "3322068134794539146",
            "market_price": 12800,
            "price": 8990,
            "product_id": "579685049795",
            "sales": 142790,
            "score": 19043,
            "title": "珀莱雅粉底液干皮油皮亲妈持久水润保湿遮瑕控油BB霜女学生平价",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6871459380907216143",
          "item_img": "tos-cn-p-0015/1525806ef0e44d9aaeb8cc3437cfeb27_1599886314",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6871459380907216143"
        },
        {
          "author": {
            "avatar": "https://p6-dy-ipv6.byteimg.com/aweme/100x100/2de070003a7d51b268494.jpeg?from=4010531038",
            "id": 3671957135698909,
            "name": "小草的低卡零食屋",
            "shop_url": "snssdk1128://goods/shop/?uid=3671957135698909"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/Fu6iv986_jeRgCkRmuY_LJysBqkG.jpg",
            "detail_url": "",
            "id": "61975346188200",
            "market_price": 9990,
            "price": 8990,
            "product_id": "619753461882",
            "sales": 21142,
            "score": 18970,
            "title": "薄荷健康网红轻卡零食大礼包女低零食小吃休闲食品脂解馋控卡",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6870471859356421389",
          "item_img": "tos-cn-p-0015/10caa1d2ca75436fac23a5ffd602e3a5_1599656483",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6870471859356421389"
        },
        {
          "author": {
            "avatar": "https://p29-dy.byteimg.com/aweme/100x100/3152e0002371d5b604412.jpeg?from=4010531038",
            "id": 2326200557505672,
            "name": "陈彦妃",
            "shop_url": "snssdk1128://goods/shop/?uid=2326200557505672"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FjHJNnDnaOM1qeiSldZu_GITbTS4.jpg",
            "detail_url": "",
            "id": "60100911108800",
            "market_price": 22900,
            "price": 9900,
            "product_id": "601009111088",
            "sales": 136805,
            "score": 18800,
            "title": "膜法世家纱布修护面膜10片补水保湿水杨酸控油淡痘印女男魔法世家",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6867078089420066062",
          "item_img": "tos-cn-p-0015/1b1536b0fd474df0a503c2e96bb41236_1598866241",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6867078089420066062"
        },
        {
          "author": {
            "avatar": "https://p3-dy-ipv6.byteimg.com/aweme/100x100/3152e0002371d5b604412.jpeg?from=4010531038",
            "id": 2326200557505672,
            "name": "陈彦妃",
            "shop_url": "snssdk1128://goods/shop/?uid=2326200557505672"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FgGnpRbQOuGvR91LXD4PrBIGORzb.jpg",
            "detail_url": "",
            "id": "60122318747600",
            "market_price": 13900,
            "price": 7990,
            "product_id": "601223187476",
            "sales": 119099,
            "score": 18761,
            "title": "完美日记金色散粉蜜粉饼定妆粉持久控油防水防汗空气蜜粉三丽鸥",
            "up_or_down": 16
          },
          "is_recommended": 0,
          "item_id": "6828023437299125516",
          "item_img": "tos-cn-p-0015/e8a087ce62dd448bb25572b23d59d5dd_1589773143",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6828023437299125516"
        },
        {
          "author": {
            "avatar": "https://p3-dy-ipv6.byteimg.com/aweme/100x100/3136b000b9ca4e7d26cdf.jpeg?from=4010531038",
            "id": 103429813472,
            "name": "老宋的微醺23点",
            "shop_url": "snssdk1128://goods/shop/?uid=103429813472"
          },
          "goods": {
            "commodity_type": 4,
            "cover": "temai/47761068e6b078ca704912f77502f253www800-800",
            "detail_url": "",
            "id": "3425901610688249759",
            "market_price": 15000,
            "price": 8400,
            "product_id": "3421505481997430330",
            "sales": 7280,
            "score": 18667,
            "title": "【青岛啤酒】白啤11度 焕新包装 日期新鲜 500ml*12听",
            "up_or_down": -9
          },
          "is_recommended": 0,
          "item_id": "6871489674897116424",
          "item_img": "tos-cn-p-0015/2b7653e35aa9474ca2c71a62e16ce1eb_1599893400",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6871489674897116424"
        },
        {
          "author": {
            "avatar": "https://p26-dy.byteimg.com/aweme/100x100/31b0b0003211ec5acb246.jpeg?from=4010531038",
            "id": 56819687816,
            "name": "哦王小明(9月27号下午4点直播)",
            "shop_url": "snssdk1128://goods/shop/?uid=56819687816"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FifpzQDe8dAjsM_xv24h_bAPxr6a.jpg",
            "detail_url": "",
            "id": "59760292257800",
            "market_price": 20900,
            "price": 9900,
            "product_id": "597602922578",
            "sales": 22620,
            "score": 18494,
            "title": "韩国Medicube乐得遮瑕液针管修复笔膏棒美蒂秋芙官网脸部修容神器",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6745379879673548043",
          "item_img": "tos-cn-p-0015/87f83fc076634164aaeb3a9ae5b4aae6",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6745379879673548043"
        },
        {
          "author": {
            "avatar": "https://p26-dy.byteimg.com/aweme/100x100/313cd00025f648fc91dd5.jpeg?from=4010531038",
            "id": 99836084682,
            "name": "大P",
            "shop_url": "snssdk1128://goods/shop/?uid=99836084682"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FlHlK4TgLind-a7_E5me-YjEbcOQ.jpg",
            "detail_url": "",
            "id": "62037211800000",
            "market_price": 999900,
            "price": 999900,
            "product_id": "620372118000",
            "sales": 0,
            "score": 17318,
            "title": "【 9/15 20:00 NEW 喜欢收藏加购】Plastic tree 新品集合页",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6871179927291448590",
          "item_img": "tos-cn-p-0015/1e6fdba3cb2b4c32995e0e7308ece86d_1599821268",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6871179927291448590"
        },
        {
          "author": {
            "avatar": "https://p6-dy-ipv6.byteimg.com/aweme/100x100/31549000d07ea979ba97b.jpeg?from=4010531038",
            "id": 71515824773,
            "name": "橙子小厨",
            "shop_url": "snssdk1128://goods/shop/?uid=71515824773"
          },
          "goods": {
            "commodity_type": 4,
            "cover": "temai/FtRNxIGNomnbTGfQkdf1aU8oEoMEwww800-800",
            "detail_url": "",
            "id": "3430208748084456683",
            "market_price": 16900,
            "price": 5900,
            "product_id": "3430200248444808557",
            "sales": 101412,
            "score": 17073,
            "title": "【美之扣】电动绞蒜器家用手动小型料理机打拉切压蒜大蒜搅蒜器",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6865161334309260559",
          "item_img": "tos-cn-p-0015/70ad09f24ffc4c40a7c0a976a112dda9_1598419937",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6865161334309260559"
        },
        {
          "author": {
            "avatar": "https://p3-dy-ipv6.byteimg.com/img/tos-cn-avt-0015/1674333200881679~c5_100x100.jpeg?from=4010531038",
            "id": 98372493335,
            "name": "哈哈妈妈",
            "shop_url": "snssdk1128://goods/shop/?uid=98372493335"
          },
          "goods": {
            "commodity_type": 4,
            "cover": "temai/FpMDP4XdDe7EBLR4qcvWKNBBpkWZwww800-800",
            "detail_url": "",
            "id": "3434439411255905663",
            "market_price": 6990,
            "price": 2990,
            "product_id": "3434439247921305926",
            "sales": 2720,
            "score": 16950,
            "title": "【主播福利减5元】卡通椅背多功能后座汽车餐盘车载收纳储物盒",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6871410895738686735",
          "item_img": "tos-cn-p-0015/944c4b9dc5cf4fe099f07bf2c2200eb8_1599875025",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6871410895738686735"
        },
        {
          "author": {
            "avatar": "https://p3-dy-ipv6.byteimg.com/aweme/100x100/310ec000271943dfe24f0.jpeg?from=4010531038",
            "id": 2150298885563934,
            "name": "骆王宇",
            "shop_url": "snssdk1128://goods/shop/?uid=2150298885563934"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/Fi1M-H_7gDgWzd0y4la2sITfXDcH.jpg",
            "detail_url": "",
            "id": "62572257754600",
            "market_price": 36000,
            "price": 36000,
            "product_id": "625722577546",
            "sales": 4582,
            "score": 16731,
            "title": "【骆王宇专属】UNISKIN优时颜#6.3抗糖美白精华祛黄改善暗沉",
            "up_or_down": -16
          },
          "is_recommended": 0,
          "item_id": "6868578564632071437",
          "item_img": "tos-cn-p-0015/0adca255b39a4b46992ce10e60121d27_1599215595",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6868578564632071437"
        },
        {
          "author": {
            "avatar": "https://p3-dy-ipv6.byteimg.com/aweme/100x100/1b56b0004b5d1d8efeb94.jpeg?from=4010531038",
            "id": 24883947010,
            "name": "广式老吴",
            "shop_url": "snssdk1128://goods/shop/?uid=24883947010"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/Fh9j_RUlaUWI3MddYtP8jerHG4tb.jpg",
            "detail_url": "",
            "id": "61601333551600",
            "market_price": 18900,
            "price": 18900,
            "product_id": "616013335516",
            "sales": 69764,
            "score": 16710,
            "title": "美宝莲旗舰店SuperStay巨持妆粉底液遮瑕控油持久女防水防汗正品",
            "up_or_down": 5
          },
          "is_recommended": 0,
          "item_id": "6853356286948527360",
          "item_img": "tos-cn-p-0015/ca2647233f774911b93ad6af6f0c3c2b_1595671360",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6853356286948527360"
        },
        {
          "author": {
            "avatar": "https://p3-dy-ipv6.byteimg.com/img/tos-cn-avt-0015/ca81add7df7c947c786f5fbd1f0fbcbb~c5_100x100.jpeg?from=4010531038",
            "id": 75852011344,
            "name": "兰普兰",
            "shop_url": "snssdk1128://goods/shop/?uid=75852011344"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FlT6mBk0sS8IyCq05QzkdSebACgd.jpg",
            "detail_url": "",
            "id": "61304446364500",
            "market_price": 16900,
            "price": 9990,
            "product_id": "613044463645",
            "sales": 77595,
            "score": 16709,
            "title": "【王一博代言】完子心选3+1神经酰胺面膜贴片补水保湿舒缓修护",
            "up_or_down": -1
          },
          "is_recommended": 0,
          "item_id": "6865179006275292430",
          "item_img": "tos-cn-p-0015/f9e509e412a94b2a994a3723c90ba0ad_1598424079",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6865179006275292430"
        },
        {
          "author": {
            "avatar": "https://p3-dy-ipv6.byteimg.com/aweme/100x100/20acb000345aae2a8c11e.jpeg?from=4010531038",
            "id": 101161791994,
            "name": "主编的心机",
            "shop_url": "snssdk1128://goods/shop/?uid=101161791994"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FhI44NzDrNdcfph62p0pHLslpmRq.jpg",
            "detail_url": "",
            "id": "3317429891583065777",
            "market_price": 24800,
            "price": 11990,
            "product_id": "4359111383",
            "sales": 84043,
            "score": 16061,
            "title": "膜法世家绿豆泥面膜美白清洁毛孔淡痘印去黑头涂抹式泥膜魔法世家",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6863053288233831688",
          "item_img": "tos-cn-p-0015/f259e1a18f824c17a0d0d189894f13da_1597929139",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6863053288233831688"
        },
        {
          "author": {
            "avatar": "https://p9-dy.byteimg.com/aweme/100x100/2ce1f0004c79ddc371cf5.jpeg?from=4010531038",
            "id": 68027072858,
            "name": "婕婕家里有宝藏啊",
            "shop_url": "snssdk1128://goods/shop/?uid=68027072858"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FvO8UW66HzUC6LJlAWi0a1Pke-U2.jpg",
            "detail_url": "",
            "id": "61670884590900",
            "market_price": 29900,
            "price": 10900,
            "product_id": "616708845909",
            "sales": 51,
            "score": 15990,
            "title": "几光感应灯定制礼盒专属款送礼无线感应全屋智能灯光多场景组合套装",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6871622667716365568",
          "item_img": "tos-cn-p-0015/16c40c0151ba4ba18631b64f3da8a6dc_1599924333",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6871622667716365568"
        },
        {
          "author": {
            "avatar": "https://p9-dy.byteimg.com/aweme/100x100/1b5450005c99f4e066be3.jpeg?from=4010531038",
            "id": 98704396690,
            "name": "园艺优享家",
            "shop_url": "snssdk1128://goods/shop/?uid=98704396690"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FiBrjDkZpvhKeiOSl1iyJVTR7zCg.jpg",
            "detail_url": "",
            "id": "61959824282500",
            "market_price": 338000,
            "price": 338000,
            "product_id": "619598242825",
            "sales": 4,
            "score": 15918,
            "title": "家用湿垃圾处理器厨余粉碎机厨房垃圾生物降解发酵菌种有机肥",
            "up_or_down": -25
          },
          "is_recommended": 0,
          "item_id": "6871179328731008269",
          "item_img": "tos-cn-p-0015/b4b425d947b34721be7596089828d40a_1599821111",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6871179328731008269"
        },
        {
          "author": {
            "avatar": "https://p26-dy.byteimg.com/aweme/100x100/2f78a00006acde4e17db8.jpeg?from=4010531038",
            "id": 329449466757675,
            "name": "隔壁小吴",
            "shop_url": "snssdk1128://goods/shop/?uid=329449466757675"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/Fh-8ZkEgWQCLXYnDoIU-RucGH_b4.jpg",
            "detail_url": "",
            "id": "62212992052600",
            "market_price": 13900,
            "price": 13900,
            "product_id": "622129920526",
            "sales": 2028,
            "score": 15372,
            "title": "【全系15款】自然实验室blings小众香不撞香男女持久鸡尾酒淡香水",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6871789643382181132",
          "item_img": "tos-cn-p-0015/a5567030291f4cadb4bbc52721274d3a_1599963252",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6871789643382181132"
        },
        {
          "author": {
            "avatar": "https://p6-dy-ipv6.byteimg.com/aweme/100x100/18bbe00046eafa5c2b06e.jpeg?from=4010531038",
            "id": 100016570964,
            "name": "赶海小章",
            "shop_url": "snssdk1128://goods/shop/?uid=100016570964"
          },
          "goods": {
            "commodity_type": 4,
            "cover": "temai/FuLvJj8jhe6jbu4azT5E3qL53I-bwww800-800",
            "detail_url": "",
            "id": "3433729614206340847",
            "market_price": 3900,
            "price": 1990,
            "product_id": "3433726455157266428",
            "sales": 30650,
            "score": 15139,
            "title": "【本地推荐】山东日照发货盐渍裙带菜带箱5斤19.9",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6870822721203358991",
          "item_img": "tos-cn-p-0015/f468a510249e4b9dbc2a817641467685_1599738080",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6870822721203358991"
        },
        {
          "author": {
            "avatar": "https://p26-dy.byteimg.com/aweme/100x100/3136b000b9ca4e7d26cdf.jpeg?from=4010531038",
            "id": 103429813472,
            "name": "老宋的微醺23点",
            "shop_url": "snssdk1128://goods/shop/?uid=103429813472"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FlEkhgxbSbCDpB3iWoEGp-7Sej7_.png",
            "detail_url": "",
            "id": "53891101701800",
            "market_price": 41900,
            "price": 26500,
            "product_id": "538911017018",
            "sales": 3373,
            "score": 15123,
            "title": "chivas芝华士12年苏格兰调和威士忌500ml整箱组合进口洋酒烈酒",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6871846773955104014",
          "item_img": "tos-cn-p-0015/7c04283248d44d75a270aac9620b9d3c_1599976541",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6871846773955104014"
        },
        {
          "author": {
            "avatar": "https://p6-dy-ipv6.byteimg.com/aweme/100x100/1e0ba00035e25af8fe7d1.jpeg?from=4010531038",
            "id": 72319562662,
            "name": "林剑霄",
            "shop_url": "snssdk1128://goods/shop/?uid=72319562662"
          },
          "goods": {
            "commodity_type": 8,
            "cover": "cmp-ecom-alliance/FodGbNXL1bx0itzcPcH6YZ_Tr3DL.jpg",
            "detail_url": "",
            "id": "3434786476273092135",
            "market_price": 1249900,
            "price": 1249900,
            "product_id": "100015073636",
            "sales": 2,
            "score": 15049,
            "title": "摩托罗拉 motorola razr 5G 刀锋折叠屏手机 双模5G全网通 超薄无缝无折痕+大双屏 4800万超强自拍 8GB+256GB 锋雅黑",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6871878305075809543",
          "item_img": "tos-cn-p-0015/6e77c20fded24d9898b507231cd7f4bc_1599983864",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6871878305075809543"
        },
        {
          "author": {
            "avatar": "https://p29-dy.byteimg.com/aweme/100x100/faed000943aed0948e6f.jpeg?from=4010531038",
            "id": 92440704622,
            "name": "零青子",
            "shop_url": "snssdk1128://goods/shop/?uid=92440704622"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FrYAN_R7trWUkq3GKkGpaoj7YO_P.jpg",
            "detail_url": "",
            "id": "62554581384900",
            "market_price": 5800,
            "price": 2900,
            "product_id": "625545813849",
            "sales": 354,
            "score": 14980,
            "title": "劲合明制汉服松蝶之恋原创正品立领齐腰褶裙夏季汉服全套中国风",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6867837938466655491",
          "item_img": "tos-cn-p-0015/937c17f15e964c6285c1b0ba3b907b7c_1599043132",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6867837938466655491"
        },
        {
          "author": {
            "avatar": "https://p3-dy-ipv6.byteimg.com/img/mosaic-legacy/1b57e00061bac6496c562~c5_100x100.jpeg?from=4010531038",
            "id": 65769625996,
            "name": "吉祥三宝",
            "shop_url": "snssdk1128://goods/shop/?uid=65769625996"
          },
          "goods": {
            "commodity_type": 4,
            "cover": "temai/FnJiwBaP-yUuJWXExvNxKCmZ16fWwww800-800",
            "detail_url": "",
            "id": "3426332720320646697",
            "market_price": 7000,
            "price": 1980,
            "product_id": "3425585956479192124",
            "sales": 43860,
            "score": 14876,
            "title": "瑜伽八字拉力绳",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6870090015137975567",
          "item_img": "tos-cn-p-0015/aac7aa408e1647208eb5d94c8355d316_1599567486",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6870090015137975567"
        },
        {
          "author": {
            "avatar": "https://p9-dy.byteimg.com/aweme/100x100/2dfd900044cec21a65c11.jpeg?from=4010531038",
            "id": 81793710243,
            "name": "潘雨润 9.16苗条专场",
            "shop_url": "snssdk1128://goods/shop/?uid=81793710243"
          },
          "goods": {
            "commodity_type": 4,
            "cover": "temai/FuQ2DXZxP-AdKc0mpqIpdQ0ns7Mtwww800-800",
            "detail_url": "",
            "id": "3434051607896176757",
            "market_price": 17990,
            "price": 14990,
            "product_id": "3434051236406689126",
            "sales": 2160,
            "score": 14671,
            "title": "【拍立减】凡士林(Vaseline) 维他亮肤烟酰胺流光身体乳180g",
            "up_or_down": -8
          },
          "is_recommended": 0,
          "item_id": "6871489010112449805",
          "item_img": "tos-cn-p-0015/f7d3674a16fb4d718f7c874dce5eb095_1599893244",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6871489010112449805"
        },
        {
          "author": {
            "avatar": "https://p9-dy.byteimg.com/aweme/100x100/facd000b12ec36349082.jpeg?from=4010531038",
            "id": 56663252872,
            "name": "小小莎老师",
            "shop_url": "snssdk1128://goods/shop/?uid=56663252872"
          },
          "goods": {
            "commodity_type": 4,
            "cover": "temai/2a321c4385d041fe8a6bbb22d1a333b7www800-800",
            "detail_url": "",
            "id": "3435546887825005663",
            "market_price": 35000,
            "price": 35000,
            "product_id": "3435543157704669546",
            "sales": 2545,
            "score": 14660,
            "title": "【Ｄ ｉ ｏ ｒ】口红９９９滋润 ９９９哑光 ８８８（3.5g）",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6871944724853296391",
          "item_img": "tos-cn-p-0015/b2be292e5db243d7a7090e9f0d689987_1599999317",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6871944724853296391"
        },
        {
          "author": {
            "avatar": "https://p9-dy.byteimg.com/aweme/100x100/314ef000106b341e9d9e5.jpeg?from=4010531038",
            "id": 60282990510,
            "name": "张大碗子",
            "shop_url": "snssdk1128://goods/shop/?uid=60282990510"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FlDqYGMo97VoEP9vq-6SFC8NC--p.jpg",
            "detail_url": "",
            "id": "62378289521800",
            "market_price": 29900,
            "price": 17900,
            "product_id": "623782895218",
            "sales": 7060,
            "score": 14633,
            "title": "旁氏虾滑爆水睡眠面膜虾青素焕亮紧致补水淡纹菁妍赋活微囊面膜",
            "up_or_down": -20
          },
          "is_recommended": 0,
          "item_id": "6866396280793451791",
          "item_img": "tos-cn-p-0015/7436e485253a47d684d82f0eb7c5e2d0_1598707469",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6866396280793451791"
        },
        {
          "author": {
            "avatar": "https://p6-dy-ipv6.byteimg.com/aweme/100x100/20acb0004760d0cedcdcd.jpeg?from=4010531038",
            "id": 60579555802,
            "name": "lovemimius游鹿鹿",
            "shop_url": "snssdk1128://goods/shop/?uid=60579555802"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FmoWUwBT3oGs5u9liP8n_InYVzs4.jpg",
            "detail_url": "",
            "id": "62485126476500",
            "market_price": 9900,
            "price": 9900,
            "product_id": "624851264765",
            "sales": 0,
            "score": 14330,
            "title": "mimius 8月25日上新合辑 下滑至详情页查看新品 提前收藏加购...",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6864394955176037647",
          "item_img": "tos-cn-p-0015/b44438cd11574428936843e55daf06d3_1598241501",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6864394955176037647"
        },
        {
          "author": {
            "avatar": "https://p26-dy.byteimg.com/aweme/100x100/315d50000843eb0c8b280.jpeg?from=4010531038",
            "id": 64707948091,
            "name": "猪猪芳♥️",
            "shop_url": "snssdk1128://goods/shop/?uid=64707948091"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/FiVoraJX5eUccqmmeI13znjj7ThK.jpg",
            "detail_url": "",
            "id": "60565315699100",
            "market_price": 12800,
            "price": 1590,
            "product_id": "605653156991",
            "sales": 971,
            "score": 14015,
            "title": "冬季棉拖鞋女家居家用月子室内保暖厚底防滑毛绒可爱卡通棉拖男冬",
            "up_or_down": 0
          },
          "is_recommended": 0,
          "item_id": "6871815448506207491",
          "item_img": "tos-cn-p-0015/49ed66ea4e834e9697c2da86c4560a40_1599969220",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6871815448506207491"
        },
        {
          "author": {
            "avatar": "https://p9-dy.byteimg.com/aweme/100x100/3152e0002371d5b604412.jpeg?from=4010531038",
            "id": 2326200557505672,
            "name": "陈彦妃",
            "shop_url": "snssdk1128://goods/shop/?uid=2326200557505672"
          },
          "goods": {
            "commodity_type": 7,
            "cover": "cmp-ecom-alliance/Fqjz3e1ELZiUrbxXZxPJIQUGUEym.jpg",
            "detail_url": "",
            "id": "61228863206400",
            "market_price": 13990,
            "price": 6990,
            "product_id": "612288632064",
            "sales": 39846,
            "score": 13666,
            "title": "李施德林进口温和樱花果味漱口水蜜桃青柠椰香女士学生清新漱口液",
            "up_or_down": -9
          },
          "is_recommended": 0,
          "item_id": "6869315887803927815",
          "item_img": "tos-cn-p-0015/a840e917fd6143f9b2a8821dcaf61988_1599387323",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6869315887803927815"
        },
        {
          "author": {
            "avatar": "https://p29-dy.byteimg.com/aweme/100x100/30e2c0006cdc6d6495bef.jpeg?from=4010531038",
            "id": 96106104768,
            "name": "年糕妈妈挑辅食",
            "shop_url": "snssdk1128://goods/shop/?uid=96106104768"
          },
          "goods": {
            "commodity_type": 4,
            "cover": "temai/f1c89c3f90dfed402c2cb76afa473e72www800-800",
            "detail_url": "",
            "id": "3435584584752978871",
            "market_price": 9800,
            "price": 8800,
            "product_id": "3435547611527034939",
            "sales": 76,
            "score": 13527,
            "title": "小面包幼儿护脚学步鞋",
            "up_or_down": -22
          },
          "is_recommended": 0,
          "item_id": "6871550527449173260",
          "item_img": "tos-cn-p-0015/48b9a743e8614ffaa93a85108b3cb944_1599907572",
          "item_type": 4,
          "item_url": "aweme://aweme/detail/6871550527449173260"
        }
      ],
      "special": null,
      "total": 50,
      "update_time": "更新于: 9月14日 12:00"
    },
    "error": false,
    "message": "success"
  },
  "msg": "success"
}
```


