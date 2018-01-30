# websafe-font
font-family / font-size / line-height / color / letter-spacing of reading friendly websites

记录了一系列「中文阅读友好」网页的网络安全字体相关 css 属性

*分辨率1920x1080，测试时间为最近更新时间*

针对移动端中文字体设置，可参考[腾讯 AlloyTeam 的相关文章](https://github.com/AlloyTeam/Mars/blob/master/solutions/font-family.md)，设置 `font-family`：

`-apple-system, BlinkMacSystemFont, "PingFang SC", "Helvetica Neue", STHeiti, "Microsoft Yahei", Tahoma, Simsun, sans-serif;`
***
## [flipboard](https://flipboard.com)
[《热血无赖》、《逃生》进入Xbox12月金会员免费阵容](https://flipboard.com/@flipboardcn/%E7%A7%91%E6%8A%80-h8nis64pz/%E3%80%8A%E7%83%AD%E8%A1%80%E6%97%A0%E8%B5%96%E3%80%8B%E3%80%81%E3%80%8A%E9%80%83%E7%94%9F%E3%80%8B%E8%BF%9B%E5%85%A5xbox12%E6%9C%88%E9%87%91%E4%BC%9A%E5%91%98%E5%85%8D%E8%B4%B9%E9%98%B5%E5%AE%B9/a-l2JmBfIPSjChfuufxxrqIA%3Aa%3A8854535-0042494de0%2Fg-cores.com)

```
p {
    font-family: "Tiempos", Georgia, serif;
    font-size: 16px;
    line-height: 1.85em;
    font-weight: 400;
    color: #000;
    -webkit-font-smoothing: antialiased;
    -webkit-tap-highlight-color: rgba(0,0,0,0);
}
```
***
## [知乎专栏](https://zhuanlan.zhihu.com)
[¯\_(ツ)_/¯论不同字体颜文字的特效 （另附颜文字神器下载）](https://zhuanlan.zhihu.com/p/23714718)

```
p {
    font-family: -apple-system, BlinkMacSystemFont, Helvetica Neue, PingFang SC, Microsoft YaHei, Source Han Sans SC, Noto Sans CJK SC, WenQuanYi Micro Hei, sans-serif;
    text-rendering: optimizeLegibility;
    line-height: 1.7;
    color: #333;
}
```
***
## [36氪](http://36kr.com/)
[适老设计：如何让老年人享受数字科技？](http://36kr.com/p/5057296.html)

```
p {
    font-family: PingFang SC, Lantinghei SC, Helvetica Neue, Helvetica, Arial, Microsoft YaHei, \\5FAE\8F6F\96C5\9ED1, STHeitiSC-Light, simsun, \\5B8B\4F53, WenQuanYi Zen Hei, WenQuanYi Micro Hei, "sans-serif";
    line-height: 30px;
    font-size: 16px;
    font-weight: 400;
    color: #3d464d;
    text-size-adjust: 100%;
    word-wrap: break-word;
    -webkit-font-smoothing: antialiased;
    -webkit-tap-highlight-color: rgba(0,0,0,0);
}
```
***
## [简书](http://www.jianshu.com/)
[美女田径运动员，退役后的精彩健身之路（送给想要放弃健身的朋友）](http://www.jianshu.com/p/79351c717e33)

```
p {
    font-family: -apple-system, SF UI Text, Arial, PingFang SC, Hiragino Sans GB, Microsoft YaHei, WenQuanYi Micro Hei, sans-serif;
    color: #2f2f2f;
    font-size: 16px;
    font-weight: 400;
    line-height: 1.7;
    text-size-adjust: 100%;
    word-wrap: break-word;
    -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
```
***
## [Typo.css](http://typo.sofi.sh/)

```
p {
    font-family: "PingFang SC", "Lantinghei SC", "Microsoft Yahei", "Hiragino Sans GB", "Microsoft Sans Serif", "WenQuanYi Micro Hei", sans;
    color: #333;
    text-rendering: optimizelegibility;
    font-weight: 300;
    line-height: 1.8;
}
```
***
## [漢字標準格式](https://css.hanzi.co/manual/sass-api)

```
p {
    line-height: 1.7;
    color: #222;
    font-family: "Biaodian Pro Sans CNS", "Helvetica Neue", Helvetica, Arial, "Zhuyin Heiti", "Han Heiti", sans-serif;
    font-feature-settings: "liga" 1,"locl" 0;
    font-size: 16px;
    -webkit-font-smoothing: subpixel-antialiased;
}
```
***
## [Type is Beautiful](http://www.typeisbeautiful.com/)
[参数化设计与字体战争：从 OpenType 1.8 说起](http://www.typeisbeautiful.com/2016/09/10968/)

```
p {
    font-family: "Classic Grotesque W01", "Avenir Next", "Segoe UI", "Helvetica Neue", Arial, "Hiragino Sans GB", "PingFang SC", "Heiti SC", "Microsoft YaHei UI", "Microsoft YaHei", "Source Han Sans", sans-serif;
    line-height: 1.6;
      vertical-align: baseline;
    -webkit-font-smoothing: antialiased;
}
```
***
## [IPN](https://ipn.li)
[电子书是怎么做出来的](https://ipn.li/itgonglun/195/)

```
p {
    font-size: 18px;
    line-height: 27px;
    font-family: "Metropolis", "Helvetica Neue", helvetica, arial, sans-serif;
    color: #222223;
}
```
***
## [图月志](http://iconmoon.com/blog2/)
[设计师真是一帮表里难如一的人](http://iconmoon.com/blog2/microsoft-surface-studio/)

```
p {
    line-height: 1.8;
    font-weight: 400;
    font-family: Apercu, 'PingFang SC', 'Microsoft YaHei', Arial, SimHei, sans-serif;
    text-rendering: optimizeLegibility;
    -webkit-font-smoothing: antialiased;
    -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
    color: #565c63;
    vertical-align: baseline;
    text-justify: auto;
}
```

***
## license
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
