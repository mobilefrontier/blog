+++
title = "移动开发每周阅读清单：第二十四期"
date = "2016-08-15T21:33:45+08:00"
description = "Google 正在悄悄的开发一款全新的操作系统，命名为Fuchsia。为什么 Google 要开发一个全新的OS和kernel？最有可能的原因是，Google希望Fuchsia有一天能代替Chrome OS和Android，但也许Google也会像三星对待Tizen OS一样对待Fuchsia。但也有可能只是谷歌的一次尝试。"
tags = ""
+++


## 新闻

[库克任苹果CEO五周年专访：关于犯错、人工智能和手机市场](http://tech.sina.com.cn/it/2016-08-15/doc-ifxuxnak0256466.shtml)

蒂姆·库克（Tim Cook）担任苹果CEO即将满5周年，他近期接受了《华盛顿邮报》的专访。这篇文章简单的概括了专访都说了些啥。

[Google悄悄开发的全新操作系统 Fuchsia 被发现了！](http://osp.io/archives/2540)

Google 正在悄悄的开发一款全新的操作系统，命名为Fuchsia。为什么 Google 要开发一个全新的OS和kernel？最有可能的原因是，Google希望Fuchsia有一天能代替Chrome OS和Android，但也许Google也会像三星对待Tizen OS一样对待Fuchsia。但也有可能只是谷歌的一次尝试。

## 教程

**iOS**

[重识 Objective-C Runtime - Smalltalk 与 C 的融合](http://blog.sunnyxx.com/2016/08/13/reunderstanding-runtime-0/)

这是重识 Objective-C Runtime 系列文章的第一篇，作者曾在 2014 分享了一次 Runtime ，并出了几个题目，导致 Runtime 成了面试时的“必考题”，时隔多年，作者加深了对 Runtime 的理解，促成了这一系列的文章。

[写更优雅的 Swift 框架 - rx_tap -> rx.tap](http://blog.dianqk.org/2016/08/10/better-swifty-framework-namespace/)

作者在看到 [SnapKit Swift 3分支](https://github.com/SnapKit/SnapKit/tree/feature/0.40.0)的 API 从 `snp_makeConstraints` 到 `snp.makeConstraints` 的转变，产生了极大的兴趣。本文介绍了这种新 API 的优势及实现方案，本文还有一篇[续集](http://blog.dianqk.org/2016/08/11/better-swifty-framework-namespace-2/)。

[手把手教你给一个 iOS app 配置多个环境变量](http://www.jianshu.com/p/83b6e781eb51)

在项目中配置 Test 和 Release 等环境是件非常必要的事情。本文详细介绍了利用 Build Configuration 、xcconfig 、Targets 三种方案配置多环境。

**Android**

[Chrome Custom Tabs最佳实践](http://qq157755587.github.io/2016/08/12/custom-tabs-best-practices/)

距离Google发布Chrome Custom Tabs已经一年，Twitter、Medium等国外App早已支持了这个功能，但遗憾的是国内App鲜有支持。这篇文章以官方开发文档和示例源码为基础，加上自己的理解，希望能帮助读者快速掌握Chrome Custom Tabs的用法。

[Android 上的安全音量](https://yrom.net/blog/2016/08/06/one-little-tip-to-handle-safe-media-volume-level-on-android/)

当Android 设备插上耳机，为了避免音量过高伤害用户听力，会触发其“安全音量”(Safe Media Volume)机制，如果在未经用户确认允许使用大音量时，且这时设置音量newIndex超过其推荐阈值，却会发现毫无反应，播放的声音依然不会很大。那么需要如何解决该问题呢？本文给出了答案。

[Android开发之App启动时间统计](http://www.jianshu.com/p/c967653a9468)

作为Android开发者，想必多多少少要接触启动速度优化相关的事情，当用户越来越多，产品的功能也随着迭代越来越多，App逐渐变得臃肿是一件很常见的现象，甚至可以说是不可避免的现象，随之而来的工作就是优化App性能，其中最主要的一项就是启动速度优化。本文的主角并不是启动速度优化，而是启动时间统计。

## 开源项目

**iOS**

[SwiftyGif](https://github.com/kirualex/SwiftyGif)

高性能 Swift 引擎，在不限制内存情况下，CPU 占用远低于 FLAnimatedImage，限制内存下，性能略高于 FLAnimatedImage 。基于 UIImage 和 UIImageView 扩展，灵活易用。

[simplenote-ios](https://github.com/Automattic/simplenote-ios)

Automattic 开源了自家 Markdown 编辑软件 Simplenote 的 iOS 、Android 、macOS 等版本。

[PMJSON](https://github.com/Automattic/simplenote-ios)

纯 Swift JSON 解码编码框架，在编码上，性能略优于 NSJSONSerialization 。

[IBLocalizable](https://github.com/PiXeL16/IBLocalizable)

在 Storyboard 上支持本地化，特别是对于语言的支持，体验较差，IBLocalizable 提供了更简单的方式支持 View 的本地化，支持自定义视图本地化。

**Android**

[Onboarding](https://github.com/eoinfogarty/Onboarding)

这是一个效果非常赞的引导页。

[simplenote-android](https://github.com/Automattic/simplenote-android)

simplenote是一款笔记应用，现在simplenote开放了各个端的源码，推荐大家下载代码学习研究。

[android-adDialog](https://github.com/yipianfengye/android-adDialog)

这是一个简单且强大的广告活动弹窗控件，并且可以自定义多种场景。

[CameraFilter](https://github.com/nekocode/CameraFilter)

这是一个实时相机滤镜实现，提供了多种滤镜效果。





## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**Android/iOS工程师 by 北京优络时代科技**

地点北京。负责公司APP开发，APP叫YOLO，是一款朋友间的视频直播工具。要求具备较好的Android/iOS开发基础，有良好的工程素养。待遇15~30K。简历发送至 xujianlin@yoloyolo.tv

## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[APMCon中国应用性能管理大会](http://www.bagevent.com/event/109881)

8月18日~19日在北京召开。聚焦于应用性能管理垂直领域的盛会。来自LinkedIn、AppDynamics、阿里巴巴、腾讯、京东、新浪、美团、360等国内外一线互联网公司的技术专家将给大家带来精彩的演讲分享！

----
