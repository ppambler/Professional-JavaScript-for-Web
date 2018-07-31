# 1.1　JavaScript简史

## ★出现原因

那时大多数网民的网速就只有28.8kib/s，然而网页的内容和复杂性（如简单的表单验证）却是在不断地增加。可想而知，就如政治课本常说的那句话一样：

> 我国社会的主要矛盾是人民日益增长的物质文化需要同落后的社会生产之间的矛盾

想要提高网速？——想都不要想

为此Netscape公司（大佬），决定着手开发一种客户端语言，用于处理简单的验证。总之就是在数据提交到服务器之前，希望有个程序可以过滤一下。

## ★谁设计的JavaScript

来自当时就职于 Netscape 公司的布兰登·艾奇（Brendan Eich）。本来是叫LiveScript的，可为了炒热公司即将发布的Netscape Navigator 2（搭配了脚本语言的浏览器很高大尚），而当时恰巧Java红红火火，于是就改名为[JavaScript](https://zh.wikipedia.org/wiki/JavaScript)了。这就是JavaScript的1.0版本……

## ★JavaScript的发展势头

1. 由于JavaScript1.0大热，为此趁热打铁， Netscape 随即在 Netscape Navigator 3 中又发布了 JavaScript 1.1

2. IE3.0添加JavaScript（具体一点指的是JScript）以后，标志着 JavaScript 作为一门语言，其开发向前迈进了一大步。毕竟[微软](https://zh.wikipedia.org/wiki/%E5%BE%AE%E8%BD%AF)正式进军了Web浏览器领域，而有了竞争对手，产品才会更强大……

   

## ★Netscape VS 微软

微软：看不起我家IE浏览器是吧？还把自己公司定位为市场领袖型公司是吧？他奶奶的，你们不是发布了版本3的浏览器吗？这下我就对自家产品IE投入更多资源。不好意思，我要发布IE3了，而且我也要添加脚本语言，名字叫「JScript」。抱歉我家的「JScript」是基于你们家的 Netscape JavaScript 1.0 开发的，就是气死你，呵呵哒……

## ★两个不同版本的JavaScript

- 一个是Netscape Navigator 中的 JavaScript
- 一个是Internet Explorer 中的 JScript

版本有了差异，那么写JavaScript的开发的开发人员，就得要学这个版本的语法了啊！一个页面要写两份，岂不是要GG了……

其它编程语言，如C等都是有标准规定语法和特性的。况且Web势头发展是很猛的，日后说不定会有其它的浏览器产商，为此随着业界担心的日益加剧，JavaScript的标准化问题被提上了议事日程。

## ★JavaScript1.1、ECMA、ISO/IEC

1997年，以JavaScript1.1为蓝本很荣幸地被建议提交到了ECMA，而基于JavaScript1.0实现的JScript就没有这个荣幸了。ECMA指定TC39（关注脚本语言发展的公司的程序员组成，如 Netscape、Sun、微软……）负责“标准化一种通用、跨平台、供应商中立的脚本语言的语法和语义”。TC39就像是编辑一样，而JavaScript1.1则是原稿，编辑经过数月的努力完成了 ECMA-262——定义一种名为 ECMAScript（发音为“ek-ma-script”）的新脚本语言的标准。

1998年，ISO/IEC也采用了 ECMAScript 作为标准（即 ISO/IEC-16262）。自此以后，浏览器开发商就开始致力于将 ECMAScript 作为各自 JavaScript 实现的基础，也在不同程度上取得了成功。

## ★小结

- **JavaScript的简史：**

  - 种子阶段：

    在Web日益流行的背景下，网页的大小和复杂性开始不断地增加，而网速依旧如此的慢，如做个表单验证也要考验用户的耐心——为此Netscape 公司打算开发一种客户端语言

  - 发芽阶段：

    布兰登·艾奇为Netscape Navigator 2 开发一种名为 JavaScript 的脚本语言，这是JavaScript1.0

  - 成长阶段：

    1. Netscape在 Netscape Navigator 3 中发布了 JavaScript 1.1，而微软不灭威风，在IE3.0中发布了基于JavaScript1.0的JScript
    2. 由于不同版本并存的JavaScript会在日后导致很多问题，所以需要有标准规定 JavaScript 的语法和特性。为此1997年， JavaScript 1.1以蓝本的身份被提交到了ECMA，数月后TC39发布了ECMAScript-262——定义一种名为 ECMAScript的新脚本语言的标准。
    3. 1998年，ISO/IEC也采用了 ECMAScript 作为标准（即 ISO/IEC-16262）。从此，浏览器开发商就开始致力于将 ECMAScript 作为各自 JavaScript 实现的基础。
    4. ……



---

## ★Q&A

**①蓝本为何意？**

它的同义词是[底本](https://baike.baidu.com/item/%E5%BA%95%E6%9C%AC)，到底蓝本是不是同原稿一个意思，根据这个：[原稿跟草稿有什麼差???](https://tw.answers.yahoo.com/question/index?qid=20050801000012KK15868) 东东说到的「原稿纸专用的蓝色铅笔」，而这里说的蓝色铅笔在其答案中有提到：

> 蓝色铅笔：是因为在印制成书时，这种蓝色铅笔画上去是不会被印出来的，所以有些漫画家就用这个来画在原稿上。 

同样有个蓝字，那么蓝本和原稿就是一个意思咯！

那么这样的话：「这部电视剧以同名小说为蓝本改编而成 」？我在想为啥出版的书会有错别字？是原稿的锅，还是校稿的锅？或者说都有责任……

==**总之，你的简历最好不要有错别字**==



**②Ecma、TC39、ISO/IEC？**

都是制定标准的，那么制定标准的意义何在呢？——你要知道一个东西是好的还是不好的是相对而言的，就如面试要求说「你这个技能是了解？熟练？还是精通？」一样，没有一个共有的标准的话 ，那么沟通起来就GG了……如前后端撕逼大战，互相丢锅……



**③邯郸学步**？

释义：

> 比喻一味模仿别人,非但没有学到别人的长处,反倒失去了自身的特色。也作[学步邯郸](https://zh.wiktionary.org/w/index.php?title=%E5%AD%A6%E6%AD%A5%E9%82%AF%E9%83%B8&action=edit&redlink=1)。

不要只是模仿结果，因为这只是量的堆积而已，你得要去发现这样做的逻辑所在，然后加以运用到自己未知的事物身上，总之有种「元」的味道，或者说是触类旁通……



**④「脚本」是什么东东？**

在演员眼中，就是看脚本说台词；在程序员眼中，就是一系列指令 ，不过这些指令是给计算机看，然后解释执行的，特点是短小精悍、自动化（程序都有这样的标签）



**⑤Netscape Navigator 「1/2/3」 是什么鬼？**

这是版本号啊！而且是这样的：

> 版本号没有统一的标准，完全由开发者自己决定。但比较常见的是X.Y.Z的版本标示，X更新的话就表示有重大更新，如界面重大更新等，或者不兼容老版本；Y更新表示添加了新的功能；Z表示修订错误和bug。
>
> 也有的软件用发布的年月做表示，比如Ubuntu就是如此。 

摘录自：软件升级时，版本号是怎么定的？ - [Xizhi Zhu的回答 - 知乎](https://www.zhihu.com/question/23326640/answer/24216963) 

我看了一下自己的[npm](https://zh.wikipedia.org/wiki/Npm)和node版本：

- npm：3.10.9
- node：v6.9.2

node多了个v也许是更明确这是版本之意，目前npm的稳定版本是6.2.0 ，而node当前最新版本为10.7.0 

关于node的版本有两个可选的[下载](https://nodejs.org/en/download/)：一个是LTS（全称是Long Term Support，长期支持版），一个是Current。前者是推荐广大用户使用的，它们二者这个的区别呢？

> - LTS版本支持之前的一些老版本特性，可以让你丝滑升级！ 即可靠，稳定 ，可以线上使用。
> - Current版本指新版本不是beta版本 ，由于是新的，可能会有不可预料的bug……

参考：[Node.js 的 LTS 版本意味着什么？](https://www.zhihu.com/question/35512237)

这是不是意味着，我可以升级本地的node，我之前一直在想要把node给升级了，可是那些与它依赖在一起的工具会不会受到影响？

试一下？

升级npm：

```bash
npm -g install npm@5.6.0
```

而node呢？听说windows系统下只有覆盖安装了，而且是在原安装目录安装覆盖……

 于node官网上下载，安装后，检查当前node的版本为v8.11.3，而npm则是5.6.0

目前还未测试过，不知道gitbook等工具会不会受到影响，照理说，应该不会的……

ps：由于Ruby 靠 z 的奇偶来区分 stable 和 test ，所以node的版本是不是也是如此，就不得而知了。npm更新后，我就不用在[安装依赖](https://segmentfault.com/q/1010000000403629)的时候添加 `-S`等参数了……



**⑥目前各大浏览器的对ECMAScript的兼容性情况？**

传送门：[ECMAScript](https://zh.wikipedia.org/wiki/ECMAScript)、[Kangax’ ES7 兼容性表](https://kangax.github.io/compat-table/es7/)  



---

## ★参考链接

- [蓝本](https://baike.baidu.com/item/%E8%93%9D%E6%9C%AC) 、[蓝本是什么意思啊？](https://zhidao.baidu.com/question/588939675.html?qbl=relate_question_1)、[如何理解Flask中的蓝本？](https://www.zhihu.com/question/31748237)
- [书籍出版前都是如何校对的？一个字一个字的看吗？](https://www.zhihu.com/question/20831146)
- [编辑/校對工作主要是做什麼的？入行門檻高嗎？](https://www.zhihu.com/question/32005102)
- [为什么正版图书里也会出现错别字呢？](https://zhidao.baidu.com/question/517535724.html?qbl=relate_question_2)
- [如何出版一本书？](https://www.zhihu.com/question/19614586)
- [你以为编辑看稿子就是看错别字和病句吗？大错特错！](https://www.douban.com/note/517339197/)
- [投稿有错别字，编辑看到了会不会直接OUT掉啊？](https://zhidao.baidu.com/question/140632964.html) 
- [Ecma国际](https://zh.wikipedia.org/wiki/Ecma%E5%9B%BD%E9%99%85)、[ECMAScript](https://zh.wikipedia.org/wiki/ECMAScript)
- [[译] TC39，ECMAScript 和 JavaScript 的未来（Part 1）](https://medium.com/@justjavac/tc39-ecmascript-proposals-future-of-javascript-386b12149880)、[★控制ECMAScript版本发布的TC39流程](https://www.zcfy.cc/article/the-tc39-process-for-ecmascript-features)
- [ISO](https://zh.wikipedia.org/wiki/%E5%9C%8B%E9%9A%9B%E6%A8%99%E6%BA%96%E5%8C%96%E7%B5%84%E7%B9%94)、[IEC](https://zh.wikipedia.org/wiki/%E5%9B%BD%E9%99%85%E7%94%B5%E5%B7%A5%E5%A7%94%E5%91%98%E4%BC%9A)、[GB、ISO、IEC、IEEE标准有什么区别？](https://www.zhihu.com/question/29517540)、 [★ISO、IEC、ITU——国际三大标准化组织](http://www.aqsiq.gov.cn/jgfl/bgt/tsxx/201210/t20121017_261200.htm) 
- [人们为什么要制定标准或是规范，“标准”都有什么作用，请举例说明，场景尽量宽泛些？](https://www.zhihu.com/question/61098375/answer/184912179)
- [面试词典：什么叫精通？什么叫熟悉？什么叫了解？](https://zhuanlan.zhihu.com/p/25463444)
- [邯郸学步](https://zh.wiktionary.org/zh-hans/%E9%82%AF%E9%83%B8%E5%AD%A6%E6%AD%A5)、[邯郸学步的故事](http://chengyu.t086.com/gushi/66.html)、[邯郸学步](https://baike.baidu.com/item/%E9%82%AF%E9%83%B8%E5%AD%A6%E6%AD%A5) 
- [如何用通俗易懂的语言解释脚本（script）是什么？](https://www.zhihu.com/question/19901542)
- [软件的版本号有时候会类似 1.0.1 / 3.5.3，这些都是怎么决定的？](https://www.zhihu.com/question/21405746)