+++
title = "移动开发每周阅读清单：第四期"
date = "2016-03-21T21:33:45+08:00"
description = "『移动开发每周阅读清单』第四期与大家见面了，今晚苹果举行春季发布会，不知道会有人熬夜看直播吗？"
tags = ""
+++

『移动开发每周阅读清单』第四期与大家见面了，今晚苹果举行春季发布会，不知道会有人熬夜看直播吗？

## 新闻

[Apple 正在准备自有云架构 McQueen](https://developer.apple.com/news/?id=03092016a)

依赖移动终端的力量，Apple 现在已经是全球最大的云服务提供商之一。包括 App Store，iCloud，Apple Music 等在内的服务每天有数以亿计的用户在使用。业内人士报道，Apple 最近开始了一个叫做 “Project McQueen” 的项目，试图开始构建企业自由的云架构。在之前，Apple 的云服务大部分都依赖于 Amazon，并使用了某些 Microsoft 和 Google 的服务。显然 Apple 对于现状并不太满意，特别是用户在加载图片或是下载视频时可能面临的速度较慢的问题，已经成为了 Apple 云服务发展的瓶颈。

[App Analytics 分析周报上线](https://developer.apple.com/news/?id=03092016a)

对于 app 下载和评论的管理一直是 iTunes Connect 的弱项，不过最近一两年来 Apple 一直这方面进行了改进，包括在 iTunes Connect 中添加分析模块，更好的 Crash 报告等。最近，Apple 为开发者提供了周报邮件，以帮助开发者追踪 app 的下载和评分状况。有需要的开发者可以在 iTunes Connect 中进行订阅。

[Android N内部名称曝光：纽约芝士蛋糕](http://digi.tech.qq.com/a/20160318/048847.htm)

谷歌已经放出了Android N的第一个开发者预览版，最终名称应该为安卓7.0，根据惯例谷歌每次都会为新系统取一个甜点的代号，这次的甜点是以N打头。而现在最新的消息是，Android N的内部名称也已曝光，为New York Cheesecake。

[Google调整Material Design加入底部导航](http://www.androidpolice.com/2016/03/14/bottom-bars-officially-become-a-thing-with-latest-material-spec-update/)

随着Android N预览版的发布，Google也更新了其Material Design设计语言，加入了Bottom Navigation。因为之前Google曾在规范里声明避免添加底部导航，这次更新也被视为食言和自打脸的行为。不过Google此举显然是经过深思熟虑和市场调查后的产物，倒不必盲目反对。

[Google Play提供应用试用功能](http://app.myzaker.com/news/article.php?app_id=5&_appid=AndroidPhone&_version=6.43&_bsize720_1280&sharechannel=wx&pk=56e7d33e9490cbc83e000088)

最初，当你在应用商店搜索一个应用时，只能看到相关的文字介绍和几张应用截图。为了让用户在下载前更好地了解一款应用，2014年，Google和苹果应用商店先后推出了视频预览功能，允许开发者在介绍页面放一段15到30秒的视频，来更好地展示自己的应用。现在，Google决定更进一步，除了截图和视频，用户可以在下载一款应用前，直接试用10分钟。


## 教程

**iOS**

[iOS冰与火之歌番外篇 - App Hook答疑以及iOS 9砸壳](http://drops.wooyun.org/papers/13824)

关于 iOS 安全系列的最新文章。上架 App Store 的 app 会被进行加壳处理，我们想要对这些 app 进行 hook 或者探索，第一步就是要进行去壳。本文主要介绍了 iOS 上砸壳 (Dumpdecrypted)，签名及重新安装的一些技巧。

[初探 Swift Sequences 和 Generators](http://swift.gg/2016/03/10/experimenting-with-swift-2-sequencetype-generatortype/)

Swift 的 `GeneratorType` 和 `SequenceType` 是两个非常强大的协议。如果你认为它们只是被用来构建 for...in 循环的话你就大错特错了。它们组合起来其实包含了函数式编程的很多思想，可以作为基本的容器单元进行使用。如果你对此有兴趣的话，可以通过这篇文章进行初步了解。

[VIPER to be or not to be?](https://swifting.io/blog/2016/03/07/8-viper-to-be-or-not-to-be/)

一篇关于 VIPER 架构的讨论。Apple 官方推荐的 MVC 架构可能是绝大多数 iOS app 的选择，MVC 架构虽然上手非常容易，但是精通却相对困难。对于一些比较庞大的项目，MVC 往往无法满足可维护性和可扩展性，因此才会有对其他各种开发架构的探索。VIPER 就是一个通过组件职责进行划分的构建框架，如果你的 app 规模较大，使用 VIPER 可能会有助于 app 模块的明确化，本文在这个方向对 VIPER 的适用场景和一些实践进行了说明。

**Android**

[Android安全攻防战，反编译与混淆技术完全解析（下）](http://blog.csdn.net/guolin_blog/article/details/50451259)

Apk如果没有采取一定的安全处理，很容易反编译。这样就有可能泄漏核心技术，因此一款安全性高的程序最起码要做到的一件事就是：对代码进行混淆。混淆代码并不是让代码无法被反编译，而是将代码中的类、方法、变量等信息进行重命名，把它们改成一些毫无意义的名字。混淆代码可以在不影响程序正常运行的前提下让破解者很头疼，从而大大提升了程序的安全性。本文详细讲解了Apk的混淆技术。

[dagger2让你爱不释手-基础依赖注入框架篇](http://www.jianshu.com/p/cd2c1c9f68d4)

使用依赖注入带来的好处非常明显，比如依赖的注入和配置独立于组件之外。因为对象是在一个独立、不耦合的地方初始化，所以当注入抽象方法的时候，我们只需要修改对象的实现方法，而不用大改代码库。依赖也可以注入到一个组件中：我们可以注入这些依赖的模拟实现，这样使得测试更加简单。dagger2是一款知名的依赖注入库，本文是一篇介绍dagger2基础的文章，有助于我们快速上手dagger2。

[Butter Knife源码解析](https://mp.weixin.qq.com/s?__biz=MzA4MjU5NTY0NA==&mid=404147665&idx=1&sn=a16153b2a658db64ab80926cd3b76447)

ButterKnife是一个专注于Android系统的View注入框架，可以让开发人员从繁琐、臃肿的代码中解脱出来，并且实现这些只需要几行代码。ButterKnife能够提供的注解类型太多了，本文以解析@Bind注解为例，为我们介绍了Butter Knife的实现原理。

[大型项目 Gradle 的常用库和版本管理](http://www.wangchenlong.org/2016/03/15/manage-gradle-lib-version/)

随着Android开发的成熟，模块越来越多，引入库也随之增加， 需要统一管理这些库和版本号。 根据自己的开发经验， 本文介绍使用Gradle参数配置实现库的规范管理。

[Android界面性能调优手册](https://androidtest.org/android-graphics-performance-pattens/)

界面是Android应用中直接影响用户体验最关键的部分。如果代码实现得不好，界面容易发生卡顿且导致应用占用大量内存。本文是一篇界面性能优化的高质量文章，作者结合自己的实践经验，讲解了渲染知识、检测及调试技巧等。并且给出了实用的界面优化建议。

## 开源项目

**iOS**

[PeekPop](https://github.com/marmelroy/peekpop)

iPhone 6s 和 6s Plus 支持 3D Touch 技术，并提供了一种全新的 Peek & Pop 交互方式，可以让用户对内容进行快速预览，并提供新的入口。但是这个特性被限制在了新设备上，这使得绝大多数用户无法享受到 Peek & Pop 所带来的便利。该框架通过检测用户手势中的按压半径，在老设备上模拟 3D Touch 的行为，为这些设备也带来了类似 Peek & Pop 的体验。该框架 API 设计上与 Apple 的现有体系十分类似，因此转换起来也非常方便。

[SPTPersistentCache](https://github.com/spotify/SPTPersistentCache)

Spotify 最近正在陆续将他们的 iOS 组件进行开源，这次为我们带来了一个缓存管理的框架。SPTPersistentCache 提供了一整套持久化缓存的解决方案，它将缓存 header 信息存储到分立的缓存文件中，并使用这些信息进行过期管理和快速查找。同时该框架还提供了一个配套的 OS X 应用，以帮助开发者确认当前缓存系统中的内容。

[Bolts in Swift](https://github.com/BoltsFramework/Bolts-Swift)

在 Objective-C 时代，[Bolts](https://github.com/BoltsFramework/Bolts-ObjC) 就是非常常见的任务管理框架，它提供了一种类似 Promise 的方式来让我们避免复杂的异步任务处理。Bolts-Swift 将类似的内容移植到了 Swift 上，使用 Swift 的开发者现在也可以利用类似于原来 Bolts 的 API 进行异步任务管理。采用任务和 Promise 的方式来编写异步代码，有助于提高代码的可读性和维护性。如果你还没有开始尝试做类似的事情，现在就是一个进行实践的好机会。

**Android**

[BottomBar](https://github.com/roughike/BottomBar)

这是一具Material Design风格的底部切换控件。

[NodeFlow](https://github.com/Telenav/NodeFlow)

NodeFlow提供了一个简单的方法来可视化多级内容，能够完美显示项目中的分类/子类。

[RxJavaApp](https://github.com/jiang111/RxJavaApp)

RxJavaApp是一个用于学习RxJava操作符的完整项目，该项目有助于开发者快速上手RxJava。

[CoCoin](https://github.com/Nightonke/CoCoin/blob/master/README-ZH.md)

CoCoin是一款多视图记账APP，功能比较全面，涉及到报表绘制、界面自定义等多个知识点。

本周移动开发前线公众号优秀文章：

* [不要写死！天猫App的动态化配置中心实践](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=402842876&idx=1&sn=e15d596c95bf7d1ed579cfd7e410696a#rd)
* [滴滴出行iOS客户端架构演进之路](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=402854111&idx=1&sn=5876e615fabd6d921285d904e16670fb#rd)
* [Android MVP架构中的Presentation层应该怎么设计](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=402868193&idx=1&sn=790e12f84dfcea171528e6d3789c69ed#rd)
* [天猫App A/B测试实践](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=402918999&idx=1&sn=e1dcacc4dd314013a1153ec90ab4bb82#rd)

欢迎大家关注。
