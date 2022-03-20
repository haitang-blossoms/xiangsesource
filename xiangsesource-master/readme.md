备注、notes：
|中文|eng|
|--|--|
|书源权重是必要参数，但可按照自己需求改变，建议1-9999的数量|priority of booksources is required, but you can edit based on needs, number ranging from 1-9999|
|按照文件对应的参数来填写源配置，示例：json文件里显示 `"list": "//ul/li",` 那就在列表(list)里填 `//ul/li`|fill out booksource rules based on the json file, ex: if json shows: `"list": "//ul/li",` then in list type: `//ul/li`|
|若一个参数的对象是空白("")，那就代表没有规则可填，导致有的源可能内容发现少点|if an object corresponds to empty (""), then there is nothing to fill, so less information may be parsed for|
|🏴󠁧󠁢󠁥󠁮󠁧󠁿为英文资源|🏴󠁧󠁢󠁥󠁮󠁧󠁿 represents English content source|
|🔒为正版|🔒 represents official raws site|
|🍪为可登录，可自行修改httpHeaders or 登录url，不一定会带来更多功能![](https://z3.ax1x.com/2021/10/17/5YnSdf.gif)|🍪represents source can login with cookies in httpHeaders or login url, may or may not bring additional functions|
|🪧||

# 源-sources
## 文本-text

|源名-source name|链接-link|标注|备注|notes|
|--|--|--|--|--|
|晋江文学城-Jinjiang Literature City|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/jjwxc.json`|🔒🍪|||
|豆腐小说-Doufu Novel|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/doufu.json`|🔒|||
|书耽小说-Shudan Novel|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/shubl.json`|🔒🍪|||
|长佩文学-Changpei Literature|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/gongzicp.json`|🔒🍪|发现板块有点内容获取缺失的问题，但大部分应该能用|discover rules have a slight content problem, but most of it should work|
|寒武纪年|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/hanwujinian.json`|🔒|||
|悸花阅读|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/lestory.json`|🔒|||
|恋文/Lovenovel|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/lovenovelapp.json`|🔒🏴󠁧󠁢󠁥󠁮󠁧󠁿|中英皆有|both English and Chinese|
|笔趣阁xswang|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/biqugexswang.json`|🍪|||
|笔下文学|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/bxwxorg.json`|🍪|||
|腐小说|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/xpsam.json`|🍪|||
|可乐小说网|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/xklxsw.json`|🍪|||
|梦阮小说|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/mengruan.json`||||
|All Novel|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/allnovel.json`|🏴󠁧󠁢󠁥󠁮󠁧󠁿|||
|书宝网|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/shubaow.json`|🍪|||
|Collins English Dictionary|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/collinsdictionary.json`|🏴󠁧󠁢󠁥󠁮󠁧󠁿|字典，额，随便拿来玩玩呗|for fun, because why would you have a source just for dictionaries?|
|NovelUpdates|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/novelupdates.json`|🏴󠁧󠁢󠁥󠁮󠁧󠁿🍪|资源导航网站，章节内容需按网址修改|resource navigation, content rules should be edited based on what site is redirected to|
|60看书|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/60ks.json`|🍪|网址搜索功能无法用，没规则|no search function|
|101小说典藏网|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/novel101.json`||繁体字，没搜索|traditional characters, no search|
|镇魂小说|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/zhenhunxiaoshuo.json`||||
|358小说|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/35851.json`||||
|维基阅读|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/wikiyuedu.json`||书籍也可从书单寻|books can be searched for from the booklist|
|AO3|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/archiveofourown.json`|🍪|18+需要cookie/登录；那么多标签我是不会写发现规则的|cookie/login required for 18+; what the heck there are so many tags no way am i writing rules for book explore|
|sparknotes|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/wikiyuedu.json`||你用这个app看学习资料干啥？？？|what are you doing reading study guides in this app for???|
|mmKuu|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/mmkuu.json`||||
|香香腐宅小说|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/boylovenovel.json`||||
|耽美小说大全|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/dmxsdq.json`||全文为单一章节||
||||||
## 图片-images
|源名-source name|链接-link|标注|备注|notes|
|--|--|--|--|--|
|哔哩哔哩漫画|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/bilibilimanga.json`|🔒|||
|Bilibili Comics|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/bilibilicomics.json`|🔒🏴󠁧󠁢󠁥󠁮󠁧󠁿|中英皆有|both English and Chinese|
|腾讯动漫|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/macqq.json`|🔒🍪|||
|Mangaowl|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/mangaowl.json`|🏴󠁧󠁢󠁥󠁮󠁧󠁿🍪||🔪cloudflare deems this source unusable|
|漫蛙|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/manwa.json`|🍪|||
|mangadex|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/mangadex.json`|🏴󠁧󠁢󠁥󠁮󠁧󠁿|||
|365Manga|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/365manga.json`|🏴󠁧󠁢󠁥󠁮󠁧󠁿🍪|||
|MangaTuli|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/mangatuli.json`|🏴󠁧󠁢󠁥󠁮󠁧󠁿🍪|||
|Manga4Life|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/manga4life.json`|🏴󠁧󠁢󠁥󠁮󠁧󠁿🍪|||
|Lilymanga|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/lilymanga.json`|🏴󠁧󠁢󠁥󠁮󠁧󠁿🍪|||
|MangaHasu|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/mangahasu.json`|🏴󠁧󠁢󠁥󠁮󠁧󠁿|||
|MangaNato|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/manganato.json`|🏴󠁧󠁢󠁥󠁮󠁧󠁿|||
|Bato.To|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/batoto.json`|🏴󠁧󠁢󠁥󠁮󠁧󠁿|多语言|multiple languages|
|Suburban Fairy Tales|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/francisbonnet.json`|🏴󠁧󠁢󠁥󠁮󠁧󠁿|没多少但是三格漫我挺推荐的|there's not much but the comic is one i recommend|
|快看漫画|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/kkmh.json`|🔒🍪|||
|香香腐宅|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/boylove.json`|🍪|||
|包子漫画|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/baozimh.json`||||
|腐漫漫画|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/fumanmi.json`||||
|漫画魂|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/manhuahun.json`||||
|K漫画啦|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/kanmanhuala.json`||||
|国漫吧|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/guomanla.json`||||
|歪歪腐漫|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/waiwaifu.json`||||
|漫画库|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/manhuacool.json`||||
|言耽社|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/yandanshe.json`||单章节不可看，懒得修复|single chapter unviewable|
||||||
## 音频-audio
|源名-source name|链接-link|标注|备注|notes|
|--|--|--|--|--|
|New Temp Drama House|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/tempyuriradiohouse.json`||单个音频为一个书籍|single audio equates one sole book|
|水哥故事会|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/shuige.json`||||
|Mixes.Cloud|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/mixescloud.json`||单个音频为一个书籍|single audio equates one sole book|
|猫耳fM|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/missevan.json`|🔒|||
|寒武纪年|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/hanwujinianyousheng.json`|🔒|||
|听姬|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/himehear.json`|🔒|奇了怪了，三月十五二零二二今日测试付费剧集居然能通过api免费听，所以快点存这个资源哈哈|paid episodes can be listened to for free through this api, save em quick lol|
|网易云音乐|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/music163.json`|🔒|单个音频为一个书籍；可修改|single audio equates one sole book; can be edited|
|ishuyin|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/ishuyin.json`||||
|西雅图中文电台|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/chineseradioseattle.json`||不知道为啥写了这个|idk why i wrote this|
|克拉漫播|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/manbo.json`|🔒|||
|哔哩哔哩|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/bilibiliaudio.json`|🔒|单个音频为一书籍；仅视频的音频，适合听书；可被修改来看视频（但视频没有音频）|single audio equates one sole book; suitable for listening to audiobooks; can be edited to view video|
|喜马拉雅|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/ximalaya.json`|🔒|超多发现规则，可累死个我勒不会写更全啦，有需求就自行上网站找专辑再搜索呗||
|轻音社|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/fuciyuanbang.json`||||
|MuXiv Music|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/muxiv.json`||||
|听书王|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/wukongks.json`||||
|有声小说大全api|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/yst8.json`||||
||||||
## 视频-video
|源名-source name|链接-link|标注|备注|notes|
|--|--|--|--|--|
|快看漫剧|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/kuaikancomicdrama.json`|🔒|||
|YouTube|`https://cdn.jsdelivr.net/gh/haitang-blossoms/xiangsesource@main/xiangsesource-master/newsource/youtube.json`|🔒🍪|单个视频为一书籍;使用的是第三方服务，2+小时时长不可看，可能会崩; 可被修改为听书源; 发现规则可修改moreKeys|single video equates one book; uses third party service, 2+ hour video may not work; can be edited to mp3; discover can be edited in moreKeys|
||||||
