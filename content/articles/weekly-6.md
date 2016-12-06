+++
title = "移动开发每周阅读清单：第六期"
date = "2016-04-04T21:33:45+08:00"
description = "『移动开发每周阅读清单』第六期与大家见面了，上周微软Build大会召开，我看了视频直播，HoloLens没有想象中那么惊艳，Bash On Windows倒是让人期待，移动平台并没有被特别提起，反而秀了好长一段时间Xbox One。看来我们暂时不用考虑第三个移动平台了。"
tags = ""
+++

​『移动开发每周阅读清单』第六期与大家见面了，上周微软Build大会召开，我看了视频直播，HoloLens没有想象中那么惊艳，Bash On Windows倒是让人期待，移动平台并没有被特别提起，反而秀了好长一段时间Xbox One。看来我们暂时不用考虑第三个移动平台了。

## 新闻

[Apple 公司于 4 月 1 日迎来 40 岁生日](http://www.macrumors.com/2016/04/01/apple-turns-40-history-timeline/)

1976 年 4 月 1 日，乔布斯和沃兹尼亚克在 Los Altos 乔布斯家的车库中创立了苹果公司。从 Apple I 和 Apple II 的成功开始，苹果公司经历了低谷和回归，并开创了个人电脑和移动互联网的时代。这篇新闻帮助我们回顾了苹果公司过去四十年的旅程。

[iOS 更新 9.3.1 修复 Safari 链接问题](http://www.forbes.com/sites/amitchowdhry/2016/03/31/apple-ios-9-3-1-released/#3b70622711a6)

iOS 9.3 于上周发布，为我们带来了 Night Shift 和备忘录 Touch ID 等改进。而不幸的是，很多用户发现了升级 iOS 9.3 后 Safari 和其他一些 app 中的 Universal Link 失效的问题，Apple 迅速做出了对应并发布了新的修正版本 iOS 9.3.1 来解决这个问题。

[Android侵权案甲骨文拟让谷歌赔偿93亿美元](http://tech.qq.com/a/20160329/006657.htm)

来自于甲骨文递交给法庭与本案相关的材料称，甲骨文当前起诉谷歌Android系统侵犯其专利权的新一轮官司将于5月9日开庭审理，而甲骨文打算说服陪审团，让谷歌向其支付93亿美元的侵权赔偿费用。

## 教程

**iOS**

[iOS冰与火之歌 – 利用XPC过App沙盒](http://drops.wooyun.org/papers/14170)

XPC 是 OS X 上进程间通讯的常用手段，而在 iOS 中虽然第三方开发者不允许直接使用 XPC，但是这项技术还是存在于 iOS 系统之中的，这篇文章简单介绍了在 iOS 上利用 XPC 与系统进程通讯并突破沙盒的技术要点。

[Breaking Swift with reference counted structs](http://www.cocoawithlove.com/blog/2016/03/27/on-delete.html)

Swift 是一门自动内存管理的语言，但是其背后机制其实还是引用计数。对于熟悉 Objective-C 的开发者来说，最大的区别在于 Swift 中对值类型的使用非常多，而值类型并不在堆上进行内存分配，自然也就没有引用计数的问题。但是如果你在值类型中包含持有了引用类型，背后将会发生一些隐式的复制和持有，将导致内存泄露。这篇文章举了一个这方面的例子，并进行了一些探索。

[Surprises with Swift Extensions](https://pspdfkit.com/blog/2016/surprises-with-swift-extensions/)

Swift 的 extension 为我们提供了非常多的方便，虽然 Swift 本身是以 module 的方式对不同框架的代码进行了隔离，但是向 UIKit 的类型添加 extension 时，我们仍然需要为其添加前缀。不过，使用 `@objc(prefix_name)` 可以在保持 Swift 代码名字优雅的前提下，只向 Objective-C 运行时暴露合适的方法名，不失为一种好方法。这篇文章讲述了一个调试的例子，并简单解释了 Swift Extension 的一些限制。

**Android**

[APK瘦身记，如何实现高达53%的压缩效果](http://jaq.alibaba.com/community/art/show?spm=a313e.7916642.24000001.22.iDleeI&articleid=219)

本文为大家分享了一种Apk瘦身的完整攻略，以一个完整的Android开源项目为例子，主要介绍了一个检测Android APK包大小的工具平台，实测效果非常棒。

[Android应用安全开发之浅谈加密算法的坑](http://jaq.alibaba.com/community/art/show?spm=a313e.7916642.24000001.23.9NdNpj&articleid=209)

Android开发中，难免会遇到需要加解密一些数据内容存到本地文件、或者通过网络传输到其他服务器和设备的问题，但并不是使用了加密就绝对安全了，如果加密函数使用不正确，加密数据很容易受到逆向破解攻击。还有很多开发者没有意识到的加密算法的问题。本文是一篇介绍加密算法的文章，内容全面且实用。

[Android消息循环机制源码分析](http://mp.weixin.qq.com/s?__biz=MzA5MTE1NTE5NQ==&mid=405322810&idx=1&sn=65d605b60aeb6d97924dc1f932838196#rd)

提到Handler，又是一个老生常谈的话题。本文是一篇介绍Handler实现原理的文章，作者结合源码，分析了Android消息循环机制。文章详细的介绍了一些关键类：HandlerThread、Handler、Looper、MessageQueue、Messaga等。

[App环境分离的实现:Android篇](https://mp.weixin.qq.com/s?__biz=MzA5OTI1NDE0Mw==&mid=404917977&idx=1&sn=130681ad4b0573b40df562ce096cb5e3)

环境分离对于很多Android开发的同学比较陌生，很少听这个概念。其实我们在日常的开发中经常会用到该技术，环境分离就是针对不同的开发或编译环境，提供不同的版本。比如在开发的过程中需要在调试模式下进行，而上线后需要切换到生产环境。如果手动来管理，很容易出错，所以我们需要借助Gradle来进行环境管理，本文就为我们详细介绍了环境分离的具体实现。

## 开源项目

**iOS**

[WKZombie](https://github.com/mkoehnke/WKZombie)

由 Swift 编写的一个无界面浏览器框架，它非常适合用来解析网页内容，并进行一些自动化操作。像是获取网页内容值，提交表单等等自然不在话下。如果你需要在应用中实现一些类似简单爬虫或者网页自动化的流程，或是为你的网站编写测试，那使用这个框架会让你事半功倍。

[Gifu](https://github.com/kaishin/Gifu)

一个轻量级的 GIF 动画框架，它采用了利用 CADisplayLink 绑定帧动画，并逐帧解析和加载的方式，来处理体积较大的 GIF 文件。如果你的应用中恰好有显示大 GIF 文件的需求，那这个框架会是一个可选项。

[UIImageColors](https://github.com/jathu/UIImageColors)

从一张 `UIImage` 图片中提取出主色调的框架。将 cell 的背景颜色设置为与其中图片的主色调一致的颜色来增强用户体验和区分不同 cell 的内容，是在 Apple 现在的 iTunes 应用上常见的表现手段。利用该框架，你可以简单地运用将这种设计手法进行设计，而且框架中还提供了一系列配套的辅助方法以帮助你简化构建这种高对比度 cell。

**Android**

[NavigationTabBar](https://github.com/DevLight-Mobile-Agency/NavigationTabBar)

NavigationTabBar是带指示器的Navigation tab bar，支持横屏、竖屏，滑动效果流畅，颜色搭配也很不错。

[welcome-coordinator](https://github.com/txusballesteros/welcome-coordinator)

这是一个能够帮助你快速创建引导页的库，当然也可以利用该库进行深度的自定义。

[Android-SpinKit](https://github.com/ybq/Android-SpinKit)

该项目实现了一系列加载动画，这些动画效果非常赞的。

----

上周移动开发前线公众号优秀文章：

* [Swift Runtime分析：还像OC Runtime一样吗？](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=403153173&idx=1&sn=c631f95b28a0eb4b842a9494e43a30e5#rd)
* [从案例学RxAndroid开发 （上、下）](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=403201730&idx=1&sn=d16caf0c0cefe4ed7a9e0463ef5d0b11#rd)
* [React-Native痛点解析之开发环境搭建及扩展](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=403225766&idx=1&sn=acd8e3ab7f234b97827c3e210c2d8673#rd)
* [微信Android客户端后台保活经验分享](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=403254393&idx=1&sn=8dc0e3a03031177777b5a5876cb210cc#rd)
* [移动时代的视频直播技术介绍](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=403289674&idx=1&sn=f4983ee5be06030c210851da6bcb6e3c#rd)
