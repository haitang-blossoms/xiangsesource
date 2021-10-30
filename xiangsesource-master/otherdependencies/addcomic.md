# 帮助：发表添加漫剧建议
虽然可以直接报名字然后我搜索漫剧添加到json里，但是这样会麻烦。若想帮忙添加更多可看漫剧那么按照以下执行：

1. 获取漫剧/合集链接
	1. 进入合集的界面![](https://images.gitee.com/uploads/images/2021/1011/031744_96175216_9578335.jpeg "IMG_2367.jpg")
	2. 选择右上角的三点，分享到app（发送给自己是最好的选择；以下为微信的步骤，个人并未尝试其他方法）![](https://images.gitee.com/uploads/images/2021/1011/031826_49899169_9578335.jpeg "IMG_2368.jpg")
	3. 进入app点击刚刚分享的链接![](https://images.gitee.com/uploads/images/2021/1011/031859_024723e4_9578335.jpeg "IMG_2369.jpg")
	4. 选择右上角的三点，复制链接![](https://images.gitee.com/uploads/images/2021/1011/031916_63451525_9578335.jpeg "IMG_2370.jpg"))
	5. 找到链接的compilationId
		1. 链接格式： `https://social.51kuaikan.com/social/social-fe/collection_share?compilationId= 剧集ID`
2. json格式信息
	1. 填入信息的格式： `{
      "detailUrl" : " 输入方才得到的compilationId ",
      "author" : " 输入合集作者 ",
      "bookName" : " 输入合集名称 ",
      "desc" : " 输入合集简介 ",
      "cover" : " 输入合集图标 ",
      "cat : " 输入合集分类 ",
    }`
		1. 必须填的内容： detailUrl，bookName
		2. 选填的内容： author，desc，cover，cat
	2. 列子： `{
      "detailUrl" : "193453152445501456",
      "author" : "宣哲",
      "bookName" : "沈升",
      "desc" : "【本季共10集】向来温柔、安稳、不越轨的沈升，因为发现了老师的某个秘密，原本平稳的生活一去不复返。这个秘密的冲击，让沈升一步步打破自己的条框，开始选择自己真心想做的事。改编自宣哲同名漫画《沈升》，爱，是你我之间共同的秘密。",
      "cover" : "https:\/\/tncache1-f1.v3mh.com\/FhFCnrl4E_Q7ZVcGEYFA6GnoUN7l"
    }`
3. 发布评论到issues板块
	1. 到我的仓库中的issues标签发布您需要我添加的漫剧或者合集
