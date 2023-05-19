# astrology-api
astrology api 星盘 api 星盘接口
# XINGPANVIP的API接口介绍

## 一、通用星盘接口和专用接口区别
### 1、通用接口（包月服务）
是按月收费的。星盘通用接口，支持的主要是行星的位置数据和svg星盘，这个是包括在月租费里面的。
### 2、专用接口（一次性费用）
专用接口是一些特殊的，不同于星盘位置数据和svg星盘的特殊功能，专用接口是基于通用接口开发的，用户体验感更好的产品。专用接口是一次性费用，但是购买专用接口前必须先购买通用接口。
3、通用接口价格见第一部分，专用接口价格见第二部分，通用接口为按月计费，专用接口为一次性费用。
## 二、通用星盘接口价格
http://xingpan.vip/index/index/pricing.html
可以查阅


### 测试接口文档
http://www.xingpan.vip/astrology/Apiinterface
测试access_token:989f888c4283e2cc2d8a5aa4af60932c

测试的token可能很多人测，所以有时候可能会比较慢！出错，请找适当时间重新测试


### 通用接口包括
通用接口包括在套餐中，通用接口是按照月或者季度，年，周期收费。


### 基础接口
### 获取星盘配置
新闻内容、星盘、本命盘、时空盘、比较盘、马克思、三限盘、日返照、月返照、配对盘、推进盘、次限盘、行运盘、组合盘、太阳弧、组合次限、组合三限盘、时空次限盘、时空三限盘
、马盘次限盘、马盘三限盘、法达盘
通用星盘接口获取
推运数据、年运报告、语料列表、28星宿、天象盘、次限比、三限比、日返比、月返比、塔罗
塔罗牌随机发牌、骰子、骰子占卜、道历、八字、星盘语料、日运语料、月运语料、周运语料
年运语料

### 星盘类型27种

*比较1 比较2 就是交换主副盘的位置，马盘1马盘2，返照1返照2也是如此

### 接口特点
1、皮肤自由设置：全矢量SVG星盘，支持CSS 自定义线条和元素的颜色
2、接口数据广泛：支持公元前xxxxx年-xxxx年数据。
3、高精度：精确的星历数据，高精度星历表，会比一般免费APP 精确
4、星体宫位设置丰富：可供选择行星、小行星、宫位，相位，丰富的现代和古典占星内容。
5、付费接口包括免费语料。
### 星盘皮肤颜色自定义
1、接口提供内联样式的svg星盘，前端可以通过CSS和字体，自己调整星盘的颜色线条颜色，星盘背景色。以及行星符号。
2、实现各种星盘皮肤样式。
### 通用接口报告
接口中提供一些基本的报告，这些报告是基于行星落星座，落宫位的基础解释，报告内容从网上收集，免费提供使用，无版权。
通用接口的日运和二次开发的专用接口不同，通用日运接口没有得分。


## 三、测试
### JAVA PHP PYTHON 调用代码示例
http://www.xingpan.vip/index/index/docs.html
在线测试星盘的效果页面
http://www.xingpan.vip/index/index/westernastrology.html


比如要看布拉德皮特的星盘，
1、输入英文名字pitt
2、点击查找
3、找到pitt.brad这个，点击，会自动填入数据，当然你也可以不找，自己填自己想填的数据

4、高级设置



弹出菜单中的所有选项都是真实可生效的，建议吧主要行星都选择上
点击生成，可以看到
1、星盘图片SVG，星盘上的点都是矢量的有点击事件
2、主要参数，行星落星座，宫位、行星相位，和解释，




弹窗：API 	点击事件需要自己写我们星盘是矢量的，所以每个元素都有编号，可以设置任何响应的事件，比如点击事件（这个点击事件得你们程序猿自己写，因为不同语言接口是带不过去的）


### 效果测试填入

本命	http://xingpan.vip/demo/natal.html
时空盘	 http://xingpan.vip/demo/timesmidpoint.html
 比较盘  	http://xingpan.vip/demo/comparision.html
马克思	http://xingpan.vip/demo/marks.html
三限盘	http://xingpan.vip/demo/thirdprogressed.html
日返照	http://xingpan.vip/demo/solarreturn.html
月返照  http://xingpan.vip/demo/lunarreturn.html
配对盘	http://xingpan.vip/demo/synastry.html

    其他盘不一一列举了，地址在http://www.xingpan.vip/astrology/Apiinterface
页面，每个盘上方。
     
                 
###   程序猿测试地址      程序猿测试地址 
这个测试需要一定程序基础，一般用户可以跳过，如果测试页面不正常，建议用postman测试，因为有时候我们更新了接口，但是这个测试页面没有来得及更新。
http://www.xingpan.vip/astrology/Apiinterface

先获取星盘配置
再测试星盘







