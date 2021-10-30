### 概念：自行创造可从网络访问的json文件，然后用香色闺阁写发现规则来parse文件

此方法需要把需要添加到书架的书籍信息写进一个json文件。key配对和名称随意，但需要与发现规则一同，否则源无法用。
信息至少需要书籍名称以及书籍链接，其他的信息没必要，尤其是带有详情规则的源。

如果对html或者xml更熟悉那么可以自行发挥，只要规则和文件匹配

##### 列子：

若格式如下：

[
  {
    "coverUrl": " ",
    "intro": "“ ",
    "status": " ",
    "kind": " ",
    "latestChapterTitle": " ",
    "latestChapterTime":  ,
    "wordCount": " ",
    "name": " ",
    "bookUrl": " ",
    "author": " "
  },
  {
    "coverUrl": " ",
    "intro": " ",
    "status": " ",
    "kind": " ",
    "latestChapterTitle": " ",
    "latestChapterTime": ,
    "wordCount": " ",
    "name": " ",
    "bookUrl": " ",
    "author": " "
  }
]

那写发现规则时需要填：

请求信息：指向创造的json链接，如果上传到gitee那么填入json的原始数据

列表：l        (注：这个是小写L字符)

书名：name

作者：author

图标：coverUrl

简介：intro

类别：kind

状态：status

字数：wordCount

最后一章标题：latestChapterTitle

书本详情页地址：bookUrl

#### 需要实用的参考了话请见：

json文件：https://gitee.com/haitang-blossoms/xiangsesource/blob/master/otherdependencies/suibian.json

带有parse json发现规则的源：https://gitee.com/haitang-blossoms/xiangsesource/blob/master/otherdependencies/shubaowm.xbs



希望有人能看得懂此胡言乱语且实用