# frontend-interview

Based on [these questions](https://github。com/h5bp/Front-end-Developer-Interview-Questions) and the [translation](http://segmentfault。com/a/1190000003060827)。

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github。com/thlorenz/doctoc)*

- [通用问题](#%E9%80%9A%E7%94%A8%E9%97%AE%E9%A2%98)
  - [你昨天/这周都有学什么](#%E4%BD%A0%E6%98%A8%E5%A4%A9%E8%BF%99%E5%91%A8%E9%83%BD%E6%9C%89%E5%AD%A6%E4%BB%80%E4%B9%88)
  - [是什么激发让你对写代码感兴趣(你喜欢写代码的动力是什么)](#%E6%98%AF%E4%BB%80%E4%B9%88%E6%BF%80%E5%8F%91%E8%AE%A9%E4%BD%A0%E5%AF%B9%E5%86%99%E4%BB%A3%E7%A0%81%E6%84%9F%E5%85%B4%E8%B6%A3%E4%BD%A0%E5%96%9C%E6%AC%A2%E5%86%99%E4%BB%A3%E7%A0%81%E7%9A%84%E5%8A%A8%E5%8A%9B%E6%98%AF%E4%BB%80%E4%B9%88)
  - [列举一项你最近(在项目)中碰到的挑战, 你是如何解决的](#%E5%88%97%E4%B8%BE%E4%B8%80%E9%A1%B9%E4%BD%A0%E6%9C%80%E8%BF%91%E5%9C%A8%E9%A1%B9%E7%9B%AE%E4%B8%AD%E7%A2%B0%E5%88%B0%E7%9A%84%E6%8C%91%E6%88%98-%E4%BD%A0%E6%98%AF%E5%A6%82%E4%BD%95%E8%A7%A3%E5%86%B3%E7%9A%84)
  - [当你在建一个web应用程序或者网站时候, 你会考虑哪些方面(UI, 安全, 性能, SEO, 可维护性还是技术等)](#%E5%BD%93%E4%BD%A0%E5%9C%A8%E5%BB%BA%E4%B8%80%E4%B8%AAweb%E5%BA%94%E7%94%A8%E7%A8%8B%E5%BA%8F%E6%88%96%E8%80%85%E7%BD%91%E7%AB%99%E6%97%B6%E5%80%99-%E4%BD%A0%E4%BC%9A%E8%80%83%E8%99%91%E5%93%AA%E4%BA%9B%E6%96%B9%E9%9D%A2ui-%E5%AE%89%E5%85%A8-%E6%80%A7%E8%83%BD-seo-%E5%8F%AF%E7%BB%B4%E6%8A%A4%E6%80%A7%E8%BF%98%E6%98%AF%E6%8A%80%E6%9C%AF%E7%AD%89)
  - [说说你所喜欢的开发环境(OS, IDE。。。)](#%E8%AF%B4%E8%AF%B4%E4%BD%A0%E6%89%80%E5%96%9C%E6%AC%A2%E7%9A%84%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83os-ide%E3%80%82%E3%80%82%E3%80%82)
  - [如果你有五个不同的样式表, 你怎么样最好地整合应用到一个页面上去呢](#%E5%A6%82%E6%9E%9C%E4%BD%A0%E6%9C%89%E4%BA%94%E4%B8%AA%E4%B8%8D%E5%90%8C%E7%9A%84%E6%A0%B7%E5%BC%8F%E8%A1%A8-%E4%BD%A0%E6%80%8E%E4%B9%88%E6%A0%B7%E6%9C%80%E5%A5%BD%E5%9C%B0%E6%95%B4%E5%90%88%E5%BA%94%E7%94%A8%E5%88%B0%E4%B8%80%E4%B8%AA%E9%A1%B5%E9%9D%A2%E4%B8%8A%E5%8E%BB%E5%91%A2)
  - [你能描述下渐进增强和优雅降级的区别么](#%E4%BD%A0%E8%83%BD%E6%8F%8F%E8%BF%B0%E4%B8%8B%E6%B8%90%E8%BF%9B%E5%A2%9E%E5%BC%BA%E5%92%8C%E4%BC%98%E9%9B%85%E9%99%8D%E7%BA%A7%E7%9A%84%E5%8C%BA%E5%88%AB%E4%B9%88)
  - [怎么对一个站点（页面）资源进行优化处理](#%E6%80%8E%E4%B9%88%E5%AF%B9%E4%B8%80%E4%B8%AA%E7%AB%99%E7%82%B9%EF%BC%88%E9%A1%B5%E9%9D%A2%EF%BC%89%E8%B5%84%E6%BA%90%E8%BF%9B%E8%A1%8C%E4%BC%98%E5%8C%96%E5%A4%84%E7%90%86)
  - [浏览器从同一个站点一次能下载多少资源（例外情况） （不清楚TODO）](#%E6%B5%8F%E8%A7%88%E5%99%A8%E4%BB%8E%E5%90%8C%E4%B8%80%E4%B8%AA%E7%AB%99%E7%82%B9%E4%B8%80%E6%AC%A1%E8%83%BD%E4%B8%8B%E8%BD%BD%E5%A4%9A%E5%B0%91%E8%B5%84%E6%BA%90%EF%BC%88%E4%BE%8B%E5%A4%96%E6%83%85%E5%86%B5%EF%BC%89-%EF%BC%88%E4%B8%8D%E6%B8%85%E6%A5%9Atodo%EF%BC%89)
  - [说出三条方法去减少页面加载时间(感知到的或者真是的加载时间)](#%E8%AF%B4%E5%87%BA%E4%B8%89%E6%9D%A1%E6%96%B9%E6%B3%95%E5%8E%BB%E5%87%8F%E5%B0%91%E9%A1%B5%E9%9D%A2%E5%8A%A0%E8%BD%BD%E6%97%B6%E9%97%B4%E6%84%9F%E7%9F%A5%E5%88%B0%E7%9A%84%E6%88%96%E8%80%85%E7%9C%9F%E6%98%AF%E7%9A%84%E5%8A%A0%E8%BD%BD%E6%97%B6%E9%97%B4)
  - [如果你在一个项目中别人都使用tabs而你使用space, 你会怎么做](#%E5%A6%82%E6%9E%9C%E4%BD%A0%E5%9C%A8%E4%B8%80%E4%B8%AA%E9%A1%B9%E7%9B%AE%E4%B8%AD%E5%88%AB%E4%BA%BA%E9%83%BD%E4%BD%BF%E7%94%A8tabs%E8%80%8C%E4%BD%A0%E4%BD%BF%E7%94%A8space-%E4%BD%A0%E4%BC%9A%E6%80%8E%E4%B9%88%E5%81%9A)
  - [描述下你怎么创建一个简单的幻灯片播放页面](#%E6%8F%8F%E8%BF%B0%E4%B8%8B%E4%BD%A0%E6%80%8E%E4%B9%88%E5%88%9B%E5%BB%BA%E4%B8%80%E4%B8%AA%E7%AE%80%E5%8D%95%E7%9A%84%E5%B9%BB%E7%81%AF%E7%89%87%E6%92%AD%E6%94%BE%E9%A1%B5%E9%9D%A2)
  - [如果你今年能学习掌握一门技术(语言), 你觉得会是什么呢](#%E5%A6%82%E6%9E%9C%E4%BD%A0%E4%BB%8A%E5%B9%B4%E8%83%BD%E5%AD%A6%E4%B9%A0%E6%8E%8C%E6%8F%A1%E4%B8%80%E9%97%A8%E6%8A%80%E6%9C%AF%E8%AF%AD%E8%A8%80-%E4%BD%A0%E8%A7%89%E5%BE%97%E4%BC%9A%E6%98%AF%E4%BB%80%E4%B9%88%E5%91%A2)
  - [解释标准和标准机构的重要性](#%E8%A7%A3%E9%87%8A%E6%A0%87%E5%87%86%E5%92%8C%E6%A0%87%E5%87%86%E6%9C%BA%E6%9E%84%E7%9A%84%E9%87%8D%E8%A6%81%E6%80%A7)
  - [什么是文档样式闪烁(Flash of Unstyled Content), 如何避免](#%E4%BB%80%E4%B9%88%E6%98%AF%E6%96%87%E6%A1%A3%E6%A0%B7%E5%BC%8F%E9%97%AA%E7%83%81flash-of-unstyled-content-%E5%A6%82%E4%BD%95%E9%81%BF%E5%85%8D)
  - [解释ARIA和screenreaders, 怎么让一个网站可理解](#%E8%A7%A3%E9%87%8Aaria%E5%92%8Cscreenreaders-%E6%80%8E%E4%B9%88%E8%AE%A9%E4%B8%80%E4%B8%AA%E7%BD%91%E7%AB%99%E5%8F%AF%E7%90%86%E8%A7%A3)
  - [说下相比于JavaScript动画实现, CSS的动画实现有什么优点和缺点](#%E8%AF%B4%E4%B8%8B%E7%9B%B8%E6%AF%94%E4%BA%8Ejavascript%E5%8A%A8%E7%94%BB%E5%AE%9E%E7%8E%B0-css%E7%9A%84%E5%8A%A8%E7%94%BB%E5%AE%9E%E7%8E%B0%E6%9C%89%E4%BB%80%E4%B9%88%E4%BC%98%E7%82%B9%E5%92%8C%E7%BC%BA%E7%82%B9)
  - [CORS是什么它解决什么问题](#cors%E6%98%AF%E4%BB%80%E4%B9%88%E5%AE%83%E8%A7%A3%E5%86%B3%E4%BB%80%E4%B9%88%E9%97%AE%E9%A2%98)
- [HTML 问题](#html-%E9%97%AE%E9%A2%98)
  - [doctype 的作用](#doctype-%E7%9A%84%E4%BD%9C%E7%94%A8)
  - [标准模式和兼容(混杂)模式的差异](#%E6%A0%87%E5%87%86%E6%A8%A1%E5%BC%8F%E5%92%8C%E5%85%BC%E5%AE%B9%E6%B7%B7%E6%9D%82%E6%A8%A1%E5%BC%8F%E7%9A%84%E5%B7%AE%E5%BC%82)
  - [HTML 和 XHTML 的差异](#html-%E5%92%8C-xhtml-%E7%9A%84%E5%B7%AE%E5%BC%82)
  - [像 application/xhtml+xml 这样的服务页面会有什么问题么](#%E5%83%8F-applicationxhtmlxml-%E8%BF%99%E6%A0%B7%E7%9A%84%E6%9C%8D%E5%8A%A1%E9%A1%B5%E9%9D%A2%E4%BC%9A%E6%9C%89%E4%BB%80%E4%B9%88%E9%97%AE%E9%A2%98%E4%B9%88)
  - [你怎么实现一个页面的多种语言(切换)](#%E4%BD%A0%E6%80%8E%E4%B9%88%E5%AE%9E%E7%8E%B0%E4%B8%80%E4%B8%AA%E9%A1%B5%E9%9D%A2%E7%9A%84%E5%A4%9A%E7%A7%8D%E8%AF%AD%E8%A8%80%E5%88%87%E6%8D%A2)
  - [哪些方面的东西是你在设计和开发多语言网站时必须要小心谨慎考虑到的](#%E5%93%AA%E4%BA%9B%E6%96%B9%E9%9D%A2%E7%9A%84%E4%B8%9C%E8%A5%BF%E6%98%AF%E4%BD%A0%E5%9C%A8%E8%AE%BE%E8%AE%A1%E5%92%8C%E5%BC%80%E5%8F%91%E5%A4%9A%E8%AF%AD%E8%A8%80%E7%BD%91%E7%AB%99%E6%97%B6%E5%BF%85%E9%A1%BB%E8%A6%81%E5%B0%8F%E5%BF%83%E8%B0%A8%E6%85%8E%E8%80%83%E8%99%91%E5%88%B0%E7%9A%84)
  - [哪些data-的属性是有效的](#%E5%93%AA%E4%BA%9Bdata-%E7%9A%84%E5%B1%9E%E6%80%A7%E6%98%AF%E6%9C%89%E6%95%88%E7%9A%84)
  - [HTML5作为一个开放的 Web 平台，HTML5的构建块是什么](#html5%E4%BD%9C%E4%B8%BA%E4%B8%80%E4%B8%AA%E5%BC%80%E6%94%BE%E7%9A%84-web-%E5%B9%B3%E5%8F%B0%EF%BC%8Chtml5%E7%9A%84%E6%9E%84%E5%BB%BA%E5%9D%97%E6%98%AF%E4%BB%80%E4%B9%88)
  - [描述下 `cookie` `sessionStorage` `localStorage` 的区别](#%E6%8F%8F%E8%BF%B0%E4%B8%8B-cookie-sessionstorage-localstorage-%E7%9A%84%E5%8C%BA%E5%88%AB)
  - [描述下 `<script>` `<script async>` `<script defer>`的区别](#%E6%8F%8F%E8%BF%B0%E4%B8%8B-script-script-async-script-defer%E7%9A%84%E5%8C%BA%E5%88%AB)
  - [为什么一般总是把 CSS link 放置于<head></head>，而把script放在</body>前? 有什么例外么](#%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%80%E8%88%AC%E6%80%BB%E6%98%AF%E6%8A%8A-css-link-%E6%94%BE%E7%BD%AE%E4%BA%8Eheadhead%EF%BC%8C%E8%80%8C%E6%8A%8Ascript%E6%94%BE%E5%9C%A8body%E5%89%8D-%E6%9C%89%E4%BB%80%E4%B9%88%E4%BE%8B%E5%A4%96%E4%B9%88)
  - [什么是渐进渲染](#%E4%BB%80%E4%B9%88%E6%98%AF%E6%B8%90%E8%BF%9B%E6%B8%B2%E6%9F%93)
  - [你之前使用过什么不同的 HTML 模板语言么](#%E4%BD%A0%E4%B9%8B%E5%89%8D%E4%BD%BF%E7%94%A8%E8%BF%87%E4%BB%80%E4%B9%88%E4%B8%8D%E5%90%8C%E7%9A%84-html-%E6%A8%A1%E6%9D%BF%E8%AF%AD%E8%A8%80%E4%B9%88)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## 通用问题 

### 你昨天/这周都有学什么

(2015/08/07) 最近在学习了如何在 Server 端使用 ReactJS

### 是什么激发让你对写代码感兴趣(你喜欢写代码的动力是什么)

兴趣使然。

### 列举一项你最近(在项目)中碰到的挑战, 你是如何解决的

我正则不行, 我 Google

### 当你在建一个web应用程序或者网站时候, 你会考虑哪些方面(UI, 安全, 性能, SEO, 可维护性还是技术等)

安全性能方面不是前期能考虑的问题, 不过会适当注意。主要还是考虑选择合适的技术和 UI 方面的问题。

### 说说你所喜欢的开发环境(OS, IDE。。。)

能在 OSX/Windows 下开发, 不过还是觉得 OSX 下效率更高, 体现在一些细节上。不喜欢用 IDE, 用好了编辑器效率同样很高, 有些更适用 IDE 的项目除外, 前端的话暂时没这方面顾虑。

### 如果你有五个不同的样式表, 你怎么样最好地整合应用到一个页面上去呢

Concat 到一起, 再压缩。或者完全用 Sass 之类的重写。

### 你能描述下渐进增强和优雅降级的区别么

这是什么

### 怎么对一个站点（页面）资源进行优化处理

减少 HTTP 请求。压缩。使用 CDN。

### 浏览器从同一个站点一次能下载多少资源（例外情况） （不清楚TODO）

不知道。

### 说出三条方法去减少页面加载时间(感知到的或者真是的加载时间)

这和 “怎么对一个站点（页面）资源进行优化处理” 这个问题差不多吧

### 如果你在一个项目中别人都使用tabs而你使用space, 你会怎么做

叫他们转为 space。

### 描述下你怎么创建一个简单的幻灯片播放页面

Click -> Slide

### 如果你今年能学习掌握一门技术(语言), 你觉得会是什么呢

React + React Native

### 解释标准和标准机构的重要性

统一代码规范。

### 什么是文档样式闪烁(Flash of Unstyled Content), 如何避免

不清楚, 没遇到过, Google 了一下估计也不会遇到。

### 解释ARIA和screenreaders, 怎么让一个网站可理解

不清楚。

### 说下相比于JavaScript动画实现, CSS的动画实现有什么优点和缺点

性能更好（maybe yes? maybe no?）而且代码逻辑相对简单, 不过浏览器兼容性。

### CORS是什么它解决什么问题

跨域资源共享。解决了跨域请求的安全问题。

## HTML 问题

### doctype 的作用

告诉浏览器当前使用的 HTML 版本，避免浏览器出现怪异的渲染效果。

### 标准模式和兼容(混杂)模式的差异

当然是越标准 IE 的行为就会越接近标准规范

### HTML 和 XHTML 的差异

XHTML 是较规范的 HTML, 比如大小写有区别

### 像 application/xhtml+xml 这样的服务页面会有什么问题么

不知道诶

### 你怎么实现一个页面的多种语言(切换)

各个语言包，前端切换

### 哪些方面的东西是你在设计和开发多语言网站时必须要小心谨慎考虑到的

没有吧

### 哪些data-的属性是有效的

难道不是随便叫什么?

### HTML5作为一个开放的 Web 平台，HTML5的构建块是什么

我也想问什么是“构建块”

### 描述下 `cookie` `sessionStorage` `localStorage` 的区别

老生常谈了都

### 描述下 `<script>` `<script async>` `<script defer>`的区别

想死的心都有了

### 为什么一般总是把 CSS link 放置于 `<head></head>`，而把script放在 `</body>` 前? 有什么例外么

你猜

### 什么是渐进渲染

我不知道

### 你之前使用过什么不同的 HTML 模板语言么

什么是 HTML 模板语言？
