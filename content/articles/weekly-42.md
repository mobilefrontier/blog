+++
date = "2017-01-10T23:07:47+08:00"
title = "移动开发每周阅读清单：第四十二期"
description = "Apple 发布的最新统计数据表明，截止 2017 年 1 月 4 日，iOS 10 在 iPhone、iPad 和 iPod Touch 等设备上的安装覆盖率达到了 76%，而 iOS 9 的覆盖率已不足两成。数据主要收集渠道是 App Store，相对比较保守。"
+++


## 新闻

[iOS 10 设备安装率达 76%](https://9to5mac.com/2017/01/05/ios-10-now-installed-on-76-of-active-devices-according-to-apples-stats/)

Apple 发布的最新统计数据表明，截止 2017 年 1 月 4 日，iOS 10 在 iPhone、iPad 和 iPod Touch 等设备上的安装覆盖率达到了 76%，而 iOS 9 的覆盖率已不足两成。数据主要收集渠道是 App Store，相对比较保守。

[Google提供Fastboot和ADB单独下载服务](http://www.cnbeta.com/articles/574639.htm)

在许多Android用户多次呼吁之后，Google终于将ADB和Fastboot作为单独的文件提供给用户下载。以前这些文件只包含在大尺寸的Android SDK或Android Studio当中提供给用户，现在这种变化意味着它们现在比以往更快，更容易执行和侧载。

## 教程

**iOS**

[深入理解 CVPixelBufferRef](https://zhuanlan.zhihu.com/p/24762605)

在 iOS 开发中，接触到相机相关的需求时，我们可能会看到 CVPixelBufferRef 这个类型。本文详细地解释了 CVPixelBufferRef 的含义与使用。

[细聊 Cocoapods 与 Xcode 工程配置](http://www.jianshu.com/p/ad2e37e741bb)

通常在开发时，我们都会用到 CocoaPods ，除了知道如何使用 CocoaPods ，我们还应该知道 CocoaPods 的基本工作原理，本文介绍了 CocoaPods 管理依赖的基本原理。

[Swift: UIView Animation Syntax Sugar](https://medium.com/swift-programming/swift-uiview-animation-syntax-sugar-d40448fe1fed#.c6ngys70q)

本文作者在处理动画时认为 Swift 中的 API 不够优雅，在本文中作者给出了一种比较有趣的链式写法，你可以从中应用到更多的场景。


**Android**

[Input系统—ANR原理分析](http://gityuan.com/2017/01/01/input-anr/)

当input事件处理得慢就会触发ANR，那ANR内部原理是什么，哪些场景会产生ANR呢。“工欲善其事必先利其器”，为了理解input ANR原理，作者通已经写过几篇文章疏通了整个input框架的处理流程，前期的文章都是为了这篇而做铺垫。阅读文章，了解ANR触发原理以及触发场景。

[Android上如何实现矩形区域截屏](http://www.jianshu.com/p/0462dae4c808)

对屏幕进行截屏并裁剪有两种方式：早截图和晚截图。早截图，就是先截取全屏，再让用户对截取到的图片进行修改；与之相对的，晚截图，就是先让用户在屏幕上划好区域，再进行截图和裁剪。其实两者并没有什么太大的区别，本文详细介绍了实现晚截图的方法。

[Android性能优化：使用Lint优化代码、去除多余资源](http://blog.csdn.net/u011240877/article/details/54141714)

Lint是Android Studio提供的代码扫描分析工具，它可以帮助我们发现代码结构和质量问题，同时提供一些解决方案，而且这个过程不需要我们手写测试用例。Lint会根据预先配置的检测标准检查Android项目的源文件，发现潜在的bug或者可以优化的地方。Lint就像是一个洁癖患者，虽然可以让我们代码干净许多，但是如果真要把它提示的全解决，恐怕需要很大的工作量。通过本文，大家能够更加了解Lint的工作方式及其使用方法。

[一种视频预加载的方案](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247484431&idx=1&sn=7f49fd46cd4e03600e5706432f31e59b)

视频的预加载是提高用户体验的重要因素。预加载成为网络视频播放不可或缺的一个技术环节。预加载的形式有：边存边播和代理服务器预下载。两者各有优缺点，本文就预加载技术进行了详细的介绍，对做视频开发的同学会有帮助。

## 开源项目

**iOS**

[LocalizationKit_iOS](https://github.com/willpowell8/LocalizationKit_iOS)

iOS本地化组件，支持动态更新文案。

[MBNetwork](https://github.com/mmoaay/MBNetwork)

基于 Alamofire 封装的网络请求库，可以更方便地在视图上展示请求状态。

[STLoadingGroup](https://github.com/saitjr/STLoadingGroup)

参考 Dribbble 上设计的一些加载动画控件。

[Sourcery](https://github.com/krzysztofzablocki/Sourcery)

使用 Swift 进行元编程工具。


**Android**

[AnimShopButton](https://github.com/mcxtzhang/AnimShopButton)

这是一个仿饿了么、带伸缩位移旋转动画的购物车按钮。本控件并非继承自ViewGroup,而是纯自定义View。

[Store](https://github.com/NYTimes/Store)

Store 是一个Android库异步数据加载和缓存框架。

[android-animated-menu-items](https://github.com/adonixis/android-animated-menu-items)

该项目实现了在toolbar中显示带动画的菜单按钮。

## 工作

> 有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**iOS/Android/前端高级工程师 by 新美大平台部门大前端**

坐标北京。维护美团App平台架构/业务，以及移动端和前端基础设施。高级工程师要求有一定的技术规划选型能力。薪资与BAT对标。简历发送至 luozexiang@meituan.com

## 活动

> 宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[QCon北京站2017](http://2017.qconbeijing.com/)

2017年4月16日北京举行。明年第一场最值得期待的综合性技术大会。QCon内容源于实践并面向社区，演讲嘉宾依据热点话题，面向5年以上工作经验的技术团队负责人、架构师、工程总监、高级开发人员分享技术创新和最佳实践。

[WeexConf 2017](https://atf.alibaba.com/weex)

2017年1月12日杭州举行。这次WeexConf我们将和业界分享以下亮点：Weex最新的技术特性、技术工具、技术能力、技术趋势发布； Weex两次历经双11大考的实战经验及阿里生态系的业务经验； Weex团队更将首次集体亮相，畅谈从开源到加入Apache的心路历程。 