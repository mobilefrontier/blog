+++
date = "2017-02-23T21:07:47+08:00"
title = "移动开发每周阅读清单：第四十五期"
description = "苹果宣布，今年的苹果全球开发者大会（简称WWDC）将于6月5日正式在加州圣何塞举行，会期5天，大会上将讨论新的操作系统和新的开发组件问题。"
+++


## 新闻

[WWDC17 时间公布](https://developer.apple.com/wwdc/)

苹果宣布，今年的苹果全球开发者大会（简称WWDC）将于6月5日正式在加州圣何塞举行，会期5天，大会上将讨论新的操作系统和新的开发组件问题。

[谷歌高管暗示Android 8.0或命名奥利奥，5月17日发布](http://news.zol.com.cn/628/6280272.html)

2月21号消息，之前就有消息称在今年的谷歌I/O开发者大会上，Android 8.0将作为焦点亮相。随着大会的临近，Android8.0更多信息遭到曝光。昨日，Android业务副总裁Hiroshi Lockheimer在推特晒出带有奥利奥蛋糕的图片，似乎暗示Android 8.0将要命名为“奥利奥”。

## 教程

**iOS**

[Pushing the Boundaries of Swift to the Server](https://realm.io/news/altconf-karl-weinmeister-pushing-boundaries-swift-server/)

作者 Karl 在 AltConf 演讲中分享了使用 IBM Cloud 用 Swift 写服务器端代码时多么轻松，作者通过完成一个 Slack 机器人展示了 IBM Swift Sandbox 的强大。

[Acceptance Testing](https://realm.io/news/acceptance-testing/)

本文介绍了不同于单元测试的验收测试，以及对应的测试方法和隐藏的陷阱。

[iOS 逆向实战 - 钉钉签到远程“打卡”](http://www.jianshu.com/p/69ce01e15042)

本文通过逆向分析的过程，实现了钉钉远程打卡功能，你可以从中学习其分析的过程。

[iOS 无埋点数据 SDK 实践之路](http://www.jianshu.com/p/69ce01e15042)

作者开发无埋点数据收集 SDK 已有半年，本文中作者分享了实践的收获。包括不需要代码埋点就能自动的、动态可配的、全面且正确的收集用户在使用 App 时的所有事件数据。

[我是如何把 Klib 带到这个世界的](https://atjason.com/daily/2017-02-21.html)

作者开发了 Klib macOS App ，在本文中介绍了从缘由到设计再到开发和测试，以及推广等过程，你可以了解到一名个人开发者的真实写照。

**Android**

[理解Android Binder机制(2/3)：C++层](http://qiangbo.space/2017-02-12/AndroidAnatomy_Binder_CPP/)

Binder的实现是比较复杂的，想要完全弄明白是怎么一回事，并不是一件容易的事情。这里面牵涉到好几个层次，每一层都有一些模块和机制需要理解。这部分内容作者预计会分为三篇文章来讲解。第一篇对整个Binder机制做了一个架构性的讲解，本文是第二篇，讲解了Binder Framework C++部分的逻辑。

[Android触摸事件分发那些事](http://www.jianshu.com/p/5a2d56167259)

在Android开发中，经常需要自定义View。自定义View大概可以分为两个步骤：绘制外观和处理触摸事件。处理触摸事件需要知道触摸事件的分发流程，本文将带着大家详细地了解触摸事件分发流程，以及在触摸事件分发流程中扮演重要角色的方法如：dispatchTouchEvent、onInterceptTouchEvent、onTouchEvent的详细讲解。

[Android动态加载简单易懂的介绍方式](http://kaedea.com/2016/02/06/android-dynamical-loading-01-introduction/)

使用动态加载技术，可以达到让用户不用重新安装APK就能升级应用的功能（特别是SDK项目），这样一来不但可以大大提高应用新版本的覆盖率，也减少了服务器对旧版本接口兼容的压力，同时也可以快速修复一些线上的BUG。本文从动态加载的定义、类型、类加载器ClassLoader和dex文件、代理Activity模式等多方面详细介绍了动态加载的知识，作者对动态加载理解的很透彻，推荐阅读。

[从json文件到炫酷动画-Lottie实现思路和源码分析](http://www.jianshu.com/p/81be1bf9600c)

Lottie是最近Airbnb开源的动画项目，支持Android、iOS、ReactNaitve三个平台，相关背景介绍可以参考这篇文章[Airbnb开源炫酷动画库Lottie（译）－看看Airbnb的工程师怎么说](http://www.jianshu.com/p/d887c96684be)。本文主要分析了Lottie是如何把json文件转为动画的思路和源码实现。文章首先介绍了Android版本Lottie的基本使用，然后分析把json文件映射到动画的实现思路，最后分析Lottie的源码实现.


## 开源项目

**iOS**

[folding-cell](https://github.com/Ramotion/folding-cell)

参考 folding paper material 折叠效果的 UI 组件。

[Dotzu](https://github.com/remirobert/Dotzu)

iOS Debug 工具，支持 log 等级、网络请求、崩溃信息记录。

[FSPagerView](https://github.com/WenchaoD/FSPagerView)

支持非常丰富设置项的 Pager View 。

[ESTabBarController](https://github.com/eggswift/ESTabBarController)：可高度自定义的 TabBarController 组件。


**Android**

[Cockroach](https://github.com/android-notes/Cockroach)

Android中虽然可以通过设置Thread.setDefaultUncaughtExceptionHandler来捕获所有线程的异常，但主线程抛出异常时仍旧会导致Activity闪退，App进程重启。使用Cockroach后就可以保证不管怎样抛异常Activity都不会闪退，App进程也不会重启。

[routerSDK](https://github.com/Jomes/routerSDK)

这是一款小而美的路由框架。使用routerSDK，可以通过网页动态添加自定义参数启动应用，当然也可以实现通过url的方式在App内进行页面跳转。对于我们进行模块化或组件化开发很有参考价值。

[Zoomy](https://github.com/imablanco/Zoomy)

这是一款支持列表中图片拖拽、手势放大的开源库。

[Alerter](https://github.com/imablanco/Zoomy)

一款非常漂亮的自定义Alert View，从顶部弹出，位于所有视图的上层。

## 工作

> 有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**iOS/Android高级开发工程师 by 爱奇艺**

上海徐汇 / 三年以上工作经验 / 工作稳定踏实 / 可给出业内有竞争力的薪资。简历发送至 jinkai@qiyi.com

**中高级Android/iOS开发工程师 by 小红书**

坐标上海。负责参加小红书主App开发。要求三年以上相关经验，有App优化实践经验，有一定框架和架构开发经验。简历至：fzhang@xiaohongshu.com

**iOS/Android/前端高级工程师 by 新美大平台部门大前端**

坐标北京。维护美团App平台架构/业务，以及移动端和前端基础设施。高级工程师要求有一定的技术规划选型能力。薪资与BAT对标。简历发送至 luozexiang@meituan.com

## 活动


> 宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[GMTC 2017全球移动技术大会](http://gmtc.geekbang.org/?utm_source=infoq&utm_campaign=bornmobile&utm_medium=wechat)

6月9日北京举行。关注移动、前端、跨平台、AI应用等多个技术领域、促进全球技术交流，推动国内技术升级。GMTC为期两天，面向移动开发、前端、AI技术人员，聚焦前沿技术及实践经验，打造技术人员的学习和交流平台。

[QCon北京站2017](http://2017.qconbeijing.com/)

2017年4月16日北京举行。明年第一场最值得期待的综合性技术大会。QCon内容源于实践并面向社区，演讲嘉宾依据热点话题，面向5年以上工作经验的技术团队负责人、架构师、工程总监、高级开发人员分享技术创新和最佳实践。