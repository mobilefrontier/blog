+++
title = "移动开发每周阅读清单：第三十五期"
date = "2016-11-14T21:33:45+08:00"
description = "已有迹象表明，苹果正试图将某些与头戴设备相关的功能集成至iOS系统。2015年，苹果收购了Metaio，后者开发移动增强现实浏览器，以及一整套的增强现实工具。另外，前不久，苹果曝光了新的 AR 导航专利和头盔专利。"
tags = ""
+++



## 新闻

[苹果CEO库克提出下一代产品战略：专注增强现实](http://tech.qq.com/a/20161107/019819.htm)

已有迹象表明，苹果正试图将某些与头戴设备相关的功能集成至iOS系统。2015年，苹果收购了Metaio，后者开发移动增强现实浏览器，以及一整套的增强现实工具。另外，前不久，苹果曝光了新的 AR 导航专利和头盔专利。

[Android 打算终结第三方快充，强推Type-C充电标准](http://it.sohu.com/20161111/n472878365.shtml)

根据Android于10月25日更新的最新相容性定义文件（CDD）中，有开发者发现在其中 7.7 USB的相容性定义一节中，Google更新了关于充电的标准以及规范。在这份文件定义中，他们表示：“我们强烈建议Type-C设备不要支持那些借由修改提高了原本预设Vbus电压，或是修改sink/source输入电路导致设备不支持标准的USB充电器或目前Android设备上USB供电的方法。”


## 教程

**iOS**

[iOS中的各种锁](http://www.jianshu.com/p/6c8bf19eb10d)

在日常开发过程中，为了提升程序运行效率，以及用户体验，我们经常使用多线程。在使用多线程的过程中，难免会遇到资源竞争问题。我们采用锁的机制来确保线程安全。

[译文：iOS 10和macOS中的卷积神经网络](http://www.cocoachina.com/ios/20161108/17982.html)

苹果在iOS 10和macOS 10.12的Metal Performance Shaders框架和Accelerate框架里，引入了新的卷积神经网络APIs。本文将带读者走近它们，并且介绍如何使用。

[Building a Custom Collection in Swift](https://www.raywenderlich.com/139591/building-custom-collection-swift)

常用的集合类型有 Array 、 Dictionary 、 Set ，本文介绍了如何在 Swift 中编写一个自定义的集合类型。

[Structs and NSCoding](http://khanlou.com/2016/10/structs-and-nscoding/)

实现 NSCoding 需要服从NSObjectProtocol 协议，这是一个 class 的协议，那么在 Swift 中如何更好地结合 Struct 和 NSCoding ，本文作者探讨了一种可行的方案。


**Android**

[安卓动态加载入门](http://liwenkun.xyz/2016/11/11/android-load-class-dynamically/)

动态加载代码就是通过在运行时加载外部代码（磁盘，网络等）改变程序行为的技术。关于安卓动态加载技术的文章网上有很多，但很多都是基于较低安卓版本的，对于较高版本有些地方不一定适用。本文什么都基于Andriod M和大家分享了安卓的动态加载技术，让大家对这项技术有一个初步的了解。

[Android 7.1新特性之Shortcuts介绍](https://mp.weixin.qq.com/s?__biz=MzAxNjI3MDkzOQ==&mid=2654472649&idx=1&sn=3319a3e1ca0d9a78c3c3a5f05ae6f638)

Android 7.1允许App自定义Shortcuts，类似iOS的3D touch。通过在桌面长按App弹出Shortcut列表，点击某个Shortcut快速进入某项操作，同时Shortcut可以拖动到桌面进行固定。由于7.1SDK的Sources尚未开放，目前大部分内容还是根据官方AP 文档而来。Shortcuts全面介绍分为两篇，本文是基础介绍。

[Android 复杂的列表视图新写法: MultiType详解篇](https://drakeet.me/effective-multitype)

我们写一个类似微博列表页面，这样的列表是十分复杂的：有纯文本的、带转发原文的、带图片的、带视频的、带文章的等等，甚至穿插一条可以横向滑动的好友推荐条目。不同的Item类型众多，而且随着业务发展，还会更多。如果我们使用传统的开发方式，经常要做一些繁琐的工作，代码可能都堆积在一个Adapter中。本文作者给出了一种新的解决方案——MultiType。阅读文章，了解该技术的更多特性。

[PNG图片压缩对比分析](https://mp.weixin.qq.com/s?__biz=MzI1NjEwMTM4OA==&mid=2651232233&idx=1&sn=03d9858ac451f2768b804d2604a8e12e)

为了实现PNG图片的压缩，之前的处理方式是先在本地进行压缩，然后提交到SVN，再打包发布。一般采用在线压缩工具处理，将res目录下的PNG图片批量手动处理，这种方式容易出现的问题，比如为了追求高的压缩率，容易出现一张图片重复压缩的情况，导致图片严重失真；不能自定义参数开发，无法满足开发需求等。本文对比了多种压缩方案，给出了不同方案的优缺点。


## 开源项目

**iOS**

[PlaygroundTDD](https://github.com/WhiskerzAB/PlaygroundTDD)

在 Playground 中编写测试代码。

[XcodeSourceEditorExtension-Alignment](https://github.com/tid-kijyun/XcodeSourceEditorExtension-Alignment)

用于格式化代码的 Xcode Editor Extension 。

[SwiftDate](https://github.com/malcommac/SwiftDate)

可能是在 Swift 中处理 Date 的最佳方案的框架。



**Android**

[BigImageViewer](https://github.com/Piasy/BigImageViewer)

这是一个非常强大的图片工具，可以显示超级大图，不会出现OOM问题，并且占用内存很少，支持图片的平移和缩放。

[shelldroid](https://github.com/wuhx/shelldroid)

这是一个可以实现在同一台手机上管理多个微信账号的项目，手机需要ROOT，不过项目的实现原理很简单。

[ActivitySwitcher](https://github.com/Hitomis/ActivitySwitcher)

ActivitySwitcher是一个基于Activity视图操作管理库，可以实现Activity之间任意跳转、关闭任意一个Activity以及结束应用程序等功能。




## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**Android研发工程师 by QQ空间**

坐标深圳。负责Android客户端相关研发。要求2年以上项目经验，熟悉Web、React Native相关知识，对新技术有热情。简历发送至 mangosmwang@qq.com



## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

----

[ArchSummit全球架构师峰会](http://bj2016.archsummit.com/)

地点北京。ArchSummit秉承“实践第一、案例为主”的原则，展示新技术在行业应用中的最新实践，技术在企业转型中的加速作用，帮助企业技术管理者、CTO、架构师做好技术选型、技术团队组建与管理，并确立技术对于产品和业务的关键作用。
