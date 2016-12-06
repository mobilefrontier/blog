+++
title = "移动开发每周阅读清单：第十三期"
date = "2016-05-23T21:33:45+08:00"
description = "『移动开发每周阅读清单』第十三期与大家见面了，上周的Google IO不知道大家看了直播吗，是否感到兴奋呢？对于我来说，感觉没什么眼前一亮的东西呢。"
tags = ""
+++

『移动开发每周阅读清单』第十三期与大家见面了，上周的Google IO不知道大家看了直播吗，是否感到兴奋呢？对于我来说，感觉没什么眼前一亮的东西呢。

## 新闻

[Swift ABI 的稳定时间将被推迟](http://ericasadun.com/2016/05/16/winding-down-swift-3-0-abi-stability-deferred/)

在之前 Swift 3.0 的路线图中，新版本的 Swift 预计可以达到 ABI (应用二进制接口) 稳定，这将意味着旧版本的 Swift 二进制程序将可以运行在新的环境中。但是，最近 Swift 项目的创始人和负责人 Chris Lattner 在[邮件](http://thread.gmane.org/gmane.comp.lang.swift.evolution/17276)中暗示可能这个目标在 Swift 3.0 中将无法达成。通用的 ABI 和其稳定性将被移到之后的版本中实现。

[Google I/O 最全记录](http://www.ifanr.com/658538)

美国当地时间5 月18日上午，Google I/O 2016 正式拉开帷幕，超过7000名来自全球的开发者聚集美国加州谷歌总部附近的 Shoreline Amphitheatre露天剧场参加大会。与此同时，世界各地几百万观众通过现场的直播观看了I/O大会。

[Android O曝光，Android 8.0?](http://news.mydrivers.com/1/483/483462.htm)

Android N（Android 7.0）刚刚放出Beta版，今年8月、9月正式版就将与广大用户见面。网上传出的一张Moto G4新机宣传图显示，“Android O”首次出现，内容是Moto承诺G4可以升级到Android N和Android O。从字母排序和命名习惯来说，Android O应该就是Android 8.0了。

## 教程

**iOS**

[What I’m Doing With These Articles](http://inessential.com/2016/05/18/what_im_doing_with_these_articles)

文章的作者 Simmons 是 Omni 公司的自身 Objective-C 开发者，对 Swift 也非常有研究。Simmons 在他之前一系列博客文章中讨论了 Swift 和 Objective-C 在动态特性上的差异，以及不少只有 Objective-C 能解决的问题，这一系列讨论在国外 iOS 开发者社区引起了不小的反响。Simmons 在这篇文章中总结了自己的观点，他认为 Swift 只是未来的一部分，而很多开发者因为没有意识到他们其实是在一系列 Objective-C 动态特性所支撑的平台和框架上进行开发，所以看待问题相对有些局限。如果你打算或者已经从 Objective-C 转到 Swift，阅读 Simmons 的一系列文章会对深刻理解这个问题有所帮助。

[Command Line Programs on OS X Tutorial](https://www.raywenderlich.com/128039/command-line-programs-os-x-tutorial)

一般很多命令行程序都会使用像是 C，Perl 或者 Ruby 这样的语言来编写，以保证能够在各个平台运行。在 Objective-C 时代，因为 Foundation 库和其他的一些限制，很少有人使用这门语言来编写命令行工具。但是 Swift 开源并跨平台后，Foundation 也将使用 Swift 进行包装并可以运行在像是 Linux 这样的平台下，这给了使用 Swift 开发命令行程序的可能性。本文将带领你使用 Swift 创建一个命令行程序，来完成像是解析输入等基本的操作。

[Swift API 设计指南](http://swift.gg/2016/05/18/api-design-guidelines/)

Swift 3.0 引入了非常多的改动，包括函数签名的重新设计等，这带来的另一个副作用是 API 的设计也需要进行更新。如果你已经对迁移到 Swift 3.0 跃跃欲试，那么可以持续关注这篇文章和 Apple 在官方网站上的原文，来紧跟 Swift 在今年的变化。

**Android**

[Google I/O：Android ConstraintLayout 扁平化布局入门](http://www.jianshu.com/p/792d2682c538)

在Google IO大会中不仅仅带来了Android Studio 2.2预览版，同时带给我们一个依赖约束的库——ConstraintLayout，该库类似于iOS中的约束。简单来说，ConstraintLayout是相对布局的升级版本，但是区别与相对布局更加强调约束。何为约束，即控件之间的关系。该库能让你的布局更加扁平化，一般来说一个界面一层就够了；同时借助于AS我们能极其简单的完成界面布局。

[Android从按下开机键到启动发生了什么](http://www.jianshu.com/p/b4aab68c12c0)

作为一个Android开发者，了解整个系统架构是必须的，所以这篇就总结一下Android手机从按下开机键到启动这一过程发生了什么。要了解Android手机启动过程，就需要先了解基于linux系统的电脑从按下电源键的那一刻起，发生了什么，这样类比可以更好的理解Android手机的启动过程。

[掌握Android中的tools命名空间](http://android.jobbole.com/83207/)

你可能注意到了tools命名空间会出现在许多Google提供的样例布局XML文件中。此命名空间在开发阶段很有用而且不会影响用户体验。它包含了帮助我们在Android Studio设计视图中渲染布局的一套方便的属性。有时这些巧妙的属性会节约我们的构建时间，构建相关的UI改变会减少。阅读文章，了解详细的命名空间知识。

[浅析EventBus 3.0实现思想](http://alighters.com/blog/2016/05/22/eventbus3-dot-0-analyze/)

著名的EventBus大家应该都比较熟悉了。本文作者主要针对其的设计思想做了一些记录，作者希望以尽量少的代码来将其主要设计思想说的透彻明白，阅读文章，了解一些EventBus的设计思想。这里是本周另外一篇分析EventBus 3.0源码的文章。

## 开源项目

**iOS**

[SwiftTheme](https://github.com/jiecao-fm/SwiftTheme)

app 中经常会有需要切换主题的需求，而统一管理这些主题的配置和切换其实并不是想象中那么简单的事情。SwiftTheme 是一个专门负责处理这方面需求的框架，你可以通过预先定义像是配色以及图片这样的资源，就可以方便地在各个主题之间进行切换了，十分方便。

[Networking](https://github.com/3lvis/Networking)

一个简单的对 `NSURLSession` 的封装的网络框架，使用这个框架可以非常方便地完成绝大多数一般 app 中的网络部分的请求，它可以让我们用更安全的方式对网络请求进行设置，而不用再去手动处理像是 content type 或者 token 这些细节。另外，这个框架还提供了 stub 和 mock 的能力，让快速搭建原型的同时，可以避免今后对代码的再次更改。

[BATabBarController](https://github.com/antiguab/BATabBarController)

系统原生的 `TabBarView` 有着非常多的限制，为 tab bar 自定义外观一直是一件很难的事情，更别说自定义一些漂亮的交互和动画效果。而这个框架通过完全自定义重写一个 tab view controller，从而灵活地实现了一个非常炫酷的 tab bar view 动画效果。如果有类似需求的时候，不妨参考一下这个框架的组织方式。

[PMAlertController](https://github.com/Codeido/PMAlertController)

`UIAlertView` 或者 `UIAlertController` 的外观自定义也十分困难，不过因为本身它们就是作为简单的用户提示控件而存在的。在我们制作 app 时，在弹框这样重要的与用户进行交互的方式中，还是会尽可能希望与自己的 app 风格一致。PMAlertController 就是一个帮助你用更加方便灵活，可自定义的弹窗控件来替换掉 Apple 原来的部件的框架，你可以方便地为 alert 添加图片，安排按钮，实现动画等。

**Android**

[StickyHeaders](https://github.com/ShamylZakariya/StickyHeaders)

适用于RecyclerView的Adapter和LayoutManager，支持分组、导航栏滑动伸缩效果。

[MPAndroidChart](https://github.com/ArthurHub/Android-Image-Cropper)

这是一款强大的Android图表库，图表样式很丰富，使用方法简单。

[Android即时通讯和sns开源项目汇总](https://github.com/CameloeAnthony/Perfect_IM_SNS)

这是一个整理即时通讯（IM）和社交系统（SNS）优秀开源项目的文档，项目上传github欢迎提交更新。

## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**Android开发工程师 by 造作**

地点北京。负责开发维护电商类应用。要求1年以上Android实际开发经验，基础扎实，关注新技术。薪资面议，转正即拥有期权，扁平化管理，免费午餐、晚餐。简历发送至 ios@zaozuo.com

## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[GMTC全球移动技术大会](http://gmtc.geekbang.org/?utm_source=zhoubao&utm_medium=xuachuan02&utm_campaign=0523)

6月24-25日北京举办。来自BAT、携程、滴滴、微博、和社区的技术专家联袂分享，主题包括应用架构、性能优化、动态化、插件化、Swift、React Native、Weex等，为中高级移动开发工程师献上一场技术盛宴！本周为8折优惠最后一周，5人以上团购更多优惠，欢迎购票参加。

----

上周移动开发前线公众号精彩文章：

* [新浪微博iOS客户端架构与优化之路](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112273&idx=1&sn=893a66a04e541a99b7bc4d7cf227e2f7#rd)
* [Google I/O 2016：Android N携Android Studio 2.2来袭](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112276&idx=1&sn=c4f6c8d356028d58b37da187ae0ff136#rd)
* [ReactMix：基于HTML+JS+CSS写APP的最佳实践](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112282&idx=1&sn=d4b706d5346844c486af902c7b1b7162#rd)
* [React Native痛点解析之性能调优](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112293&idx=1&sn=866971daf7dba22186d2c09d1bac2418#rd)

阅读更多移动开发好文，欢迎关注『移动开发前线』公众号。
