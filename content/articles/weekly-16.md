+++
title = "移动开发每周阅读清单：第十六期"
date = "2016-06-13T21:33:45+08:00"
description = "『移动开发每周阅读清单』第十六期与大家见面了，今晚就是WWDC了，我们准备了在线微信群和大咖说陪你看直播，详情见活动栏目。"
tags = ""
+++

『移动开发每周阅读清单』第十六期与大家见面了，今晚就是WWDC了，我们准备了在线微信群和大咖说陪你看直播，详情见活动栏目。

## 新闻

[App Store 2.0，Apple 可能修改 app 付费模式和分成方式](http://www.theverge.com/2016/6/8/11880730/apple-app-store-subscription-update-phil-schiller-interview)

国外科技媒体在对 App Store 负责人 Phil Schiller 的一次采访中，后者表示最近可能会对 App Store 的现行机制进行大幅改革。除了之前已经得到确认的为搜索结果加入一个付费推广 app 的展示外，新的 App Store 可能会推出新的订阅制付费模式。普通的 app 也将可以使用订阅模式，持续地向用户收取费用并提供更新。另外，Phil 还表示可能会考虑降低 Apple 对于订阅模式第二年开始的付费分成，将传统的 30％ 的收费分成降低到 15％。

[Google 发布 TensorFlow iOS 版本](https://github.com/tensorflow/tensorflow/releases/tag/v0.9.0rc0)

如果你对前不久 Google AlphaGo 五番棋大败李世石的事件有过关注的话，可能会知道背后支持 AlphaGo 的人工智能和机器学习的软件就是 TensorFlow。TensorFlow 在去年 11 月就已经开源，科学计算和人工智能的相关从业及研究人员已经可以使用它来完成工作。而本周 Google 发布了一个 TensorFlow 的新版本，其中包含了对 iOS 系统的支持以及一个在 iOS 上进行机器学习的例子。这意味着开发者有可能很容易地在 iOS 应用中加入一些轻量级的机器学习内容，来让 app 更加智能和符合用户习惯。当然，这只是最初步的使用场景，也许开发者们还能挖掘出移动 app 和人工智能更好的结合点，并以此掀起一场 app 的革命。

[Android推出新功能：根据位置推荐应用](http://news.zol.com.cn/587/5878301.html)

据外媒报道，谷歌将在新版Android系统中推出名为“Nearby”的功能。Android手机用户能够了解他们所在的位置最有用的应用程序。这也是谷歌的Android个性化手机的最新举措。

[安卓6.0仍存内存泄露问题，谷歌承诺“新版本”解决](http://www.ithome.com/html/android/232518.htm)

目前仍有不少网友反映安卓6.0 Marshmallow系统中依然存在内存泄露问题，目前谷歌已经注意到了该问题，并承诺在“新版本（future release）”中解决，这里的“新版本”应该不会是安卓7.0，而是月度补丁。

## 教程

**iOS**

[Swift 化的视图控制器展示](https://realm.io/cn/news/slug-jesse-squires-swifty-view-controller-presenters/)

一篇来自 Realm 的翻译文章，View Controller 在 iOS 开发中的职责非常重要，而 app 制作开发时最常见的错误莫过于赋予 View Controller 太多的功能，而使其臃肿不堪，无法维护了。这篇文章为我们介绍了使用 Swift 化的 API 来重新审视和定义视图控制器的常见操作，并以此为基础，对视图控制器的实现方式进行了简化。

[Mac 应用开发基础教程](http://www.macdev.io)

随着 iOS 的成功，Mac 设备在国内的占有率也在逐渐上升。因为使用的语言和思维方式类似，所以不少 iOS 开发者也对 Mac 开发产生了兴趣。但是和 UIKit 不同，Mac 开发的 AppKit 相对历史包袱要多一些，使用起来也和 iOS 开发有不少区别。这本书对 Mac 开发的组件使用和开发方式进行了一些说明，让读者可以理解 Mac 平台开发的基础知识。如果你对 Mac 开发有兴趣的话，用来入门会是不错的选择。

[Creating and Distributing iOS Frameworks](https://www.raywenderlich.com/126365/ios-frameworks-tutorial)

如果在你的两个 app 中有共享的代码部分，那么将它们提取出来创建一个框架进行代码共享和维护一般都是很好的主意。本文介绍了对代码进行封装，并在不同平台进行重用的方法。最后，文章也涉及了如何发布在 CocoaPods 等方面的内容。如果你有计划发布和维护开源框架的话，本文会是很好的入门指导。

**Android**

[全民K歌增量升级方案](https://mp.weixin.qq.com/s?__biz=MzI1NjEwMTM4OA==&mid=2651231875&idx=1&sn=aafecb7dd87f8fbac3111d88022b5632&scene=1)

本文主要介绍一种增量升级方案。用户在升级版本时，不需要下载完整的安装包，只需下载增加的部分即可体验新版本完整功能，即节约用户流量，也减少服务器流量，并解决了多渠道问题，值得尝试。

[Android逆向之旅—动态方式破解apk终极篇(应对加固apk破解方式)](http://www.wjdiankong.cn/blog/android%E9%80%86%E5%90%91%E4%B9%8B%E6%97%85-%E5%8A%A8%E6%80%81%E6%96%B9%E5%BC%8F%E7%A0%B4%E8%A7%A3apk%E7%BB%88%E6%9E%81%E7%AF%87%E5%BA%94%E5%AF%B9%E5%8A%A0%E5%9B%BAapk%E7%A0%B4%E8%A7%A3%E6%96%B9/)

现在市场中加固apk的方式一般就是两种：一种是对源apk整体做一个加固，放到指定位置，运行的时候在解密动态加载，还有一种是对so进行加固，在so加载内存的时候进行解密释放。本文主要针对第一种加固方式实施了破解。

[Android并发编程起因](https://yq.aliyun.com/articles/54111)

大多数的Android设备是多处理器的，Android3.0和以后的版本开始支持多处理器核心架构。多处理器对称Symmetric Multi-Processor缩写为SMP，定义了针对多核CPU如何共享内存的设计。SMP使得软件开发变得更加复杂，而且SMP工作在ARM类型处理器上比x86处理器上更具有挑战，x86测试运行正常的代码可能在ARM上可能会执行失败。阅读文章，了解更多Android并发编程的知识。

## 开源项目

**iOS**

[hopper-swift-demangle](https://github.com/keith/hopper-swift-demangle)

[Hopper](http://www.hopperapp.com) 是 OS X 下的一个二进制反编译工具，我们可以用它来对编译后的二进制文件进行反编译来探索实际的行为。但是对于 Swift，由于存在 mangling，所以我们得到的反编译结果阅读起来会十分困难。这个插件将 Swift 的编译符号进行了还原，能让我们更容易地研究 Swift 二进制的反编译结果。

[PinpointKit](https://github.com/Lickability/PinpointKit)

这个框架可以让用户或者测试者通过简单的手势来向你发送带有标注的截图反馈或者是输出日志。你既可以将它用作实际产品上线后的用户反馈渠道，也可以作为内部测试时加速交流的工具。

[Flow](https://github.com/JohnSundell/Flow)

虽然基于过程的编程方式在很多时候并不是一个维护大型项目的可行方式，但是在一些像是游戏脚本或者任务脚本开发中，将各个操作进行组合还是很常见的。Flow 框架为“基于操作的编程”提供了一套简单的 API 调用方法，能让我们很容易地将各个操作级联和组织起来，而不论它是同步操作还是异步操作。

**Android**

[AndroidPhotoFilters](https://github.com/Zomato/AndroidPhotoFilters)

PhotoFiltersSDK旨在提供快速、强大和灵活的图像处理功能，该项目实现了给图片添加滤镜的功能。

[App-Architecture](https://github.com/frodoking/App-Architecture)

App-Architecture是一个关于移动应用一整套架构的解决方案开源项目。主要目的是整合流行开发模式，然后形成一个App快速开发解决方案。framework工程实现了主要架构，主要目的是抛开平台相关性。作者的另外一个开源项目[GithubIOSClient](https://github.com/frodoking/GithubIOSClient)就使用了该架构。

[CarouselLayoutManager](http://androidone.io/info_10265.html)

该项目实现了旋转木马风格的RecyclerView。


## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**中高级Android开发2名 & 高级iOS开发1名 by 欣欣旅游**

地点厦门。旅游电商行业，要求两至三年移动开发工作经验，参与过应用架构设计优先。薪资面议。简历投递邮箱：chenqh@cncn.com

## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[GMTC全球移动技术大会](http://gmtc.geekbang.org/?utm_source=zhoubao&utm_medium=xuachuan02&utm_campaign=0613)

6月24-25日北京举办。来自BAT、携程、滴滴、微博、和社区的技术专家联袂分享，主题包括应用架构、性能优化、动态化、插件化、Swift、React Native、Weex等，为中高级移动开发工程师献上一场技术盛宴！在『移动开发前线』公众号回复“大会”可获得购票优惠码。

[【InfoQ大咖说】覃超小魔王陪你看WWDC 2016](http://www.panda.tv/397309)

今晚WWDC不知道有多少人会熬夜看直播，为了这些熬夜党们我们准备了在线微信群和在线直播，由峰瑞资本技术合伙人及前Facebook早期工程师陪你看直播，一起吐槽。

----

上周移动开发前线公众号精彩文章：

* [使用React Native编写跨平台App](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112358&idx=1&sn=f8d16ece5c6cec740dc2b4e0397329f4#rd)
* [Android VPN实现原理介绍](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112375&idx=1&sn=8217fef8af88eff7bd074b643a0529ca#rd)

阅读更多移动开发好文，欢迎关注『移动开发前线』公众号。
