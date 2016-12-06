+++
title = "移动开发每周阅读清单：第二十六期"
date = "2016-08-30T21:33:45+08:00"
description = "有消息称 iOS 9 上存在严重系统漏洞，目前已有间谍软件入侵中东地区政见者的 iPhone ，此次的安全漏洞，仅适用一条短信中的链接即可远程越狱入侵。"
tags = ""
+++


## 新闻

[Apple 推送 iOS 9.3.5 ，修复严重安全漏洞](http://appleinsider.com/articles/16/08/25/dangerous-targeted-iphone-attack-nullified-by-apple-with-ios-935-patch)

有消息称 iOS 9 上存在严重系统漏洞，目前已有间谍软件入侵中东地区政见者的 iPhone ，此次的安全漏洞，仅适用一条短信中的链接即可远程越狱入侵。

[谷歌将放出安卓7.1/7.1.1/7.1.2季度更新](http://www.ithome.com/html/android/253064.htm)

现在爆料大神evleaks给出消息称，谷歌接下来会推出安卓7.1/7.1.1/7.1.2三个维护更新，这也跟之前的传闻相吻合，并且此前一份网页访问记录也曝出过安卓7.1.1和安卓7.1.2的版本。目前安卓7.0还有多项功能缺失，例如视频通话应用Allo、VR平台DayDream和谷歌助手等，估计这些功能会在后续的维护更新中添加。

## 教程

**iOS**

[微信读书排版引擎自动化测试方案](http://wereadteam.github.io/2016/08/23/Typesetter/)

在微信读书 App 中，排版引擎是最常用、最复杂的组件之一。对排版引擎代码变更的测试，往往耗时多、难度大、容易漏测。本文介绍了为解决测试的难题，如何逐步将人工测试步骤自动化，最终构建了一套微信读书排版引擎自动化测试流程，以确保微信读书排版引擎的质量。

[Auto Layout 设计美学](http://blog.callmewhy.com/2016/08/24/autolayout-design-aesthetic/)

本文介绍了设计稿与 Auto Layout 的关系，分享了作者的一些 Auto Layout 最佳实践，即分享了如何将设计稿中的像素，转化为开发稿中的约束。

[在 Swift 中安全的使用下标访问 Collection 数据](https://medium.com/@JegnuX/safe-collection-subsripting-in-swift-3771f16f883#.mlv1ukkgv)

作者分享了一种比使用 `numbers[safe: 2]` 更合理、更优雅的下标访问写法，即 `numbers.safe[2]` 。

**Android**

[Android动态布局入门及NinePatchChunk解密](https://mp.weixin.qq.com/s?__biz=MzI1NjEwMTM4OA==&mid=2651232105&idx=1&sn=fcc4fa956f329f839f2a04793e7dd3b9&scene=0)

使用XML定义布局的方式，有着结构清晰、可预览等优势，因而极为通用。可是，偏偏在某些场景下，布局是需要根据运行时的状态变化的，无法使用XML预先定义。这时候，我们只能通过JavaCode控制，在程序运行时，动态的实现对应的布局。本文给大家介绍了一些动态布局相关的基础知识和经验。

[轻听变色之谜](https://mp.weixin.qq.com/s?__biz=MzI1NjEwMTM4OA==&mid=2651232087&idx=1&sn=c8cd60ccc3b220759b44c5b951ae3cfb&scene=0)

轻听是一款小而美的Android本地音乐播放器，而它的特点之一就是拥有多彩的外衣。轻听实现变色主要是结合两种方式：自定义Style、Theme与动态配置主题色。本文为我们详细讲解了轻听变色的实现过程。

[Android动态链接库加载原理及HotFix方案介绍](http://mp.weixin.qq.com/s?__biz=MzA3NTYzODYzMg==&mid=2653577702&idx=1&sn=1288c77cd8fc2db68dc92cf18d675ace&scene=4#wechat_redirect)

随着项目中动态链接库越来越多，作者遇到了很多奇怪的问题，比如只在某一种OS上会出现的java.lang.UnsatisfiedLinkError，但是明明动态库名称没错，ABI也没错，方法也能对应的上，而且还只出现在某一些机型上。为了找到出现千奇百怪问题的原因，和能够提供一个方式来解决一些比较奇怪的动态库加载的问题，了解一下so的加载流程是非常有必要的了，便于发现问题和解决问题，这就是本文的由来。



## 开源项目

**iOS**

[SwiftTimer](https://github.com/100mango/SwiftTimer)

基于 Swift3 与 DiapatchSource 实现的 Timer 框架。优雅简洁地解决了 NSTimer 引用循环，Runloop 依赖，线程切换，不支持闭包以及不能动态调整时间间隔的问题。

[AImage](https://github.com/wangjwchn/AImage)

一个 GIF 和 APNG 的 iOS 动画引擎 Swift 框架。特别为多图情况进行了优化。GIF 渲染性能优于 [FLAnimatedImage](https://github.com/Flipboard/FLAnimatedImage)，尤其体现于多图情况。APNG 渲染在内存占用上低于 [APNGKit](https://github.com/onevcat/APNGKit) 一半。

[ChatKit-OC](https://github.com/leancloud/ChatKit-OC)

ChatKit 是一个免费且开源的 UI 聊天组件，自带云服务器，自带推送，支持消息漫游，消息永久存储。底层聊天服务基于 LeanCloud（原名 AVOS ） 的 IM 实时通信服务「LeanMessage」而开发，采用 Protobuf 协议进行消息传输。ChatKit 可以帮助开发者快速集成 IM 服务，轻松实现聊天功能，提供完全自由的授权协议，支持二次开发。


**Android**

[awesome-adb](https://github.com/mzlogin/awesome-adb)

ADB，即Android Debug Bridge，它是Android开发/测试人员不可替代的强大工具，也是Android设备玩家的好玩具。持续更新中，欢迎补充指正，觉得有用的可以将 此GitHub仓库Star收藏备用。有部分命令的支持情况可能与Android系统版本及定制ROM的实现有关。

[Amigo](https://github.com/eleme/Amigo)

这是一款hotfix开源库，使用方法非常简单。

[FastBle](https://github.com/Jasonchenlijian/FastBle)

Android BLE 蓝牙开发框架，使用回调方式处理，搜索、连接、notify、indicate、读、写等一系列蓝牙操作。

[StyleImageView](https://github.com/chengdazhi/StyleImageView)

本类库可以对ImageView，View Background，Drawable和Bitmap添加风格与设置亮度、对比度。本类库现提供十种风格。

## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

本周暂无工作推荐，可查看上几期推荐的职位。

## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[蚂蚁金服&阿里云在线金融技术峰会](http://click.aliyun.com/m/5653/)

蚂蚁金服&阿里云在线金融技术峰会将于8月30日-31日在线举办。8位蚂蚁金服和阿里云技术大V，将从蚂蚁无线技术、大规模机器学习、金融领域大数据创新、云数据库OceanBase、蚂蚁开放平台等维度，分享蚂蚁从FinTech到FinLife的技术探索思考，展现技术在互联网及金融领域的创新实践应用。蚂蚁开放平台技术路线将首度公开，希望构建更加开放和共享的技术生态。免费参与。


----
