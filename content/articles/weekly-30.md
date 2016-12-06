+++
title = "移动开发每周阅读清单：第三十期"
date = "2016-09-26T21:33:45+08:00"
description = "官方文档《The Swift Programming Language》 中文版更新，已经同步到 Swift 3.0 ，SwiftGG 出品。Android Studio 2.2发布：改进平台支持 速度提升更智能"
tags = ""
+++

## 新闻

[Swift官方文档中文版更新到Swift3.0版本](http://wiki.jikexueyuan.com/project/swift/)

官方文档《The Swift Programming Language》 中文版更新，已经同步到 Swift 3.0 ，SwiftGG 出品。

[Android Studio 2.2发布：改进平台支持 速度提升更智能](http://www.cnbeta.com/articles/540967.htm)

Google刚刚发布了Android Studio 2.2，这款IDE（集成开发环境）旨在帮助开发者们从头打造Android应用。老用户可以直接在软件的设置项中点击更新，新手们则可以到官方下载页查看最新内容。Android产品经理Jamal Eason在开发者博客文章中总结了本次更新的内容，主要集中在速度、智能和Android平台支持三个方面。

## 教程

**iOS**

[适配 Swift 3 的一点小经验和坑](https://imtx.me/archives/2064.html)

本文作者在适配 Swift 3 过程中总结了一些宝贵的经验与心得，诸如 Any vs AnyObject 的改变、protocol 实现代码位置的改变等。

[UIButton 是一个类簇( Class Clusters )？](http://www.nscookies.com/class-clusters/)

类簇是Foundation框架中广泛使用的设计模式。类簇将一些私有的、具体的子类组合在一个公共的、抽象的超类下面，以这种方法来组织类可以简化一个面向对象框架的公开架构，而又不减少功能的丰富性。本文作者讨论了 UIButton 是否为一个类簇，并给出了设计类簇的一些建议。

[Escaping and Nonescaping Closures in Swift 3](https://swiftunboxed.com/lang/closures-escaping-noescape-swift3/)

本文作者分享了什么是逃逸闭包和非逃逸闭包，以及二者的区别。同时介绍了在 Swift 3 中，逃逸闭包和非逃逸闭包的变化。

**Android**

[Android DataBinding 数据绑定](http://mp.weixin.qq.com/s?__biz=MzI1NjEwMTM4OA==&mid=2651232170&idx=1&sn=f4d7eb8f35ebf3b13696562ca3172bac&chksm=f1d9eac9c6ae63df357c3a96aa0218b5d66237c5411de5b34cd24ddb7a1d258b34444966d8c6&scene=0#rd)

2015年的谷歌IO大会上，Android UI Toolkit团队发布了DataBinding 框架，将数据绑定引入了Android开发，当时还只支持单向绑定，而且需要作为第三方依赖引入，时隔一年，双向绑定这个特性也得到了支持，同时纳入了Android Gradle Plugin（1.5.0+）中，只需要在gradle配置文件里添加短短的三行，就能用上数据绑定。

[Android混淆从入门到精通](http://www.jianshu.com/p/7436a1a32891)

作为Android开发者，如果你不想开源你的应用，那么在应用发布前，就需要对代码进行混淆处理，从而让我们代码即使被反编译，也难以阅读。混淆概念虽然容易，但很多初学者也只是网上搜一些成型的混淆规则粘贴进自己项目，并没有对混淆有个深入的理解。本篇文章的目的就是让一个初学者在看完后，能在不进行任何帮助的情况下，独立写出适合自己代码的混淆规则。

[拥抱SVG：苦恼于图片适配 in Android？](http://gold.xitu.io/post/57dfe16379bc440065e85b2b)

SVG是指可伸缩矢量图形 （Scalable Vector Graphics），它不同于传统的位图，不是通过存储图像中每一点的像素值来保存与使用图形，而是通过XML文件来定义一个图形，通过一些特定的语法和规则来绘制出我们所需的图像——同样是使用一张图片，SVG 的方式是事先定义好怎么去画这个图，然后等要用的时候再把它去画出来，而使用传统的位图的话就是已经有了画出来的图，然后要用的时候直接把画好的图拿出来用。


## 开源项目

**iOS**

[ProtocolNetwork](https://github.com/MDCC2016/ProtocolNetwork)

一个优雅的面向协议编程的示例。

[Himotoki](https://github.com/ikesyo/Himotoki)

类型安全的 JSON 解析库，优雅地使用 throws 的方式处理 JSON 。

[xTextHandler](https://github.com/cyanzhong/xTextHandler)

基于 Xcode Source Editor Extension 的插件集，提高 Xcode 8 的文本处理的体验。

[Dwifft](https://github.com/jflinter/Dwifft)

Swift diff 框架，可以非常方便遍历出两次数据的不同，可以用在 UITableView 插入、删除操作。


**Android**

[tinker](https://github.com/Tencent/tinker)

这是Github上腾讯开源的第一个项目。tinker是微信的热修复解决方案，支持dex、library、resources的动态更新。

[SuperPlayer](https://github.com/supercwn/SuperPlayer)

SuperPlayer 是一个基于IjkPlayer的控制器，支持手势操作，滑动快进，快退，支持，上滑音量亮度的变化，支持指点位置播放，播放源的切换

[BookReader](https://github.com/JustWayward/BookReader)

“任阅”，开源小说阅读器，高仿追书神器，实现追书推荐、标签检索、翻书效果、文章阅读、缓存章节、日夜间模式、文本朗读等功能。



## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

本期暂无工作推推荐。移动前线群里有个同学求职，我把他的信息发在这里，要者自取。

**求职：Android开发工程师（实习）**

期望地点北京。北京化工大学，本科打死在读。有只能台灯项目经历。简历见： https://chaoren998.github.io/aboutme.html



## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

----
