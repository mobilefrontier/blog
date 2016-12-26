+++
date = "2016-12-26T23:07:47+08:00"
title = "移动开发每周阅读清单：第四十一期"
description = "在今年的 WWDC 大会，Apple 要求开发者于年底之前为提交至 App Store 中的应用启用 HTTPS ，以支持 iOS 9 引入的 ATS（App Transport Security）技术。但近日，apple 发布声明宣布延长这个时限，提供给开发者更多的时间进行相关准备。目前 Apple 尚未公布新的截止日期。"
+++


## 新闻

[Apple 延长 App 接入 HTTPS 期限](https://developer.apple.com/news/?id=12212016b&1482372961)

在今年的 WWDC 大会，Apple 要求开发者于年底之前为提交至 App Store 中的应用启用 HTTPS ，以支持 iOS 9 引入的 ATS（App Transport Security）技术。但近日，apple 发布声明宣布延长这个时限，提供给开发者更多的时间进行相关准备。目前 Apple 尚未公布新的截止日期。

[CM社区官网已被禁止访问](http://www.ithome.com/html/android/283379.htm)

作为一家野心勃勃的创业公司，Cyanogen曾经希望开发一款比谷歌官方版本更好的Android系统，但该公司最近几个月却经历了动荡。他们不仅裁员，而且辞退了CEO，还有一位联合创始人离职。12月23日，圣诞节到来之前，Cyanogen公司在官网宣布，将在2016年12月31日关闭被Cyanogen所支持的所有服务，其中包括CyanogenMod系统，也就是我们所熟知的CM系统。


## 教程

**iOS**

[上海 T 沙龙 Slide](https://github.com/Code-T/salon-resources/tree/master/%E4%B8%8A%E6%B5%B7%202016:12:18)

沙龙分享了MVVM + RAC + Command 架构实战、基于 RAC 实现的 MVVM 框架 LPDMVVMKit和面向数据流的网络请求与数据解析三个主题。回放地址：[上海 T 沙龙12月-FRP 函数响应式编程](http://www.bilibili.com/video/av7644194/)

[写给 iOS 开发者看的 HTTPS 指南](https://autolayout.club/2016/12/22/%E5%86%99%E7%BB%99-iOS-%E5%BC%80%E5%8F%91%E8%80%85%E7%9C%8B%E7%9A%84-HTTPS-%E6%8C%87%E5%8D%97/)

不管怎样我们还是要适配HTTPS，本文将着重以大部分 iOS 开发者能理解的方式介绍 APP 启用 HTTPS 支持的过程中跟 APP 相关的部分。

[Swift 并行编程现状和展望 - async/await 和参与者模式](https://onevcat.com/2016/12/concurrency/)

距离适配完 Swift 3 可能已经过去 1 个月了，而本文作者对 2018 年发布的 Swift 5 的一些特性进行了猜想。特别是对大家可能都在期待的特性 async/await 。

[iOS书写高质量代码之耦合的处理](http://mp.weixin.qq.com/s/nP7UmlbCHeGJ9aCnTDsIHg)

耦合是每个程序员都必须面对的话题，也是容易被忽视的存在，怎么处理耦合关系到我们最后的代码质量。本文介绍了 iOS 代码中处理耦合的种种方式及差异。


[ReactiveCocoa 中集合类 RACSequence 和 RACTuple 底层实现分析](https://halfrost.com/reactivecocoa_racsequence_ractuple/)

在OOP的世界里使用FRP的思想来编程，光有函数这种一等公民，还是无法满足我们一些需求的。本文专门分析了 RAC 中 RACSequence 的底层实现。相信了解了底层实现会在使用 RAC 时更加得心应手。


**Android**

[Android Auto开发初探](http://mp.weixin.qq.com/s?__biz=MzI1NjEwMTM4OA==&mid=2651232299&idx=1&sn=113a97ad70e23c5dc110cbfc0d345982)

谷歌于2014年6月推出了Android Auto系统。它是谷歌生态系统的一个重要终端。说它是个系统其实并不完全准确，因为谷歌并没有提供完整的操作系统，而是提供了一套Android Auto SDK给汽车厂商。汽车厂商需要把这套Android Auto SDK集成到他们自己的车载操作系统中。

[上个版本我就改了一行代码！](http://mp.weixin.qq.com/s?__biz=MzAxNzMxNzk5OQ==&mid=2649485010&idx=1&sn=89e7d2c68080b66adaef1eb74f1190b9)

App的启动图标（icon）是程序在发版的时候直接打到Apk里的，但由于业务的需求，有时候我们需要修改icon图标。如果仅仅为了一个图标而去发一个新版，再提交到几十个市场，似乎有点小题大做。本文给出了一种动态替换icon的方案，完美实现了产品经理换icon的需求。

[Android性能监控实现原理](http://www.jianshu.com/p/9c07323dc7e5?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io)

APM即应用程序性能管理。APM主要做的事情是crash监控，卡顿监控，内存监控，增加trace，网络性能监控，app页面自动埋点等。性能监控其实就是hook 代码到项目代码中，从而做到各种监控。常规手段都是在项目中增加代码，但最好的办法是做到非侵入式的，即一个sdk即可。阅读文章，了解性能监控的实现原理。

[Tangram——天猫导购页面动态化方案与实践](http://pingguohe.net/2016/12/20/Tangram-design-and-practice.html)

Tangram中文名是七巧板的意思，我们希望这个框架提供一系列基本单元，就像积木块一样，通过快速拼装就能搭建出一个页面或者调整页面的结构。重运营的业务特别是电商业务，往往讲究灵活多变，需要对线上业务做实时调整，此类页面动态化的需求便应运而生。天猫团队再本月的SFDC大会上初次介绍了手机天猫的Tangram方案，本文是Tangram的整体介绍与相关业务开发实践的介绍。


## 开源项目

**iOS**

[iOS-Awesome-Starter-Kit](https://github.com/NghiaTranUIT/iOS-Awesome-Starter-Kit)

结合ReSwift和PromiseKit的初始工程。

[EasyTipView](https://github.com/nitishmakhija/EasyTipView)

友好地对用户展示操作提示库。

[NEKit](https://github.com/zhuhaow/NEKit)

Network Extension 封装的工具库。


**Android**

[DanmukuLight](https://github.com/hpdx/DanmukuLight)

Android上专为视频直播打造的轻量级弹幕库（100多kb）。

[AvatarLabelView](https://github.com/yanbober/AvatarLabelView)

一个可配置的迷你版轻量级 Label辅助类，支持多种配置效果。

[WowSplash](https://github.com/githubwing/WowSplash)

云扩散融合效果，作者的实现思路堪称完美。

## 工作

> 有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**iOS/Android/前端高级工程师 by 新美大平台部门大前端**

坐标北京。维护美团App平台架构/业务，以及移动端和前端基础设施。高级工程师要求有一定的技术规划选型能力。薪资与BAT对标。简历发送至 radishchrist@gmail.com

## 活动

> 宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[QCon北京站2017](http://2017.qconbeijing.com/)

2017年4月16日北京举行。明年第一场最值得期待的综合性技术大会。QCon内容源于实践并面向社区，演讲嘉宾依据热点话题，面向5年以上工作经验的技术团队负责人、架构师、工程总监、高级开发人员分享技术创新和最佳实践。

[WeexConf 2017](https://atf.alibaba.com/weex)

2017年1月12日杭州举行。这次WeexConf我们将和业界分享以下亮点：Weex最新的技术特性、技术工具、技术能力、技术趋势发布； Weex两次历经双11大考的实战经验及阿里生态系的业务经验； Weex团队更将首次集体亮相，畅谈从开源到加入Apache的心路历程。 