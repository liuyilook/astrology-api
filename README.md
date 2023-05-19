# astrology-api
astrology api 星盘 api 星盘接口![图片](https://github.com/liuyilook/astrology-api/assets/26639682/503805c7-9466-42b8-8650-0340fc1282bb)

<p>XINGPANVIP的API接口介绍</p>
<h1>一、通用星盘接口</h1>


<p>http://xingpan.vip/index/index/pricing.html 可以查阅</p>
<h2>测试接口文档</h2>

<p>http://www.xingpan.vip/astrology/Apiinterface </p>

<p>测试access_token:989f888c4283e2cc2d8a5aa4af60932c</p>

<p>测试的token可能很多人测，所以有时候可能会比较慢！出错，请找适当时间重新测试</p>
<h2>通用接口包括</h2>

<p>通用接口包括在套餐中，通用接口是按照月或者季度，年，周期收费。</p>

<h2>获取星盘配置</h2>

<p>新闻内容、星盘、本命盘、时空盘、比较盘、马克思、三限盘、日返照、月返照、配对盘、推进盘、次限盘、行运盘、组合盘、太阳弧、组合次限、组合三限盘、时空次限盘、时空三限盘 、马盘次限盘、马盘三限盘、法达盘 通用星盘接口获取 推运数据、年运报告、语料列表、28星宿、天象盘、次限比、三限比、日返比、月返比、塔罗 塔罗牌随机发牌、骰子、骰子占卜、道历、八字、星盘语料、日运语料、月运语料、周运语料 年运语料</p>
<h2>星盘类型27种</h2>.
<style type="text/css">
	table.tableizer-table {
		font-size: 12px;
		border: 1px solid #CCC; 
		font-family: Arial, Helvetica, sans-serif;
	} 
	.tableizer-table td {
		padding: 4px;
		margin: 3px;
		border: 1px solid #CCC;
	}
	.tableizer-table th {
		background-color: #104E8B; 
		color: #FFF;
		font-weight: bold;
	}
</style>
<table class="tableizer-table">
<thead><tr class="tableizer-firstrow"><th>%为合盘$为推运</th><th>展示盘情况</th><th>输入说明</th></tr></thead><tbody>
 <tr><td>本命盘</td><td>单盘，个人本命</td><td>个人数据</td></tr>
 <tr><td>天象盘%</td><td>单盘</td><td>默认此时天象</td></tr>
 <tr><td>行运盘%</td><td>双盘，个人VS此时天象</td><td>个人VS此时时间</td></tr>
 <tr><td>次限盘%</td><td>次限单盘</td><td>需要个人数据+推运时间</td></tr>
 <tr><td>次限比较盘%</td><td>双盘，本命VS次限单盘</td><td>个人数据+推运时间</td></tr>
 <tr><td>三限盘%</td><td>三限单盘</td><td>个人数据+推运时间</td></tr>
 <tr><td>三限比较盘%</td><td>双盘，本命VS三限单盘</td><td>个人数据+推运时间</td></tr>
 <tr><td>太阳返照盘%</td><td>单盘，日返单盘</td><td>个人数据+推运时间</td></tr>
 <tr><td>日返比较盘1%</td><td>双盘，本命VS日返单盘</td><td>个人数据+推运时间</td></tr>
 <tr><td>日返比较盘2%</td><td>双盘，日返单盘VS本命</td><td>个人数据+推运时间</td></tr>
 <tr><td>太阳弧盘%</td><td>双盘，本命VS太阳弧盘</td><td>个人数据+推运时间</td></tr>
 <tr><td>月亮返照盘%</td><td>单盘，月返单盘</td><td>个人数据+推运时间</td></tr>
 <tr><td>月返比较盘1%</td><td>双盘，本命VS月返盘</td><td>个人数据+推运时间</td></tr>
 <tr><td>月返比较盘2%</td><td>双盘，月返盘VS本命</td><td>个人数据+推运时间</td></tr>
 <tr><td>法达星限%</td><td>单盘</td><td>个人数据+推运时间</td></tr>
 <tr><td>比较盘$</td><td>双盘</td><td>双人数据</td></tr>
 <tr><td>组合中点盘$</td><td>单盘</td><td>双人数据</td></tr>
 <tr><td>时空中点盘$</td><td>单盘</td><td>双人数据</td></tr>
 <tr><td>马克思盘$</td><td>单盘</td><td>双人数据</td></tr>
 <tr><td>组合次限盘$</td><td>单盘</td><td>双人数据+推运时间</td></tr>
 <tr><td>组合三限盘$</td><td>单盘</td><td>双人数据+推运时间</td></tr>
 <tr><td>时空次限盘$</td><td>单盘</td><td>双人数据+推运时间</td></tr>
 <tr><td>时空三限盘$</td><td>单盘</td><td>双人数据+推运时间</td></tr>
 <tr><td>马盘次限盘$</td><td>单盘</td><td>双人数据+推运时间</td></tr>
 <tr><td>马盘三限盘$</td><td>单盘</td><td>双人数据+推运时间</td></tr>
</tbody></table>

<p>*比较1 比较2 就是交换主副盘的位置，马盘1马盘2，返照1返照2也是如此</p>
<h2>接口特点</h2>

<p>1、皮肤自由设置：全矢量SVG星盘，支持CSS 自定义线条和元素的颜色</p><p> 2、接口数据广泛：支持公元前xxxxx年-xxxx年数据。 </p><p> 3、高精度：精确的星历数据，高精度星历表，会比一般免费APP 精确 </p><p> 4、星体宫位设置丰富：可供选择行星、小行星、宫位，相位，丰富的现代和古典占星内容。 </p><p> 5、付费接口包括免费语料。</p>
<p>星盘皮肤颜色自定义</p>

<p>1、接口提供内联样式的svg星盘，前端可以通过CSS和字体，自己调整星盘的颜色线条颜色，星盘背景色。以及行星符号。 2、实现各种星盘皮肤样式。</p>
<h2>通用接口报告</h2>

<p>接口中提供一些基本的报告，这些报告是基于行星落星座，落宫位的基础解释，报告内容从网上收集，免费提供使用，无版权。 通用接口的日运和二次开发的专用接口不同，通用日运接口没有得分。</p>
<h1>三、测试</h1>
<h2>JAVA PHP PYTHON 调用代码示例</h2>

<p>http://www.xingpan.vip/index/index/docs.html </p>
<p>在线测试星盘的效果页面</p>
 <p>http://www.xingpan.vip/index/index/westernastrology.html</p>

<p>比如要看布拉德皮特的星盘， 1、输入英文名字pitt 2、点击查找 3、找到pitt.brad这个，点击，会自动填入数据，当然你也可以不找，自己填自己想填的数据</p>

<p>4、高级设置</p>

<p>弹出菜单中的所有选项都是真实可生效的，建议吧主要行星都选择上 点击生成，可以看到 1、星盘图片SVG，星盘上的点都是矢量的有点击事件 2、主要参数，行星落星座，宫位、行星相位，和解释，</p>

<p>弹窗：API 点击事件需要自己写我们星盘是矢量的，所以每个元素都有编号，可以设置任何响应的事件，比如点击事件（这个点击事件得你们程序猿自己写，因为不同语言接口是带不过去的）</p>
<p>效果测试填入</p>

<p>本命 http://xingpan.vip/demo/natal.html </p>
<p>时空盘 http://xingpan.vip/demo/timesmidpoint.html </p>
<p>比较盘 http://xingpan.vip/demo/comparision.html </p>
<p>马克思 http://xingpan.vip/demo/marks.html </p>
<p>三限盘 http://xingpan.vip/demo/thirdprogressed.html </p>
<p>日返照 http://xingpan.vip/demo/solarreturn.html </p>
<p>月返照 http://xingpan.vip/demo/lunarreturn.html </p>
<p>配对盘 http://xingpan.vip/demo/synastry.html</p>
<p>其他盘不一一列举了，地址在http://www.xingpan.vip/astrology/Apiinterface</p>

<p>页面，每个盘上方。</p>
<p>程序猿测试地址 程序猿测试地址</p>

<p>这个测试需要一定程序基础，一般用户可以跳过，如果测试页面不正常，建议用postman测试，因为有时候我们更新了接口，但是这个测试页面没有来得及更新。 http://www.xingpan.vip/astrology/Apiinterface</p>

<p>先获取星盘配置 再测试星盘</p>
