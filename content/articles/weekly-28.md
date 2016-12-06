+++
title = "移动开发每周阅读清单：第二十八期"
date = "2016-09-12T21:33:45+08:00"
description = "Apple 正式发布了 iPhone 7 / 7 Plus、Apple Watch 2 新品，带来 AirPods 无线耳机，并把马里奥带进了 iOS。iPhone 7 新增亮黑色，移除3.5mm 耳机孔，支持 IP67 防水防尘等级。"
tags = ""
+++

## 新闻

[Apple 发布 iPhone 7 / 7 Plus 、Apple Watch 2 等新品](http://www.apple.com/cn/iphone-7/)

Apple 正式发布了 iPhone 7 / 7 Plus、Apple Watch 2 新品，带来 AirPods 无线耳机，并把马里奥带进了 iOS。iPhone 7 新增亮黑色，移除3.5mm 耳机孔，支持 IP67 防水防尘等级。

[谷歌开始向Android One手机推送安卓7.0](http://mobile.yesky.com/392/104916392.shtml)

按照以往的惯例，谷歌的Nexus手机和平板将享受到第一时间升级至最新版Android系统的优待，今年也不例外，几天前谷歌在修复电池和性能问题之后终于向Nexus 6P推送了Android 7.0 Nougat正式版。而另一方面，Android One手机则应该是第二波收到Android 7.0更新的机型。据最新报道，谷歌已经在开始向Android One手机推送Nougat更新了。

## 教程

**iOS**

[处理手势冲突和错乱的一点经验](http://yulingtianxia.com/blog/2016/08/29/Some-Experience-of-Gesture/)

作者分享了自己在实践中得到的一些处理手势的经验，如界面内容变化较多引发的手势冲突、界面内容数量较多引发的手势错乱。

[从 Auto Layout 的布局算法谈性能](http://draveness.me/layout-performance/)

本文从 iOS 中影响性能的另一大杀手，也就是万恶之源 Auto Layout来分析如何对 iOS 应用的性能进行优化以及 Auto Layout 到底为什么会影响性能？并给出选择 Auto Layout 还是 frame 布局一些建议。

[Swift 如何同时兼容 Xcode7 和 Xcode8](http://radex.io/xcode7-xcode8/)本文介绍了如何让 Swift 项目可以同时在 Xcode 7 和 Xcode 8 下开发，并介绍了将项目迁移到 Xcode 8 & Swift 2.3 的一些技巧，同时本文还有一篇[中文翻译](http://swift.gg/2016/09/02/xcode7-xcode8/)。


**Android**

[Android 6.0运行时权限管理最佳实践](http://blog.csdn.net/yanzhenjie1003/article/details/52503533)

在Android6.0开始，App可以直接安装，App在运行时一个一个询问用户授予权限，系统会弹出一个对话框让用户选择是否授权某个权限给App。这个对话框不是开发者调用某个权限的功能时由系统自动弹出，而是需要开发者手动调用，如果你直接调用而没有去申请权限的话，将会导致App奔溃。本文为我们详细讲解了Android 6.0的权限管理知识。

[Android内存泄漏的简单检查与分析方法](http://mp.weixin.qq.com/s?__biz=MzAxMzYyNDkyNA==&mid=2651332518&idx=1&sn=bcc31ed271efbdc7784c2b18bd046d33&scene=1&srcid=0908vrWOHzhOfspBV5CIdIA4#rd)

内存泄漏问题大约是Android开发者最烦恼的问题之一了，内存泄漏不可小视，在Android开发中，比如说一个Activity页面会占用许多资源开销，如果页面发生泄漏，关闭以后页面没有能被系统回收，对应用程序的伤害是很大的。本文详解了如果发现内存泄漏、发现后使用工具来分析内存泄漏等知识。

[Android深入理解Loader机制，让APP轻装上阵](http://mp.weixin.qq.com/s?__biz=MzIyMjQ0MTU0NA==&mid=2247483736&idx=1&sn=926a762eee99264b967dd74c3f18023e&scene=1&srcid=0906d1W2N1uRyjerIoZmpCzG#rd)

Android开发者都经历过APP UI开发不当会造成OverDraw，导致APP UI渲染过慢，但是很多人却没听过OverLoad，OverLoad一般是由于开发者在主线程进行耗时操作，导致程序变慢，甚至出现的ANR的现象，那么Android早已为这种现象提供完美的解决方案，就是本文给大家带来的Android Loader机制。

## 开源项目

**iOS**

[TPPDF](https://github.com/Techprimate/TPPDF)

一款将 NSMutableAttributedString 渲染成 PDF 的 Swift 框架，基于生成器模式。

[iOS10-day-by-day](https://github.com/shinobicontrols/iOS10-day-by-day)

shinobicontrols 新开 iOS-day-by-day 项目，和以往的 day-by-day 项目一样，该项目演示了 iOS 10 的各种新特性 Demo 。

[NMessenger](https://github.com/eBay/NMessenger)

基于 AsyncDisplaykit 的轻量聊天消息组件。

**Android**

[LingDong2.0](https://github.com/zhoubowen-sky/LingDong2.0)

这是一个面对面文件快传的项目。

[GeekNews](https://github.com/codeestX/GeekNews)

GeekNews是一款开源的新闻阅读App，使用了目前比较流行的一些技术，包括Material Design、MVP、RxJava、Retrofit、Dagger2、Realm、Glide等。

[TedBottomPicker](https://github.com/ParkSangGwon/TedBottomPicker)

一款从底部弹出的图片选择器，支持滑动到顶部的功能，用户体验比较友好。


## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

本期暂无工作推推荐。


## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

----
