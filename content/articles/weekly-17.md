+++
title = "移动开发每周阅读清单：第十七期"
date = "2016-06-20T21:33:45+08:00"
description = "『移动开发每周阅读清单』第十七期与大家见面了，上周的WWDC大家熬夜看了吗？都有什么吐槽呢？"
tags = ""
+++

『移动开发每周阅读清单』第十七期与大家见面了，上周的WWDC大家熬夜看了吗？都有什么吐槽呢？

## 新闻

[Apple 表示暂时没有开发 Android 版 iMessage 应用的计划](http://www.theverge.com/2016/6/15/11940010/walt-mossberg-apple-wwdc-2016-recap-themes)

在 WWDC 上，新版本 iOS 的一大亮眼功能就是信息应用的全面加强。现在用户可以在信息应用中输入贴纸，使用全屏效特效等，而第三方开发者也能够通过扩展的方式来创建 iMessage app，来强化和提供官方应用所不具备的功能。而对于一款 IM 应用来说，Android 系统的市场份额是不可忽视的。Apple 表示考虑到用户隐私和机器学习等因素，暂时不可能在 Android 平台推出信息应用。也就是说，官方的信息应用可能在今后一段时间内都还是会处于尴尬和边缘的状态。

[ATS 限制将被加强，明年起将不允许未采用 HTTPS 协议的应用随意上架](http://www.ithome.com.tw/news/106574)

App Transport Security (ATS) 是 Apple 在 WWDC 15 时提出的网络安全相关的规定，它限定应用只能通过 HTTPS 的方式访问网络资源，提高了安全性。在本周 WWDC 的网络安全相关 session 中，Apple 表示将收紧限制，从明年起，开发者将不能再随意通过设置来绕开 HTTPS 的限制了。如果你的应用需要访问 HTTP 的未加密网络，需要在审核时提出合理的理由。关于这方面的详细内容，可以参看[这篇文章](https://onevcat.com/2016/06/ios-10-ats/)中的描述。

[重大更新不跳号Android N或延续为6.X](http://news.imobile.com.cn/articles/2016/0620/168836.shtml)

Android开发者lambggy爆料，谷歌在前不久更新了Android Studio版本，随后谷歌又放出了Android N的Beta4版本，此版本的API最后定型，具体来说是Android API 24。但是在谷歌官方的IDE可以看到，该API 24版本号并不是之前传言的7.0，而是6.X。

## 教程

**iOS**

[开发者所需要知道的 iOS 10 SDK 新特性](https://onevcat.com/2016/06/ios-10-sdk/)

一篇对于 iOS 10 中开发者所需要知道的新特性的概述类文章，对 iOS 的发展方向进行了简单的展望。对于不同的开发者来说，WWDC 16 中他们所感兴趣的点可能会有所不同，这篇文章中总结了可能是所有 iOS 开发者在新的 SDK 中都普遍感兴趣的一些方面，如果你没有时间完整地研究所有 session，可以参考这个总结来寻找你的兴趣点。

[UITableview Tip](https://github.com/vedon/iOS-tech/blob/master/UITableViewOpt/UITableView_Opt.md)

`UITableView` 是每个 iOS 开发者都会用到的，也可能是最常用到的组件之一。这篇文章先探索了 `UITableView` 背后的一些工作方式的细节，并在此基础上展开，为我们介绍了一些优化 `UITableView` 时的技巧。通过合理的配置和巧妙的优化，用户界面可以达到非常高效的状态。另外，今年 WWDC 也专门针对 `UITableView` 和 `UICollection` 的优化问题有个 [session](https://developer.apple.com/videos/play/wwdc2016/219/)，想继续深入的读者不妨看看视频，一探究竟。

[Call Directory Extension 初探](http://colin1994.github.io/2016/06/17/Call-Directory-Extension-Study/)

CallKit 是 iOS 10 引入的新框架，它可以用来实现提供 VoIP 的无缝拨打和现实，以及来电显示和拦截等功能。本文带领读者简单探索了使用 CallKit 来创建来电拦截的部分 API，整个使用相对来说比较简单，所以相关 API 也没有很大难度。

[GUI Architectures](http://martinfowler.com/eaaDev/uiArchs.html)

iOS 应用开发中，用户界面的开发以及他它与应用其他部分如何连接和交互一直是最重要的课题之一。这篇文章不仅仅针对 iOS，它针对所有的 GUI 开发，阐述了各种不同架构方法，包括 MVC、MVVM、VIPER 等等，它们背后共通的思想和原理。在了解常见的 GUI 设计模式之后，再阅读本文会有一种醍醐灌顶，拨云见日的感觉，强烈推荐中高级开发者进行阅读。

**Android**

[安卓跨进程点击事件的解决方案](https://mp.weixin.qq.com/s?__biz=MjM5ODY4ODIxOA==&mid=2653199724&idx=1&sn=4162df42fc6b4c9acd3a2d726a2a4939&scene=1)

本文作者在做Android自动化的时候，发现使用instrument自带的Instrumention.sendPointerSync向其他应用程序发送点击事件的时候，没有效果，而且报出错误：
Permission denied,injecting event from pid XXX XXX uid to window XXX owned by uid XXX.
简单翻译过来就是：从一个应用程序向另外一个应用程序发送事件，因为两个程序的uid不一致，导致权限不够。这就涉及到了跨进程通信的知识，阅读文章，了解作者是如何解决该问题的。

[debuggerd源码篇](http://gityuan.com/2016/06/15/android-debuggerd/)

Android系统有监控程序异常退出的机制，这便是本文要讲述得debuggerd守护进程。当发生native crash或者主动调用debuggerd时，会输出进程相关的状态信息到文件或者控制台。针对进程出现的不同的状态，Linux kernel会发送相应的signal给异常进程，捕获signal并对其做相应的处理（通常动作是退出异常进程）。而Android在这机制的前提下，通过拦截这些信号来dump进程信息，方便开发人员调试分析。本文源码角度探索了debuggerd客户端和服务端的工作原理。

[从linux到android，进程的方方面面](http://www.jianshu.com/p/d80d5d0f7dbe)

默认情况下，Android为每个应用程序创建一个单独的进程，所有组件运行在该进程中，这个默认进程的名字通常与该应用程序的包名相同。Android是基于Linux的，那么Android的进程与Linux的有什么特殊的地方？本文为我们做了详细解读。阅读文章，了解更多关于进程的知识。

## 开源项目

**iOS**

[AssistantKit](https://github.com/anatoliyv/AssistantKit)

有时候我们需要判别用户使用的设备种类、系统版本或者屏幕尺寸等信息。我们可以使用 SDK 中相关的方法来进行获取，但是系统 SDK 提供的方法存在很难使用，而且不太安全等问题。AssistantKit 是一个这方面的一站式解决方案，你可以用更加符合先进开发的方式来获取这些信息。

[AppDevKit](https://github.com/yahoo/AppDevKit)

Yahoo 开源了一系列 Objective-C 的辅助工具集合，其中包括了很多常见的 extension，提供了对于 Cache，AutoLayout 以及其他 100 多个方面的简便方法和现有类的加强。

[Cleanse](https://github.com/square/Cleanse)

Square 开源的一个用 Swift 进行依赖注入的框架。如果你熟悉 Android 和 Java 的话，一定不会对 Square 的几个 Java 框架陌生，比如 okhttp，picasso 和 Dagger。而这次 Square 为我们带来的 Cleanse 就是参考了 Dagger 在 Swift 中实现的依赖注入框架。通过依赖注入的手段，我们可以很容易并且安全地改变既存代码的行为。这不仅在大型应用开发中为我们带来更多灵活性，也对为较复杂的代码编写测试提供了便利条件。

**Android**

[Android主流图片缓存工具汇总](http://blog.androidone.io/?p=35)

这是一个关于图片缓存工具的汇总，汇总了目前比较流行的图片缓存框架，开发者可以选择最适合的使用。

[RecyclerViewUndoSwipe](https://github.com/HoneyNeutrons/RecyclerViewUndoSwipe)

这是一个支持手势调整 item位置、滑动删除功能的RecycleView。

[NoHttp](https://github.com/yanzhenjie/NoHttp)

NoHttp支持大文件、多文件上传、文件下载、自动维持Cookie、异步/同步请求，多种Http缓存模式，302/303重定向, 支持代理服务器.



## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

一直都是发招聘信息，本期反其道而行之，向大家推荐两名同学。他们都是移动前线群的志愿者，无偿的在背后默默帮助大家。

林炜富，目前大四学生，找Android开发实习工作，期望城市广州。在校期间担任IT协会会长，开发广师网管助手App。有技术博客，CET4. 简历见[这里](http://lshare.deercv.com/)。

师威振，2年工作经验，找Ruby开发职位，期望城市北京。有实际项目经验，目前在某B2B项目做后端开发。简历见[这里](http://jdshi.deercv.com/)。


## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[GMTC全球移动技术大会](http://gmtc.geekbang.org/?utm_source=zhoubao&utm_medium=xuachuan02&utm_campaign=0620)

6月24-25日北京举办。来自BAT、携程、滴滴、微博、和社区的技术专家联袂分享，主题包括应用架构、性能优化、动态化、插件化、Swift、React Native、Weex等，为中高级移动开发工程师献上一场技术盛宴！在『移动开发前线』公众号回复“大会”可获得购票优惠码。大会售票最后一天！6月21日18:00截止售票。

[百度沙龙64期：百度开放云移动游戏和直播技术解读](http://form.mikecrm.com/lTsM3a)

本期沙龙将邀请百度开放云内部专家，分享移动游戏和直播在发展中对云的需求痛点，以及百度开放云在移动游戏和直播上的技术优势，并就相关实际案例给出具体讲解。

----

上周移动开发前线公众号精彩文章：

* [WWDC 2016 Keynote总结：滴，信仰已充值](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112383&idx=1&sn=81f44d4602c2aa9220aa32091474e2ac#rd)
* [GMTC全球移动技术大会议程出炉，最火移动技术就在这里！](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112387&idx=1&sn=84f988650d8d35ae43894bcb117f7fba#rd)
* [React Native 开发之 IDE 选型和配置](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112392&idx=1&sn=135e29ddde3050d469be98db815c267e#rd)

阅读更多移动开发好文，欢迎关注『移动开发前线』公众号。
