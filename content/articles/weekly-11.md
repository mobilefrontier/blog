+++
title = "移动开发每周阅读清单：第十一期"
date = "2016-05-09T21:33:45+08:00"
description = "『移动开发每周阅读清单』第十一期与大家见面了，上周App Store又出故障了，让人不得不怀疑苹果工程师的软件质量呢。"
tags = ""
+++

『移动开发每周阅读清单』第十一期与大家见面了，上周App Store又出故障了，让人不得不怀疑苹果工程师的软件质量呢。

## 新闻

[6月1日起iOS应用须支持IPv6](https://developer.apple.com/news/?id=05042016a)

日前苹果发布声明，向应用开发者发出提醒：即将到来的App Store策略要求所有iOS应用必须包含对IPv6-only网络的支持。根据此次苹果在开发者网站的声明，大部分现有应用程序已经通过NSURLSession和CFNetwork APIs兼容该协议。依然使用IPv4 APIs的或者硬件编码IP地址的开发者将需要手工调整应用代码来适应苹果的最新策略。

[App Store出现搜索故障 多款知名应用从搜索结果消失](http://techcrunch.com/2016/05/05/apples-app-store-search-is-completely-broken-right-now/)

上周有人发现在App Store搜索时出现问题，得不到想要的结果，一时之间还有人认为苹果大规模下架应用。后来发现只是苹果调整算法出现故障，有人猜测是因为苹果可能在App Store推出竞价排名，调整算法导致的结果。不过现在搜索结果已恢复正常。

[安卓6.0最新安装率出炉：“大增”2.9%](http://www.ithome.com/html/android/222547.htm)

又来到了月初，意味着又到谷歌更新安卓各版本安装率数据的时候了。在最新的安卓系统安装率数据中，Froyo（2.2）仍然还没消失，Marshmallow（6.0）则增长势头强劲，安卓6.0则是唯一一个安装率上升的版本，增长了2.9%，达到7.5%，虽然增幅很大，但这个增长率仍不及去年这个时候Lollipop的增长率。

## 教程

**iOS**

[关于Swift编译时间优化](https://medium.com/@RobertGummesson/regarding-swift-build-time-optimizations-fc92cdd91e31#.rp2smfllt)

本文介绍了Swift应用编译期的一些性能问题（及绕过方法），顺便介绍了测量编译器性能的一个Xcode插件，如果你在编译Swift应用时遇到了缓慢现象，你应该看看这篇文章并且试试其中的方法。

[准备好迎接Swift 3.0 API变化](http://swift.gg/2016/05/03/preparing-for-3-0-api-pruning/)

Swift 3.0 API 命名方式会大改，作者总结了几条改动规则，帮助你更好地“重新入门 Swift”。

[Swift Style Guide: April 2016 Update Guide](https://www.raywenderlich.com/133102/swift-style-guide-april-2016-update)

Raywenderilich官方的Style Guide更新了，针对Swift2.2的新特性进行了更新。Raywenderilich的这份Swift编码规范比较流行，并且官方一直在保持更新，使用Swift开发的同学可以参照他们的规范制定自己的编码规范。

[别人的App不好用？自己改了便是。Moves篇](http://mp.weixin.qq.com/s?__biz=MzIwMTYzMzcwOQ==&mid=2650948304&idx=1&sn=f76e7b765a7fcabcb71d37052b46e489&scene=0#wechat_redirect)

虾神分享的iOS逆向方面的教程，分为上下两篇。本文以Moves应用威力，修改其应用并重新签名，以达到在不越狱的情况修正Moves中的中国火星坐标。

**Android**

[Android 新一代编译toolchain Jack&Jill 简介](http://taobaofed.org/blog/2016/05/05/new-compiler-for-android/)

在众多的Android N新特性中，有一项新工具链的出现与Android生态圈的所有开发者息息相关，即Jack&Jill编译器的引入。在依赖了Sun/Oracle的Java编译器十年之后，Android 终于有了自己的Java编译器。本文试图对市面上非常有限的资料进行总结，向大家介绍Jack&Jill的缘起，工作方式和原理。

[完美的安卓model层架构](http://blog.piasy.com/2016/05/06/Perfect-Android-Model-Layer/)

无论是MVC、MVP还是MVVM，Model的角色都非常重要，合理的Model设计对整个项目的架构有着至关重要的作用。本文作者提出的Model思想利用OkHttp和Retrofit进行网络请求；使用了SqlDelight、AutoValue及其系列扩展生成model，通过SqlBrite提供数据库访问的reactive API，最终给出了一个完美的Model层。

[Instant Run: How Does it Work（墙）](https://medium.com/google-developers/instant-run-how-does-it-work-294a1633367f#.lmfl31ig1)

Android Studio 2引入了Instant Run功能，降低了开发者（修改→调试）的执行周期。想了解背后是如何实现的吗？简而言之，Instant Run = Incremental build + Hot，Warm，or Cold swap。更多介绍见Reto Meier发在Google Developers上这篇[文章](https://medium.com/google-developers/instant-run-how-does-it-work-294a1633367f#.65tachhhc)和[视频](http://v.youku.com/v_show/id_XMTU2MDI0NTE3Mg==.html?f=26291338)。

## 开源项目

**iOS**

[GRDB.swift](https://github.com/groue/GRDB.swift)

简化SQLite在Swift中使用的工具包。其中一个有趣的特性是GRDB提供协议和一个类用于像操作普通对象一个操作数据库中的列。

[Interpolate](https://github.com/marmelroy/Interpolate)

Interpolate是一个Swift下的插值框架，用于插入手势动画。它的核心思想认为所有动画都是初始值随着时间的变化。



**Android**

[flexbox-layout](https://github.com/google/flexbox-layout)

这是一个来自Google官方的开源项目，支持通过CSS的方式来灵活的进行页面布局。

[Bourbon](https://github.com/hitherejoe/Bourbon)

这是一个MVP架构的开源项目，项目内容来自Dribbble，支持Android Mobile，Tablet，Wear和TV。

[PagerBottomTabStrip](https://github.com/tyzlmjj/PagerBottomTabStrip)

PagerBottomTabStrip 是一个基本谷歌Material Design规范完成的安卓底部导航栏控件。


## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

本周暂无新工作介绍，找工作的同学可以看看前几期的推荐。


## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[GMTC全球移动技术大会](http://gmtc.geekbang.org/?utm_source=zhoubao&utm_medium=xuachuan02&utm_campaign=0509)

6月24-25日北京举办。上周新增千米网移动架构师张西涛，阿里聚划算高级技术专家朴诚（马召），淘宝无线技术专家、Weex核心开发宁栗（凝砺）。本周为8折促销期间，5人以上团购更多优惠，欢迎购票参加。

[Google I/O Extended](http://mp.weixin.qq.com/s?__biz=MzAwODY4OTk2Mg==&mid=2652038418&idx=1&sn=0ef846d70dcaf8cc65ed9f0479aa51fd&scene=4#wechat_redirect)

5月18日晚上10点在全国23城市举行。Google IO将于下周举行，而这个是由Google官方支持，由全国各地的GDG组织的活动，一起观看Google I/O的直播。感兴趣的可以报名，和朋友们一起High。

----

上周移动开发前线公众号精彩文章：

* [从视觉到App：网易有钱iOS项目切图与适配实践](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112179&idx=1&sn=4c7cb33b756b343b93de8b7ccb38b486#rd)
* [糯米移动组件架构演进之路](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112195&idx=1&sn=27fa638e90b09a107057e4a5e8d01ab1#rd)
* [群分享：网易NeteaseAPM iOS SDK技术实现分享](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112215&idx=1&sn=9cc5b5fa630542a6d4b7a5626e35217a#rd)

阅读更多移动开发好文，欢迎关注『移动开发前线』公众号。
