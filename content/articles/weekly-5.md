+++
title = "移动开发每周阅读清单：第五期"
date = "2016-03-28T21:33:45+08:00"
description = "『移动开发每周阅读清单』第五期与大家见面了，上周苹果春季发布会已经开过了，比起以往的产品还有亮点，这次大家好像就剩下吐槽了呢。"
tags = ""
+++

​『移动开发每周阅读清单』第五期与大家见面了，上周苹果春季发布会已经开过了，比起以往的产品还有亮点，这次大家好像就剩下吐槽了呢。

## 新闻

[Apple 2016 春季发布会公布小屏 iPhone SE 以及 9.7 inch iPad Pro](http://www.macrumors.com/2016/03/22/9-7-ipad-pro-iphone-se-2gb-ram/)

今年的春季发布会比以往都要短，Apple 在发布会上主要公布了小屏 iPhone SE 以及 9.7 inch iPad Pro。两者都配置了与当前 Apple 旗舰产品类似的硬件，包括 2GB 的内存以及最新的 CPU。Mac 产品线本次没有按照惯例进行更新，有媒体猜测 Apple 正在重新设计 13 inch 和 15 inch 的笔记本电脑，并将于六月或者七月随着 WWDC 一同公布。

[Xcode for iPad Pro 消息](http://minutestomidnight.net/blog/2016/3/considering-an-xcode-for-ipad-pro)

iPad Pro 具有堪比甚至超过某些笔记本电脑的屏幕尺寸和性能，而且被 Apple 定义为一款生产力工具。最近有传言表明 Apple 正在开发 iPad Pro 版的 Xcode，包括文本编辑，Interface Builder，完整的编译链工具，版本管理，以及本机调试等一系列激动人心的特性。如果消息属实，那在不久的将来我们应该就可以在移动设备上开发移动设备应用了。

[谷歌计划做Android手机通用VR设备 类似三星Gear开放版](http://news.4399.com/hangye/zixun/vr/m/615648.html)

Google内部人士的消息称，Google第一款真正意义上的VR设备实际上就相当于三星Gear VR的开放版——该产品不会受品牌约束，支持所有的Android手机设备接入。在软件层面上，Google未来的计划是把VR功能内建到Android中。如果这是真的，那么诸如Cardboard这样的VR设备将无需第三方应用介入，简化转换过程，进而从理论上降低延迟。目前Google官方尚未对Android VR和VR头戴设备的消息做出回应，但如果不出意外的话，相信在今年5月的I/O大会上我们就能一睹为快了。


## 教程

**iOS**

[iOS 视图控制器转场详解](https://github.com/seedante/iOS-Note/wiki/ViewController-Transition)

iOS 7 开始，SDK 为我们提供了方便的自定义 View Controller 转场的解决方案，通过精心调整，可以说我们现在能够实现任何复杂的转场效果，这对于提高应用品质和用户的使用体验可以说是至关重要的。这篇文章介绍了转场背后的机制，缺陷以及实现过程中的技巧与陷阱。如果你对自定义转场还不理解的话，这篇文章将通过一步步带你实现一些转场效果，让你理解自定义转场背后的原理。

[iOS 9.3 更新，动态库加载速度大幅优化](https://github.com/stepanhruda/dyld-image-loading-performance)

随着春季发布会的结束，iOS 9.3 也正是发布了。之前 iOS 8 一直以来困扰开发者的动态库冷加载速度太慢的问题在 iOS 9.3 中得到了彻底的解决。开发者发现，对于数量较多的动态框架，新版本中加载速度约提升了 75%。不过因为现在 app 的不太可能只从 iOS 9.3 开始支持，因此动态库的使用还是应该谨慎，或者使用文中的方法来绕过加载过慢的问题。

[Contributing to Open Source Swift](https://realm.io/news/tryswift-jesse-squires-contributing-open-source-swift/)

这是本月 try! Swift 会议上一个 session 的视频。在 Swift 开源后，iOS/OS X 开发者社区展现出了巨大的热情并提交了相当多的贡献，来帮助 Swift 进步。这个 session 为我们讲述了如何上手并准备为 Swift 提交代码或者做出贡献。有志于为 Swift 开源作出贡献，或者是对 Swift 源码结构和开发方式好奇的开发者可以看看。

**Android**


[从零开始的Android新项目3 - MVPVM in Action， 谁告诉你MVP和MVVM是互斥的](http://blog.zhaiyifan.cn/2016/03/16/android-new-project-from-0-p3/)

MVVM(Model-View-ViewModel)，在Android上对应data binding。即ViewModel到View的映射，不需要再去自己找到View，然后更新字段，而是在映射建立后直接更新ViewModel然后反映到View上。而MVP解决了activity/fragment过重的问题，通过V/P分离能够帮助提高可维护性。本文作者在自己的新应用中，采用了MVP+MVVM的混合方式，阅读文章，了解这种架构的详细实施方案。

[Android Bitmap面面观](http://www.jayfeng.com/2016/03/22/Android-Bitmap%E9%9D%A2%E9%9D%A2%E8%A7%82/)

在日常开发中，可以说和Bitmap低头不见抬头见，基本上每个应用都会直接或间接的用到，而这里面又涉及到大量的相关知识。本文是对Bitmap常用知识的梳理总结，有助于我们全面的了解Bitmap的一些细节。

[ViewAnimator源码分析](http://www.jianshu.com/p/749c4531d108)

在项目开发中我们应该都接触过动画效果的开发。我们知道在Andorid中实现动画大致分为两类，一种是Tween/Frame动画，另一种是Property Animation也就是属性动画。本文章介绍了属性动画中关于ViewAnimator的相关实现原理。ViewAnimator是用来简化我们写属性动画代码量的，它可以通过非常简洁的代码通过建造者模式调用来组合各种动画，从而让代码简洁易读。本文详细解析了ViewAnimator的源码。

[Android自定义Lint实践](http://tech.meituan.com/android_custom_lint.html)

Android Lint是Google提供给Android开发者的静态代码检查工具。使用Lint对Android工程代码进行扫描和检查，可以发现代码潜在的问题，提醒程序员及早修正。为保证代码质量，很多开发者都会在开发流程中加入代码检查的功能，如果代码检测到问题，则无法合并到正式分支中，这些检查中就包括Lint。而由于原生Lint无法满足一些特有的需求以及原生Lint存在一些检测缺陷或者缺少一些必要的检测，所以需要自定义Lint。本文是美团关于自定义Lint的实践。

[RxJava学习总结](http://wangxinghe.me/blog/2016-03-27/rxjava-basis/)

RxJava一个响应式编程框架，采用观察者设计模式，该框架毫无疑问是近两年来最火热的Android开发技术这一，本文是一篇关于RxJava的基础教程，作者总结了自己学习RxJava的一些知识点，有助于RxJava新手快速熟练该技术。


## 开源项目

**iOS**

[Appz](https://github.com/SwiftKitz/Appz)

在 iOS 9 中使用 URL Scheme 打开其他 app 的方式受到了很大的限制，为了安全因素，Apple 鼓励使用 Universal Link 的方式在应用间跳转。但是相比起探测应用的 URL Scheme，链接更难以整理。Appz 是一个帮助开发者更容易使用 Deep Link 的框架，它收集了很多常见应用的打开方式和对应的 app id，并且保证了外部链接的检查和打开代码与应用的其他逻辑代码分离，并且易于测试。

[Permission](https://github.com/delba/Permission)

在 iOS 中获取像是推送通知，麦克风或者联系人等权限的代码虽然不是很困难，但是却分散在 SDK 的各处，使用起来不是很方便。这个框架将 iOS 中所有的权限请求集中处理，并为我们提供了统一和简洁的 API。

[RKTagsView](https://github.com/kuler90/RKTagsView)

帮助生成类似 OS X 上 NSTokenField 那样的 tag 的视图类。

[NextGrowingTextView](https://github.com/muukii/NextGrowingTextView)

随着输入文本变化而自动调整高度的 text view。相比起其他类似的实现，NextGrowingTextView 是基于 iOS 7 的 TextKit 大幅修改之前的类似框架的重写。它为使用者提供了足够的委托方法和访问接口，十分灵活。

**Android**

[nginx-rtmp-module](https://github.com/arut/nginx-rtmp-module)

这是一个本地的RTMP音视频直播demo，有了它，就可以自己学习和使用ffmpeg、libRTMP库，能够在Android下写推流以及拉流播放的代码和应用。

[BoomMenu](https://github.com/Nightonke/BoomMenu)

BoomMenu是一款带有爆炸效果的菜单按钮，不仅效果很炫，并且提供了多达32种的排列方式。

[RoadRunner](https://github.com/glomadrian/RoadRunner)

Road Runner是一个通过使用SVG图片，快速生成加载动画的库。

-----

上周移动开发前线公众号优秀文章：

* [国外iOS大牛的分享经验和对Swift的看法](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=402985015&idx=1&sn=7a25c3f3de45031d5c9c58478113fa5e#rd)
* [携程移动App架构优化之旅](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=403009403&idx=1&sn=d19264fa1d06b9c5a9dfb1d192a0ed8e#rd)
* [JSPatch开源经验分享](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=403063229&idx=1&sn=34651b982e211ae64742913026d459b0#rd)
* [移动平台的3D编程介绍：在你的应用展示3D模型](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=403104403&idx=1&sn=8a200e29db744eb032a75e88a61e5c9c#rd)
