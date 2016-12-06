+++
title = "移动开发每周阅读清单：第二十二期"
date = "2016-08-01T21:33:45+08:00"
description = "库克在员工会议上公布了最近销售了十亿台 iPhone ，这标志着 Apple 的一个里程碑。库克表示， iPhone 已经成为一款改变世界的成功产品，及感谢每一个人在 Apple 帮助改变世界。"
tags = ""
+++


## 新闻

[Apple 官方宣称已经销售十亿台 iPhone](http://www.macrumors.com/2016/07/27/apple-has-sold-1-billion-iphones/)

库克在员工会议上公布了最近销售了十亿台 iPhone ，这标志着 Apple 的一个里程碑。库克表示， iPhone 已经成为一款改变世界的成功产品，及感谢每一个人在 Apple 帮助改变世界。

[安卓党福音：谷歌新算法让更新包减小50%](https://www.zybuluo.com/Sniper/note/454529)

近日Google Play宣布应用全新算法（即二进制差量算法bsdiff），该算法能够使用户下载应用更新包的文件大小减少了50%，这对于许多存储吃紧的安卓用户来说，无疑是个好消息。

## 教程

**iOS**

[如何在 Objective-C 的环境下实现 defer](https://github.com/Draveness/iOS-Source-Code-Analyze/blob/master/libextobjc/%E5%A6%82%E4%BD%95%E5%9C%A8%20Objective-C%20%E7%9A%84%E7%8E%AF%E5%A2%83%E4%B8%8B%E5%AE%9E%E7%8E%B0%20defer.md)

Swift 2 加入了 defer 关键字，拥有了在推迟代码执行的功能，而本文分析了 libextobjc 源码，探讨了在 Objective-C 中实现 defer 效果的方案。

[理解 iOS 的内存管理](http://blog.devtang.com/2016/07/30/ios-memory-management/)

在 Swift 和 Objective-C 中，管理内存的方案都是 ARC ，但作为一名合格的 iOS 开发者，仍然有必要理解 iOS 的内存管理，学会如何解决循环引用的问题。本文介绍了如何解决循环引用，以及如何使用 Instruments 查找循环引用问题。

[Swift 3 GCD 改进速览](https://medium.com/swift-and-ios-writing/a-quick-look-at-gcd-and-swift-3-732bef6e1838)

从 Swift 2 迁移到 Swift 3 是个庞大的工程，而 GCD 的变化尤其之大，本文介绍了各种 dispatch\_async 、Queue attributes 、Work items、dispatch\_time_t 等在 Swift 3 下的语法变化。

**Android**

[Android闹钟设置的解决方案](http://www.jianshu.com/p/1f919c6eeff6)

Android设置闹钟并不像iOS那样这么简单，做过Android设置闹钟的开发者都知道里面的坑有多深。本文针对不同的系统版本，给出了Android闹钟设置的解决方案。

[Android性能模式篇之智能的工作计划](http://hlong.xyz/2016/07/28/Android%E6%80%A7%E8%83%BD%E6%A8%A1%E5%BC%8F%E7%AF%87%E4%B9%8B%E6%99%BA%E8%83%BD%E7%9A%84%E5%B7%A5%E4%BD%9C%E8%AE%A1%E5%88%92%28%E8%AF%91%29/)

随着需求和业务的发展，越来越多的apps需要去异步执行各种各样的任务，有些任务是用户去执行的，而有些任务则是apps自身需要去执行，这些任务的使用场景有：更新网络资源、下载信息、更新后台任务等。如何智能化的去处理这项工作，是至关重要的，如果处理方式得当的话，不仅可以提高你的应用性能，还可以减轻系统的压力。阅读文章，了解如何做到智能处理该问题。

[Android Patch方案与持续交付](http://wereadteam.github.io/2016/07/26/AndroidPatch/)

近一两年Android热补丁框架非常热门。早期的补丁框架偏向于以代码修复为主，主要分为两大类：native hook方案和Multidex方案。当这些开源的解决方案不能满足需求的时候，就需要重新造一个轮子出来。本文是微信读书团队关于热修复的实践总结，文中提供的热修复方案全面支持patch Java代码、资源文件和native so文件。版本只需要正常滚动，开发同学无需关心是发布patch版本还是正常版本，并且集成非常简单。

[Android Studio 2.2 中几个实用的新功能](http://www.jianshu.com/p/bc9bbac5a170)

文章中汇总了Android Studio 2.2中一些实用的新功能。

## 开源项目

**iOS**

[lf.swift](https://github.com/shogo4405/lf.swift)

通过 RTMP 和 HLS 实现的照相机和麦克风流库，适用于 iOS 和 macOS 。

[Zip](https://github.com/marmelroy/Zip)

简单易用的解压、压缩文件的 Swift 框架。

[Translucid](https://github.com/Ekhoo/Translucid)

为文字设置图片背景的 Swift 轻量框架。

**Android**

[AutoWrapLineLayoutDemo](https://github.com/Hector1990/AutoWrapLineLayoutDemo)

AutoWrapLineLayout是Android上可自动换行的布局。[这里](http://www.jianshu.com/p/0bf98017b196)是一篇介绍该项目的文章。

[DecentBanner](https://github.com/chengdazhi/decentbanner)

这是一个支持无限循环的图片轮播组件，提供了是否自动播放的控制开关，轮播效果很流畅。

[Tinker_imitator](https://github.com/zzz40500/Tinker_imitator)

微信热修复方案的三方实践。

[Android傻瓜式分包插件](https://github.com/TangXiaoLv/Android-Easy-MultiDex)

开发过大中型Android项目的同学对于方法数满65536问题都不陌生，我们一般选择分包来解决该问题。该项目给出的解决方案配置很简单，推荐大家使用。


## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**iOS/Android工程师 by 东方证券**

地点上海。负责公司理财产品开发。要求本科学历，3年开发经验，有独立开发者经验优先。薪资面议。简历发送至 114476523@qq.com

## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[APMCon中国应用性能管理大会](http://www.bagevent.com/event/109881)

8月18日~19日在北京召开。聚焦于应用性能管理垂直领域的盛会。来自LinkedIn、AppDynamics、阿里巴巴、腾讯、京东、新浪、美团、360等国内外一线互联网公司的技术专家将给大家带来精彩的演讲分享！

----
