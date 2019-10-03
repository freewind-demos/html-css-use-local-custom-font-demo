Css Use Local Custom Font Demo
==============================

这里以google的Bitter字体为例。

需要先下载需要的字体文件。Google自己提供的功能不好用，使用下面这个网址非常好：

https://google-webfonts-helper.herokuapp.com/fonts/bitter?subsets=latin

注意同一个字体有多个不同后缀的文件，是为了兼容不同的浏览器。

然后还需要在CSS中定义一个`@font-face`，声明字体名称、不同格式对应的文件等等。

```
open index.html
```
