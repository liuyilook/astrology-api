# astrology-api
astrology api 星盘 api 星盘接口
<p>XINGPANVIP的API接口介绍</p>

<p>一、通用星盘接口和专用接口区别</p>
<p>1、通用接口（包月服务）</p>
<p>是按月收费的。星盘通用接口，支持的主要是行星的位置数据和svg星盘，这个是包括在月租费里面的。</p>
<p>2、专用接口（一次性费用）</p>
<p>专用接口是一些特殊的，不同于星盘位置数据和svg星盘的特殊功能，专用接口是基于通用接口开发的，用户体验感更好的产品。专用接口是一次性费用，但是购买专用接口前必须先购买通用接口。</p>
<p>3、通用接口价格见第一部分，专用接口价格见第二部分，通用接口为按月计费，专用接口为一次性费用。</p>
<p>二、通用星盘接口价格</p>
<p>http://xingpan.vip/index/index/pricing.html</p>
<p>可以查阅</p>


<p>测试接口文档</p>
<p>http://www.xingpan.vip/astrology/Apiinterface</p>
<p>测试access_token:989f888c4283e2cc2d8a5aa4af60932c</p>

<p>测试的token可能很多人测，所以有时候可能会比较慢！出错，请找适当时间重新测试</p>


<p>通用接口包括</p>
<p>通用接口包括在套餐中，通用接口是按照月或者季度，年，周期收费。</p>


<p>基础接口</p>
<p>获取星盘配置</p>
<p>新闻内容、星盘、本命盘、时空盘、比较盘、马克思、三限盘、日返照、月返照、配对盘、推进盘、次限盘、行运盘、组合盘、太阳弧、组合次限、组合三限盘、时空次限盘、时空三限盘</p>
<p>、马盘次限盘、马盘三限盘、法达盘</p>
<p>通用星盘接口获取</p>
<p>推运数据、年运报告、语料列表、28星宿、天象盘、次限比、三限比、日返比、月返比、塔罗</p>
<p>塔罗牌随机发牌、骰子、骰子占卜、道历、八字、星盘语料、日运语料、月运语料、周运语料</p>
<p>年运语料</p>

<p>星盘类型27种</p>
<p>%为合盘$为推运	展示盘情况	输入说明</p>
<p>本命盘	单盘，个人本命	个人数据</p>
<p>天象盘%	单盘	默认此时天象</p>
<p>行运盘%	双盘，个人VS此时天象	个人VS此时时间</p>
<p>次限盘%	次限单盘	需要个人数据+推运时间</p>
<p>次限比较盘%	双盘，本命VS次限单盘	个人数据+推运时间</p>
<p>三限盘%	三限单盘	个人数据+推运时间</p>
<p>三限比较盘%	双盘，本命VS三限单盘	个人数据+推运时间</p>
<p>太阳返照盘%	单盘，日返单盘	个人数据+推运时间</p>
<p>日返比较盘1%	双盘，本命VS日返单盘	个人数据+推运时间</p>
<p>日返比较盘2%	双盘，日返单盘VS本命	个人数据+推运时间</p>
<p>太阳弧盘%	双盘，本命VS太阳弧盘	个人数据+推运时间</p>
<p>月亮返照盘%	单盘，月返单盘	个人数据+推运时间</p>
<p>月返比较盘1%	双盘，本命VS月返盘	个人数据+推运时间</p>
<p>月返比较盘2%	双盘，月返盘VS本命	个人数据+推运时间</p>
<p>法达星限%	单盘	个人数据+推运时间</p>
<p>比较盘$	双盘	双人数据</p>
<p>组合中点盘$	单盘	双人数据</p>
<p>时空中点盘$	单盘	双人数据</p>
<p>马克思盘$	单盘	双人数据</p>
<p>组合次限盘$	单盘	双人数据+推运时间</p>
<p>组合三限盘$	单盘	双人数据+推运时间</p>
<p>时空次限盘$	单盘	双人数据+推运时间</p>
<p>时空三限盘$	单盘	双人数据+推运时间</p>
<p>马盘次限盘$	单盘	双人数据+推运时间</p>
<p>马盘三限盘$	单盘	双人数据+推运时间</p>
<p>*比较1 比较2 就是交换主副盘的位置，马盘1马盘2，返照1返照2也是如此</p>

<p>接口特点</p>
<p>1、皮肤自由设置：全矢量SVG星盘，支持CSS 自定义线条和元素的颜色</p>
<p>2、接口数据广泛：支持公元前xxxxx年-xxxx年数据。</p>
<p>3、高精度：精确的星历数据，高精度星历表，会比一般免费APP 精确</p>
<p>4、星体宫位设置丰富：可供选择行星、小行星、宫位，相位，丰富的现代和古典占星内容。</p>
<p>5、付费接口包括免费语料。</p>
<p>星盘皮肤颜色自定义</p>
<p>1、接口提供内联样式的svg星盘，前端可以通过CSS和字体，自己调整星盘的颜色线条颜色，星盘背景色。以及行星符号。</p>
<p>2、实现各种星盘皮肤样式。</p>
<p>通用接口报告</p>
<p>接口中提供一些基本的报告，这些报告是基于行星落星座，落宫位的基础解释，报告内容从网上收集，免费提供使用，无版权。</p>
<p>通用接口的日运和二次开发的专用接口不同，通用日运接口没有得分。</p>
<p>三、专用的接口类型</p>
<p>为了满足不同用户的个性化需求，我们也可以提供专用接口，可以按照客户需求，付费开发，专用接口需要调用星盘普通接口数据，所以购买专用接口必须是我们的通用接口客户。</p>
<p>专用接口的服务器由我公司维护，专用接口和通用接口一样通过api调用。</p>
<p>专用接口价格组成</p>
<p>费用主要包括开发费+语料费用+ui费用，</p>
<p>开发费：满足客户个性化需要产生的开发费，确定需求后定价，定制报告，包括年运，事业，爱情，婚姻，性格，学业，财富，等，定制接口的开发费用是一次性的。</p>
<p>语料：因为要编写客户看到的结果页的文字内容，按照客户不同要求，语料字数会有不同，语料字数可以依据要求，增加或者减少，语料字数越多，可能性越大，阅读体验就会越好。语料可以自行准备，或者委托我们编写。</p>
<p>UI设计：是可选项目，可以只要接口自己设计。</p>
<p>二开专用接口的例子和例子价格</p>
<p>以下是几个专用接口的例子和例子价格</p>
<p>产品服务项目	开发	语料预计价格	UI设计	合计（元）	备注</p>
<p>星座九宫格	5000	3000	2000	10000	备注：语料千字150元</p>
<p>运势	5000	30000	2000	37000	备注：语料千字150元</p>
<p>合盘	5000	9000	3000	17000	备注：语料千字150元</p>
<p>爱情	2000	3000	2000	7000	备注：语料千字150元</p>
<p>事业	2000	3000	2000	7000	备注：语料千字150元</p>
<p>其他定制报告	10000	12000	4000	26000	单报告单价</p>
<p>其他定制报告，可以是不包括在以下例子中的，比如生时校正、卜卦、学业，婚姻，爱情，事业，财运，性格，等基于占星原理的报告，可以按照客户的需求定制开发。</p>

<p>基于个人的星座运势</p>

<p>上图界面是测测界面，我们接口实现了类似、甚至更多的功能，我们并没有为测测提供数据支持，上图只作为说明功能用。</p>
<p>星座运势基于个人，出生时间不同，即使只有半小时差距，每日每人也有不同的解释。配套的内容语料17万字。</p>

<p>性格解析九宫格</p>

<p>个人星座解释，每个人不同过的8个行星或者点的落座，这个界面，出生时间差最多两小时是绝对不会完全同的，差4分钟就可能造成差异。</p>
<p>缘分合盘</p>




<p>合盘包括5个维度的得分，以及一句话评价双方关系。及合盘解析（可以选择，也可以只选择得分）</p>










<p>简单的，千字内报告</p>

<p>年运接口</p>
<p>每年的年运报告，提供基于客户出生时间的，占星和生肖报告。</p>
<p>主要包含板块：丨逆行预警丨法达运势丨新年每月月运丨一年中最重要相位影响丨生肖指引丨</p>
<p>在接口文档中包括了年运的接口，可以测试，但数据不一定不是当前年份的。</p>

<p>四、测试</p>
<p>JAVA PHP PYTHON 调用代码示例</p>
<p>http://www.xingpan.vip/index/index/docs.html</p>
<p>在线测试星盘的效果页面</p>
<p>http://www.xingpan.vip/index/index/westernastrology.html</p>


<p>比如要看布拉德皮特的星盘，</p>
<p>1、输入英文名字pitt</p>
<p>2、点击查找</p>
<p>3、找到pitt.brad这个，点击，会自动填入数据，当然你也可以不找，自己填自己想填的数据</p>

<p>4、高级设置</p>



<p>弹出菜单中的所有选项都是真实可生效的，建议吧主要行星都选择上</p>
<p>点击生成，可以看到</p>
<p>1、星盘图片SVG，星盘上的点都是矢量的有点击事件</p>
<p>2、主要参数，行星落星座，宫位、行星相位，和解释，</p>




<p>弹窗：API 	点击事件需要自己写我们星盘是矢量的，所以每个元素都有编号，可以设置任何响应的事件，比如点击事件（这个点击事件得你们程序猿自己写，因为不同语言接口是带不过去的）</p>


<p>效果测试填入</p>

<p>本命	http://xingpan.vip/demo/natal.html</p>
<p>时空盘	 http://xingpan.vip/demo/timesmidpoint.html</p>
<p> 比较盘  	http://xingpan.vip/demo/comparision.html</p>
<p>马克思	http://xingpan.vip/demo/marks.html</p>
<p>三限盘	http://xingpan.vip/demo/thirdprogressed.html</p>
<p>日返照	http://xingpan.vip/demo/solarreturn.html</p>
<p>月返照              	http://xingpan.vip/demo/lunarreturn.html</p>
<p>配对盘	http://xingpan.vip/demo/synastry.html</p>

<p>    其他盘不一一列举了，地址在http://www.xingpan.vip/astrology/Apiinterface</p>
<p>页面，每个盘上方。</p>
<p>     </p>
<p>                 </p>
<p>     程序猿测试地址 </p>
<p>这个测试需要一定程序基础，一般用户可以跳过，如果测试页面不正常，建议用postman测试，因为有时候我们更新了接口，但是这个测试页面没有来得及更新。</p>
<p>http://www.xingpan.vip/astrology/Apiinterface</p>

<p>先获取星盘配置</p>
<p>再测试星盘</p>



<p>五、案例</p>
<p>	接口服务	APP开发	内容	占星逻辑	二开</p>
<p>爱神星	✓	✓	✓		</p>
<p>易测	✓		✓		✓</p>
<p>千聊	✓				</p>
<p>晴开	✓				</p>
<p>轻盐	✓		✓		</p>
<p>准了			✓	✓	</p>
<p>SOUL app	✓				</p>
<p>爱星盘			✓		</p>
<p>智星			✓	✓	</p>
<p>					</p>
<p>					</p>

<p>上表内容包括：占星的语料词条，或者占星报告中的文字，或者成品的运势，或者占星文章</p>


<p>爱神星APP、星盘接口+二开</p>
<p>易测APP 星盘接口+二开</p>
<p>千聊，星盘接口</p>
<p>先开这个https://m.qianliao.net/financial/mine</p>
<p>成为我们这边的用户，https://tools.dachensky.net/tools/wx-start-new-user</p>
<p>晴开，星盘接口+二开</p>

<p>轻盐，星盘接口+二开</p>


<p>准了，报告逻辑+内容</p>
<p>智星，报告逻辑+内容</p>

<p>soulAPP</p>




先获取星盘配置
再测试星盘






