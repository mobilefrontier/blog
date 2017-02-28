+++
date = "2017-02-23T21:07:47+08:00"
title = "移动开发每周阅读清单：第四十六期"
description = "Apple 正式宣布，Apple 总部的名字为 Apple Park，并将于 4 月开始有员工入驻。公司超过 12,000 名员工将用超过 6 个月的时间搬入，公司大楼和公园的建设将一直持续到夏季。"
+++


## 新闻

[Apple Park 4 月对员工开放](http://www.apple.com/cn/pr/library/2017/02/22Apple-Park-Opens-to-Employees-in-April.html)

Apple 正式宣布，Apple 总部的名字为 Apple Park，并将于 4 月开始有员工入驻。公司超过 12,000 名员工将用超过 6 个月的时间搬入，公司大楼和公园的建设将一直持续到夏季。

[折腾了十年安卓版的“iMessage”终于诞生](http://www.leiphone.com/news/201702/5lwZHiAYgGsIeDWR.html)

近日，谷歌Play商店上线了 “Android Messages”，中文名“Android信息”。明眼人一瞧就知道这是干什么的。没错，它正是谷歌效仿苹果在iOS上推出iMessage的做法，开发的安卓平台御用短信软件。

## 教程

**iOS**

[没想到 Swift 里 KVC 还能有坑](http://www.jianshu.com/p/196e3bfcf95e)

因为 Swift API 的变动，Swift 团队在 KVC 和 KVO 留下了一些你需要注意坑。本文介绍了存在一个坑，以及对应的解决方案。

[iOS 组件化 —— 路由设计思路分析](http://www.jianshu.com/p/76da56b3bd55)

长文，随着项目的开发，复杂度也随之增加，我们可能会考虑做一些组件化的事情。尽管这样做了以后会让开发更加有效率，更加好维护，但是如何解耦各层，解耦各个界面和各个组件，降低各个组件之间的耦合度，如何能让整个系统不管多么复杂的情况下都能保持“高内聚，低耦合”的特点？这一系列的问题都摆在开发人员面前，亟待解决。本文阐述了相应问题的一些解决方案。

[谈谈 iOS 中图片的解压缩](http://blog.leichunfeng.com/blog/2017/02/20/talking-about-the-decompression-of-the-image-in-ios/#jtss-tsina)

本文介绍了 iOS 中图片的解压缩的原理，介绍了位图的概念。而图片解压缩的过程其实就是将图片的二进制数据转换成像素数据的过程。了解这些知识，将有助于我们更好地处理图片，管理好它们所占用的内存。

[Clang Plugin--Sherlock](http://blog.mrriddler.com/2017/02/24/Clang%E6%8F%92%E4%BB%B6-Sherlock/)

本文介绍了一些 Clang 插件相关的内容，你可以结合本文对自己项目进行一些类似 Lint 的操作。

[所有权宣言 - Swift 官方文章 Ownership Manifesto 译文评注版](https://onevcat.com/2017/02/ownership/)

长文，Swift 团队最近在邮件列表里向社区发了一封邮件，讲述了关于内存所有权方面的一些未来的改变方向。作为上层 API 的使用者来说，我们可能并不需要了解背后所有的事实，但是 Apple 的这封邮件中对 Swift 的值和对象的内存管理进行了很全面的表述，一步步说明了前因后果。如果你想深入学习和了解 Swift 的话，建议阅读本文。你可以在这里阅读[原文](https://github.com/apple/swift/blob/master/docs/OwnershipManifesto.md)。

**Android**

[Android权限机制与适配经验](http://mp.weixin.qq.com/s?__biz=MzI1NjEwMTM4OA==&mid=2651232379&idx=1&sn=b606cea54aafdcce30972cec62df45f0)

Android M已经发布一段时间了，市面上很多应用都已经适配Android M。权限机制，作为Android M的一大特性，受到了很多开发者的关注。本文主要分享了以下几个知识点的内容，1、Android权限机制关键知识点；2、QQ音乐对于权限的适配经验；3、近段时间以来遇到的一些Android权限方面的问题。

[手机淘宝：亿级用户APP的快速运维交付实践](http://mp.weixin.qq.com/s?__biz=MzAxNDEwNjk5OQ==&mid=2650400312&idx=1&sn=ce8468991c70ab2e06634f59cd2b6865)

很少有公司会有App运维这个岗位，移动客户端运维这块，大部分公司应该都是研发工程师自己在做。不过像阿里这样几乎每天都有版本迭代的公司，App运维是很必要。本文作者比较关注移动化运维的事情，文章围绕手淘APP的运维交付实践进行了详细介绍。

[深度了解Android 7.0 ，你准备好了吗？](http://mp.weixin.qq.com/s/8Nouh0ZZklqjxfachhoA-g)

2016年8月22日，谷歌正式推送Android 7.0 Nougat（牛轧糖）正式版，首发推送了多款Nexus设备。除了修复常规BUG，Android 7.0还新增了分屏、新的Notification、VR支持等新特性。本文对Android 7.0的新特性进行了详解说明。

[Google VR for Android敲门](http://www.jianshu.com/p/7867fe980fb4)

虚拟现实（Virtual Reality）技术是一种可以创建和体验虚拟世界的计算机仿真系统，最近几年虚拟现实概念很火，技术上也有很多突破。Google、苹果等顶级互联网公司都进行了大手笔的投入。本文是一篇介绍如何在Android手机上运行、开发VR程序的基础教程。


## 开源项目

**iOS**

[TodayMind](https://github.com/cyanzhong/TodayMind)

在通知中心管理提醒事项 App 。

[NextLevel](https://github.com/NextLevel/NextLevel)

功能丰富的相机组件。

[EasyTipView](https://github.com/teodorpatras/EasyTipView)

Tip 组件，可以为你的用户友好地展示使用提示。

[Typist](https://github.com/totocaster/Typist)

简单轻量的键盘管理工具。

[Motion](https://github.com/CosmicMind/Motion)

无缝动画转场组件，你可以将其用在图库展示中。


**Android**

[ThinRPlugin](https://github.com/meili/ThinRPlugin)

hinR插件在编译时将除R$styleable.class以外的所有R.class删除掉，并且在引用的地方替换成对应的常量，从而达到缩减包大小和减少dex个数的效果。该插件已经在蘑菇街app上使用，将包大小降低1mb（原包大小40mb）,dex数量减少3个。

[Aceso](https://github.com/meili/Aceso)

Aceso是基于Instant Run Hot Swap的Android热修复方案，使用它你能在不用重新发布版本的情况下对线上app的bug进行修复。

[Android-skin-support](https://github.com/ximsfei/Android-skin-support)

一款Android换肤框架，极低的学习成本， 极好的用户体验。只需要两行代码，就可以实现换肤。

[Shuttle](https://github.com/timusus/Shuttle)

这是一款开源的本地音乐播放器。

## 工作

> 有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**iOS/Android高级开发工程师 by 爱奇艺**

上海徐汇 / 三年以上工作经验 / 工作稳定踏实 / 可给出业内有竞争力的薪资。简历发送至 jinkai@qiyi.com

**中高级Android/iOS开发工程师 by 小红书**

坐标上海。负责参加小红书主App开发。要求三年以上相关经验，有App优化实践经验，有一定框架和架构开发经验。简历至：fzhang@xiaohongshu.com

**iOS/Android/前端高级工程师 by 新美大平台部门大前端**

坐标北京。维护美团App平台架构/业务，以及移动端和前端基础设施。高级工程师要求有一定的技术规划选型能力。薪资与BAT对标。简历发送至 luozexiang@meituan.com

## 活动


> 宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[GMTC 2017全球移动技术大会](http://gmtc.geekbang.org/?utm_source=infoq&utm_campaign=bornmobile&utm_medium=wechat)

6月9日北京举行。关注移动、前端、跨平台、AI应用等多个技术领域、促进全球技术交流，推动国内技术升级。GMTC为期两天，面向移动开发、前端、AI技术人员，聚焦前沿技术及实践经验，打造技术人员的学习和交流平台。

[QCon北京站2017](http://2017.qconbeijing.com/)

2017年4月16日北京举行。明年第一场最值得期待的综合性技术大会。QCon内容源于实践并面向社区，演讲嘉宾依据热点话题，面向5年以上工作经验的技术团队负责人、架构师、工程总监、高级开发人员分享技术创新和最佳实践。