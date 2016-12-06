+++
title = "移动开发每周阅读清单：第二十期"
date = "2016-07-19T21:33:45+08:00"
description = "7月19日，苹果发布旗下多款产品的系统更新，涵盖iOS、macOS、tvOS、以及watchOS四大系统正式版，以及这些系统的开发者测试版。现在苹果旗下的系统很多，一次更新完也不轻松啊。"
tags = ""
+++

## 新闻

[苹果放出系统更新全家桶 正式版+测试版全都有](http://tech.sina.com.cn/mobile/n/n/2016-07-19/doc-ifxuapvs8777687.shtml)

7月19日，苹果发布旗下多款产品的系统更新，涵盖iOS、macOS、tvOS、以及watchOS四大系统正式版，以及这些系统的开发者测试版。现在苹果旗下的系统很多，一次更新完也不轻松啊。

[Android 7.0最后一版预览开放下载](http://news.mydrivers.com/1/491/491795.htm)

谷歌官方释出了第五版Android 7.0 Nougat Developer Preview，这将是正式版前最后一版预览。本版支持General Mobile 4G、Pixel C、Nexus 5X、Nexus 6、Nexus 6P、Nexus 9、Nexus Player等谷歌直系设备。新的Android N开发者预览版包含了最新的API（level 24）和模拟器，开发者依然可以做应用兼容测试准备。

## 教程

**iOS**

[WWDC 16上发布的更新全攻略](https://gist.github.com/mackuba/e8fb4219c7ef611f47cdb66b93986d85)

波兰开发者Kuba Suder在看完本届的WWDC、各种Session和官网发布声明之后总结的文章，非常全面，有些隐藏更新苹果很可能只是在某些地方不经意提到，很容易忽略过去，因此本文对于iOS开发者来说值得一读。

[Swift类型的秘密](https://medium.com/@slavapestov/the-secret-life-of-types-in-swift-ff83c3c000a5#.dxzz78wox)

Swift团队负责编译器部分的Slava Pestov的文章。本文是对Swift类型是如何实现的一个详细解释，看完能让你对Swift中的类型理解更加深入，同时也让你对如何给Swift项目贡献给出了一些提示。

[高效的iOS系统版本检查](https://pspdfkit.com/blog/2016/efficient-iOS-version-checking)

对于iOS系统版本检查我们有许多方案来实现，Peter Steinberger写了这篇文章，梳理了各种方案并给出他认为最有效率的做法。

**Android**

[浅谈Android自定义锁屏页的发车姿势](https://mp.weixin.qq.com/s?__biz=MzI1NjEwMTM4OA==&mid=2651231949&idx=1&sn=c5de2b2a719644392ddc756a6c6d5920&scene=0)

要实现一个自定义锁屏是一件繁琐的事情，因为系统有100种方法让这个非本地的锁屏待不下去。但是，人类的智慧是无限的，程序员需要逆流而上。Android系统实现自定义锁屏页的思路很简单，即在App启动时开启一个service，在Service中时刻监听系统SCREEN_OFF的广播，当屏幕熄灭时，Service监听到广播，开启一个锁屏页Activity在屏幕最上层显示，该Activity创建的同时会去掉系统锁屏。本文给出了自定义锁屏的具体实现。

[HermesEventBus-饿了么开源的Android跨进程事件分发框架](https://elelogistics.github.io/2016/07/13/HermesEventBus-%E4%B8%80%E7%A7%8D%E6%96%B0%E7%9A%84Android%E8%B7%A8%E8%BF%9B%E7%A8%8B%E4%BA%8B%E4%BB%B6%E5%88%86%E5%8F%91%E6%A1%86%E6%9E%B6)

由于Android不同进程之前不能相互通信，所以当开发过程中遇到跨进程通信的时候,常用的方案就是AIDL(Android Interface Definition Language)通过它我们可以定义进程间的通信接口,但是当应用中出现大量跨进程通信的时候，比如你想体验一下插件化开发或者特殊需求在单应用中需要开多个进程，那么写过AIDL的同学都会有痛不欲生的感觉。HermesEventBus就是为了解决此问题而生，本文详细讲解了该框架的用法及原理。

[FaceBook出品：基于Android的内存优化](http://www.jianshu.com/p/831f936b8304)

作者通过自动化工具来测试不同场景和设备上运行的性能，以此衡量出代码在运行时的内存使用率，帧率等。当使用其中一个工具，TraceView，测试发现对Long.valueOf()有频发的调用，使内存中堆积的对象过多，导致崩溃。这篇文章描述了如何解决这个问题，并且提供了相关的源码。

## 开源项目

**iOS**

[FileKit](https://github.com/Dschee/FileKit)

在Objective-C中我们有非常方便的调用NSString的文件路径的方法，但在Swift中会比较麻烦，这个开源项目即将相关API进行封装，模仿成NSString的调用方式，并且还增加了一些功能。

[facebook-sdk-swift](https://github.com/facebook/facebook-sdk-swift)

Facebook发布了纯由Swift编写的SDK开源项目，表明了它对Swift语言的大力支持。目前项目还是beta版本，初始的commit message是非常可爱的颜文字，而且有亚洲风格，让人怀疑此SDK的主开发者是个亚裔呢。

[Celluloid](https://github.com/100mango/Celluloid)

一个完整的iOS app项目，其对应的app已上架app store，充分运用和支持Photo Extension特性。纯Swift编写，非常好的学习项目。

**Android**

[StereoView](https://github.com/ImmortalZ/StereoView)

这是一个Android 3D立体无限旋转滚动容器项目，实现的3D效果使用场景很多，推荐大家收藏。

[GiftCard](https://github.com/ldoublem/GiftCard)

这是一个效果很棒的礼物卡效果，动画效果很赞，适合于卡券类页面的显示。

[AndroidChromium](https://github.com/JackyAndroid/AndroidChromium/blob/master/README-CN.md)

谷歌浏览器安卓版源码项目，本项目是世界级的安卓架构，理清本项目业务逻辑完全可以胜任国内一线公司工程师。



## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

本周暂无新工作推荐，可以看看上周刚发布的两个新职位。

## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[APMCon中国应用性能管理大会](http://www.bagevent.com/event/109881)

8月18日~19日在北京召开。聚焦于应用性能管理垂直领域的盛会。来自LinkedIn、AppDynamics、阿里巴巴、腾讯、京东、新浪、美团、360等国内外一线互联网公司的技术专家将给大家带来精彩的演讲分享！

----
