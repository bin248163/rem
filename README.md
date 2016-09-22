# rem
如今市面上移动设备的分辨率各种各样，网页设计中常用的单位px在移动端布局中显得力不从心，css3的出现了一个带来了一个新的css单位——rem，rem是解决移动端分辨率适配问题比较完美的方案。

rem（font size of the root element）是指相对于根元素的字体大小的单位。简单的说它就是一个相对单位。看到rem大家 一定会想起em单位，em（font size of the element）是指相对于父元素的字体大小的单位。它们之间其实很相似，只不过一个计算 的规则是依赖根元素一个是依赖父元素计算。

rem于em其实有点类似，不同的是rem是相对于根元素的字体大小的单位，em指相对于父元素的字体大小的单位。
rem的使用
rem相对于根元素<html>的font-size来做计算,举个例子：
设置根元素<html>的font-size：14px，div宽高为10rem，则得到一个宽高各为140px的div。
需注意的是使用rem布局需在页面头部定义mate标签禁止页面缩放。
