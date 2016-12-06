+++
title = "移动开发每周阅读清单：第二十一期"
date = "2016-07-25T21:33:45+08:00"
description = "本周，苹果发布了 iOS 10 的第三个开发者预览版。在这次更新中，通过 Touch ID 直接解锁手机的功能终于回归，同时也加入了一些新功能，并对此前的一些功能进行了调整和优化。下面是整理的 iOS 10 最新测试版的新变化。"
tags = ""
+++


## 新闻

[14 个 iOS 10 Beta 3 的新变化](http://mp.weixin.qq.com/s?__biz=MjM5NDU1NTE5NA==&mid=2712709607&idx=2&sn=dd0e2032bb7910d142fbf6c15668861c&scene=1&srcid=0722iqHmlLHxdyr0dONPPWMM#wechat_redirect)

本周，苹果发布了 iOS 10 的第三个开发者预览版。在这次更新中，通过 Touch ID 直接解锁手机的功能终于回归，同时也加入了一些新功能，并对此前的一些功能进行了调整和优化。下面是整理的 iOS 10 最新测试版的新变化。

[Android 7.0新功能：标注应用来源](http://3c.cqnews.net/html/2016-07/24/content_37787127.htm)

谷歌在近日正式放出了Android 7.0最终预览版。在该版本中，谷歌对应用程序的来源进行了更清晰的标注。在新的“App Info”页面中，谷歌为“App Details”下方添加了一行标注，在这里用户可以看到，该应用的来源究竟是Google Play商店还是第三方。此外，该功能还能识别出该应用是否是通过拷贝的APK安装而来。

## 教程

**iOS**

[Swift 3 最终版即将到来](https://lists.swift.org/pipermail/swift-evolution/Week-of-Mon-20160711/024424.html)

Swift 3 相对于 2 来说还是有非常多的破坏性改进，在 3.0 刚发布的时候，很多人发现升级之后第三方库各种不兼容，而某些第三方库迟迟不升到 Swift 3.x 版本，是因为担心后续还会引入破坏性更新。不过现在它们可以放心升级了，Swift 3 版本的开发接近尾声，特性均被冻结，可以放心使用。

[真实世界中的iOS Flux架构](http://blog.benjamin-encz.de/post/real-world-flux-ios/)

本文用一个真实项目为例说明如何在iOS项目里采用Flux架构，主要解决了哪些问题，以及遇到的坑，文章包括非常详尽的从MVC到Flux的迁移指南，如果你还不了解Flux架构，推荐阅读。

[Ziggurat iOS App Architecture](https://corner.squareup.com/2015/12/ziggurat-ios-app-architecture.html)

另一篇架构文章，不过写的粗略一些。受到React Native与Flux的启发，Square的iOS工程师们弄出了单方向数据流的iOS编程架构，用来解决MVC带来的各种麻烦。

**Android**

[Google I/O 2016笔记之Espresso 进阶](http://hlong.xyz/2016/07/20/Google%20IO%202016%20%E7%AC%94%E8%AE%B0%E4%B9%8BEspresso%20%E8%BF%9B%E9%98%B6/)

Espresso是Google官方提供的一个易于测试Android UI的开源框架，于2013年10月推出它的released版本，目前最新版本已更新到2.x . 并且在Android Studio 2.2预览版中已经默认集成该测试库。本文详细介绍了Espresso的使用方法。

[PathMeasure之迷径追踪](http://www.jianshu.com/p/3efa5341abcc)

Path不论是在自定义View还是动画，都占有举足轻重的地位。Android SDK提供了一个非常有用的API来帮助开发者实现这样一个Path路径点的坐标追踪，这个类就是PathMeasure。本文为我们详解了PathMeasure的相关知识。

[Android打包提速实践](http://www.jianshu.com/p/e456a5ac8613)

Apk打包是Android开发者们几乎每天都会做的事情。由于业务不断发展，Apk也变的越来越大，打包时间也变的越来越长。本文作者结合实践经验，提出了debug包和release包的打包提速的方案。阅读文章，看看作者是如何实现打包提速的。

[Android端应用秒开优化体验](http://zhengxiaoyong.me/2016/07/18/Android%E7%AB%AF%E5%BA%94%E7%94%A8%E7%A7%92%E5%BC%80%E4%BC%98%E5%8C%96%E4%BD%93%E9%AA%8C/)

作者近日遇到一个问题：应用启动很慢、卡图标。主要表现在中低端机型中。为了解决这个问题，文章作者借了个低端机和一个中端机来一看究竟，对同一应用分别测了下它在中低端机的启动时间，找到了启动慢、卡的原因所在，并且给出了解决方案。阅读文章，了解作者的启动速度优化方案。

## 开源项目

**iOS**

[EmojiTextView](https://github.com/fastred/EmojiTextView)

看过WWDC 2016的同学可能还记得在介绍新版iMessages时提到的一个特性，自动将文章转换为表情，这个开源项目实现了几乎相同的效果，并且可以用在大多数文本输入中。

[Wire](https://github.com/wireapp/)

这是一整套包括iOS、Android、Web端完整App的开源项目。Wire是一个加密的IM应用，现在它把客户端代码开源出来，如果有跨平台IM开发的需求，可以参考。

[PopupDialog](https://github.com/Orderella/PopupDialog)

一个简单易用、可自定义的弹出对话框控件，使用Swift编写。

**Android**

[ticker](https://github.com/robinhood/ticker)

ticker是一个带有滚动动画的TextView，非常适合于一些货币显示的场景。

[LogReport](https://github.com/wenmingvs/LogReport)

这是一个崩溃日志上传框架。当App崩溃的时，把崩溃信息保存到本地的同时，自动给GitHub提交崩溃issue，只需要几行代码，就能完成所有配置。另外，崩溃信息支持邮件上传和HTTP上传，自动提交到issue使用的是邮件上传的方式。如果你拥有私人服务器，你也可以使用HTTP上传。

[StatusBarCompat](https://github.com/niorgai/StatusBarCompat)

这是一个为了兼容处理状态栏的工具类,不需要设置不同的style.xml文件，最重要的特性就是可以在不重启Activity的情况下切换setStatusBarColor和translucentStatusBar。



## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

本周暂无新工作推荐。

## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[APMCon中国应用性能管理大会](http://www.bagevent.com/event/109881)

8月18日~19日在北京召开。聚焦于应用性能管理垂直领域的盛会。来自LinkedIn、AppDynamics、阿里巴巴、腾讯、京东、新浪、美团、360等国内外一线互联网公司的技术专家将给大家带来精彩的演讲分享！

----
