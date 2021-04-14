https://m.kanman.com/ 

## 首页：

### 1）用大流量漫画名作为标题和关键词

    <title>穿越西元3000后漫画 斗罗大陆漫画 斗破苍穹漫画 漫画大全 看漫网 看漫画</title>
    <meta name="keywords" content="穿越西元3000后,偷星九月天,斗罗大陆漫画,斗破苍穹漫画,漫画大全,看漫网,看漫画">
    <meta name="description" itemprop="description" content="看漫画致力于打造国内知名的正版漫画阅读平台，拥有偷星九月天、斗罗大陆、斗破苍穹、浪漫传说、暴走邻家等大批优秀国产漫画的正版授权。看漫画网一直坚持提供漫画免费阅读。看漫画，为漫画而生，看偷星九月天漫画、斗罗大陆漫画、斗破苍穹漫画就上看漫画网">
    <meta itemprop="name" content="穿越西元3000后漫画 斗罗大陆漫画 斗破苍穹漫画 漫画大全  看漫网 看漫画">
    <meta itemprop="image" content="/static/images/favicon.ico">

### 2）在顶部增加分类和搜索两个模块
虽然是隐藏的，但是搜索引擎能看到
常用搜索中，放书名关键词，搜索热词中，放书名关键词。
分类中，放长尾关键词。

### 3）大量使用 a.title 和 img.alt ,而且重复书名，书名后还加上漫画

滑动展示图，也写img.alt和a.title


### 4）使用百度对小说类页面的专用meta

* 书封面页 itemprop="name" 指示快照名称 itemprop="image" 指示快照出图

* 关键词是 书名+免费观看全集/漫画免费版/下拉式阅读 +网站名  完整无广告 全集免费 漫画图片 漫画网
* 使用了 og:type 来指示搜索引擎，自己是小说，并用标准方式给出小说的信息
* 采用了聚类方式，把“详情”“目录”“推荐”“留言”做到了一起。
* 有作者页，也从这里链接引入
还有给作者打call , 打赏，礼物，月票，推荐，评分，分享。等
* 有主角页面，主角和主配角都有页面。给出相关的书名链接。

    <title>我是大仙尊免费观看全集_我是大仙尊漫画免费版_我是大仙尊漫画下拉式阅读-看漫画</title>
    <meta name="keywords" content="我是大仙尊漫画全集免费,我是大仙尊漫画下拉式阅读,我是大仙尊完整版无广告,我是大仙尊漫画,我是大仙尊漫画图片,我是大仙尊漫画网">
    <meta name="description" itemprop="description" content="看漫画在线大全免费看漫画，并提供最新的我是大仙尊漫画下拉式在线免费阅读,我是大仙尊漫画结局,我是大仙尊漫画图片我是大仙尊漫画版在线观看无广告.我是大仙尊漫画免费全集在线观看就来看漫画!">
    <meta itemprop="name" content="上看漫画，《我是大仙尊》 让你看个过瘾哦！">
    <meta itemprop="image" content="https://image.yqmh.com/mh/107289.jpg">  
    <meta property="og:type" content="novel">
    <meta property="og:title" content="我是大仙尊">
    <meta property="og:description" content="【独家/每周五更新】前世是修仙界的绝世天才，被十大天尊陷害自爆而亡，意外重生到了自己二十岁的时候。一心只想着修炼成仙重返仙界的他，成为了地球最强的男人，翻手为云覆手为雨，惹本天尊者，灰飞烟灭！！">
    <meta property="og:image" content="//image.yqmh.com/mh/107289.jpg">
    <meta property="og:novel:category" content="玄幻 漫改 都市 修真 新作">
    <meta property="og:novel:author" content="传奇漫业">
    <meta property="og:novel:book_name" content="我是大仙尊">
    <meta property="og:novel:read_url" content="https://m.kanman.com/107289/">
    <meta property="og:url" content="https://m.kanman.com/107289/">
    <meta property="og:novel:status" content="连载">
    <meta property="og:novel:update_time" content="2021-04-09">
    <meta property="og:novel:latest_chapter_name" content="第1话 仙界至尊，都市重生">
    <meta property="og:novel:latest_chapter_url" content="https://m.kanman.com/107289/1.html">
    <link rel="prefetch prerender" href="1.html">
    <link rel="canonical" href="https://www.kanman.com/107289/">
    <meta name="applicable-device" content="mobile">

## 章节页面

### 1）书名 书名+漫画+章节名

    <meta name="keywords" content="万丈光芒不及你人设,万丈光芒不及你漫画人设">
    <meta name="description" itemprop="description" content="看漫画是为您提供万丈光芒不及你人设、万丈光芒不及你漫画人设免费阅读,本站是更新万丈光芒不及你漫画最快的网站。">
    <meta itemprop="name" content="上看漫画，《万丈光芒不及你》 让你看个过瘾哦！">

章节页面没有做更多的处理，仅仅只有开头的时候有章节标题，在div中增加了一个chapter-name，其他的没有做。
可能是因为考录到不需要搜索引擎收录章节。

### 2）下拉式阅读

内容上所谓的下拉式阅读，就是弄一个框架，下拉到底部的时候，Ajax读取下一章的内容，Add到框架中。
并不难实现。
这种“下拉式”的章节页面，头和尾都是看不到的，所以也没有在头部和尾部做更多的处理。

>`下拉页面 Ajax调用`

    https://m.kanman.com/api/getchapterinfov2?product_id=1&productname=kmh&platformname=wap&comic_id=105956&chapter_newid=31&isWebp=1&quality=low

>`下拉页面 Ajax调用回复`

    {"data":{"comic_id":105956,"comic_newid":"hslrhmxnq","comic_name":"万丈光芒不及你","last_chapter_id":"1771707","last_chapter_newid":"di260hua-1615895720002","last_chapter_name":"第260话 李奶奶的传奇一生","show_type":1,"readtype":1,"comic_status":1,"charge_paid":0,"charge_coin_free":1,"update_time":1615895720000,"boo_virtual_coin":true,"charge_status":"10000000000000000000","charge_share_free":1,"charge_advertise_free":1,"charge_truetime_free":1,"charge_limittime_free":1,"charge_limitline_free":1,"charge_vip_free":1,"charge_spread_free":1,"charge_game_free":1,"charge_coupons_free":1,"charge_lottery_free":1,"charge_limittime_paid":1,"charge_limitline_paid":1,"charge_others_paid":1,"charge_credit_paid":1,"is_copyright":1,"current_chapter":{"chapter_name":"第31话 尹伊沫的善良","chapter_newid":"31","chapter_id":1506033,"chapter_domain":"isamanhua.com","start_num":1,"end_num":12,"price":0,"chapter_image_addr":"/feature/1506033_2_1.jpg","create_date":1523264069977,"chapter_img_list":["http://chapter.manhualang.com/comic/W/%E4%B8%87%E4%B8%88%E5%85%89%E8%8A%92%E4%B8%8D%E5%8F%8A%E4%BD%A0/%E7%AC%AC31%E8%AF%9DF4/1.jpg-kmh.low.webp?auth_key=1618475749-c5caf3d1fd464581adb03bb1ede51562-0-ed723d167e0c9c39c607222f965d602c"]},"next_chapter":{"chapter_id":1506034,"chapter_newid":"32","chapter_name":"第32话 被总裁抓住了","price":0,"chapter_image_addr":"","create_time":"2018-05-17T16:07:34.000Z","topic_copyright":"","chapter_domain":"cnmanhua.com","rule":"W/万丈光芒不及你重切版/第32话v1/{i}.jpg","start_num":1,"end_num":15,"create_date":1523264069977,"chapter_img_list":["http://chapter.cnmanhua.com/comic/W/%E4%B8%87%E4%B8%88%E5%85%89%E8%8A%92%E4%B8%8D%E5%8F%8A%E4%BD%A0%E9%87%8D%E5%88%87%E7%89%88/%E7%AC%AC32%E8%AF%9Dv1/1.jpg-kmh.low.webp?auth_key=1618475749-f8aefa82f16d446d8bf66053aa4adbc0-0-f5a390f8096a3c2005915c96ff337d50","http://chapter.cnmanhua.com/comic/W/%E4%B8%87%E4%B8%88%E5%85%89%E8%8A%92%E4%B8%8D%E5%8F%8A%E4%BD%A0%E9%87%8D%E5%88%87%E7%89%88/%E7%AC%AC32%E8%AF%9Dv1/2.jpg-kmh.low.webp?auth_key=1618475749-21943fd336a64e66893b2ad5930b8050-0-169fa17a18c78872ee3fe331f6ab308c","http://chapter.cnmanhua.com/comic/W/%E4%B8%87%E4%B8%88%E5%85%89%E8%8A%92%E4%B8%8D%E5%8F%8A%E4%BD%A0%E9%87%8D%E5%88%87%E7%89%88/%E7%AC%AC32%E8%AF%9Dv1/3.jpg-kmh.low.webp?auth_key=1618475749-310d45866e394cd782c6ffb32f765b08-0-777b699afc3f8ea2acae1b6da68d545d","http://chapter.cnmanhua.com/comic/W/%E4%B8%87%E4%B8%88%E5%85%89%E8%8A%92%E4%B8%8D%E5%8F%8A%E4%BD%A0%E9%87%8D%E5%88%87%E7%89%88/%E7%AC%AC32%E8%AF%9Dv1/4.jpg-kmh.low.webp?auth_key=1618475749-6dca1c3dfa2143419870269c1a107f83-0-c368d6c092453ec8c2bc6107b1aa9eee",]}},"status":0,"message":"ok"}

>`下拉页面框架`

    <div class="acgn-reader-chapter__item-box" chapter-id="20" chapter-name="第20话 送女神回家"><div style="width:auto" class="acgn-reader-chapter__item loading" chapter-index="1" chapter-pid="20">
        <div class="acgn-reader-chapter__loading-tip">1</div>
      </div><div style="width:auto" class="acgn-reader-chapter__item loading" chapter-index="2" chapter-pid="20">
        <div class="acgn-reader-chapter__loading-tip">2</div>
      </div><div style="width:auto" class="acgn-reader-chapter__item loading" chapter-index="3" chapter-pid="20">
        <div class="acgn-reader-chapter__loading-tip">3</div>
      </div>

      </div></div>


>`滑动图的例子`

        <img class="lazy-image" src="/static/images/comm/space.gif" alt="仙尊奶爸当赘婿,仙尊奶爸当赘婿漫画" style="background: url("//cms.samanlehua.com/cms/chendan/378cc870-9b34-11eb-9947-31bb94f846cb.png-noresize.webp") center center / cover no-repeat; opacity: 1;">

>`搜索 热门搜索的例子`
        
        <div class="hot-search" id="js_hotSearch"><div class="hot-hd">热门搜索</div>
	    <ul class="hot-tags">		
    	<li class="tag" data-id="106584" style="background: #fffae6; color: #ffc323;">
					哦，我的宠妃大人
				</li>				
				<li class="tag" data-id="107451" style="background: #ebf7ff; color: #3bafff;">
					踏碎仙河
				</li>		
    </ul></div>

>`书名项的例子`

        <li class="card r1c2">
        <a href="/107454/" title="女帝的后宫漫画">
        <div class="card-graph r16x16">
         <img class="lazy-image" src="/static/images/comm/space.gif" alt="女帝的后宫,女帝的后宫漫画" style="background: url(&quot;//image.yqmh.com/mh/107454.jpg-300x300.webp&quot;) center center / cover no-repeat; opacity: 1;">
        <div class="abs-bottom">
         <ul class="tags-list">
             <li class="item">搞笑</li>
             <li class="item">恋爱</li>
            <li class="item">后宫</li>
            </ul>
        </div>
        </div>
        <div class="card-title">女帝的后宫</div>
        <div class="card-text">霸道女总的逆后宫攻略</div>
    </a>
    </li>