# FAQ

## ★Gitbook使用

### ◇插件

- search-plus：支持中文全文搜索的插件，默认的只支持搜索英文关键字

### ◇内容书写语法

- 不能出现html标签，为此目前只能用倾斜的语法 `**`来表示了，而且需要注意是字符之间要连贯起来，毕竟你没有加<>也会被渲染出来

  如这样：<script>console.log(1)</script> 这块是看不见的，你 `Ctrl+shift+I`一下这块区域，直白一点就是「右键→☞检查」

  或者是这样： script console.log(2) /script

  还有这样：`<script>` console.log('Hello！world ') `</script>`

  当然后面两个写法在本地浏览是没事的，可是提交到远程仓库就出问题了，可这有区别吗？真是醉了……

  ps：又可以了，真是没事找事了，其实说实在的你见过哪个标签是不写 `<>`是可以运行的？下次出错就看一下markdown语法有没有写错……毕竟是直接用Typora写的笔记

- 本地markdown是可以显示不加http协议的超链接的，而markdown转html后，就得注意了，得要加上http协议才行，如这样 <http://www.baidu.com>，而不是 www.baidu.com

  突然发觉之前的一些超链接的markdown显示需要用`<>`括起来，不然相邻的字符就会被收拢为链接的一部分了

  **总之本地markdown显示的样子和其转换成html的样子，不一定一模一样**

  



