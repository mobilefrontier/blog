+++
date = "2017-02-15T21:07:47+08:00"
title = "移动开发每周阅读清单：第四十四期"
description = "苹果认为AR(增强现实)将会成为下一一项重大技术,到底AR市场有多大?是不是和iPhone一样大?之前,苹果CEO库克曾经表示公司对AR有兴趣……"
+++


## 新闻

[苹果CEO库克：AR影响力将会和iPhone一样巨大](http://tech.sina.com.cn/it/2017-02-13/doc-ifyamkzq1263806.shtml)

苹果认为AR(增强现实)将会成为下一一项重大技术,到底AR市场有多大?是不是和iPhone一样大?之前,苹果CEO库克曾经表示公司对AR有兴趣……

[Google手机操作系统二月份统计数据：牛轧糖份额首度超过1%](https://view.inews.qq.com/a/TEC2017020700552607)

Google手机操作系统二月份统计数已经出炉，这个月的数字显示最新的Android操作系统份额终于突破1%。这些数字显示，牛轧糖7.1的份额为0.3%，牛轧糖7.0的份额为0.9%。牛轧糖7.0二月份份额比一月份提升0.4%，牛轧糖7.1的份额提升0.1%，两个牛轧糖版本现在合并份额为1.2%，比上个月增加0.5%。

## 教程

**iOS**

[iOS 10 不提示「是否允许应用访问数据」，导致应用无法使用的解决方案](http://www.jianshu.com/p/28e8919a2cae)

由于大陆相关部门出台的新规定指出，应用在未经用户允许的前提下，系统不能授予其使用联网、获取定位的功能。Apple 在 iOS 10 操作系统中加入了关于应用使用数据的授权弹窗提示，用户在 iOS 10 系统中第一次打开应用时，会被要求对于是否授予应用联网权限进行选择。不过，新的权限系统的引入也带来了一个 iOS 10 的新 bug。本文给出了对应的解决方案，你也可以采取类似的方案提示用户解决该问题。

[ReactiveCocoa 中 奇妙无比的“宏”魔法](http://www.jianshu.com/p/4c5613e256c8)

在ReactiveCocoa 中，开源库作者为我们提供了很多种魔法，“黑”魔法，“红”魔法……本文介绍其中的“红”魔法，即“宏”。

[谈谈 GIF 格式](https://zhuanlan.zhihu.com/p/22590949)

长期以来，iOS 被 Android 歧视的一个点就是不支持 GIF，甚至每一代 iPhone 推出都要有人谣传这一代 iPhone 要支持 GIF 了。事实上，只是 iOS 平台的照片应用，不支持播放 GIF 。本文介绍了作者应用 GIF 一些相关经验及如何在剪贴板里面获取 GIF 文件，以及把 GIF 放进剪贴板。



**Android**

[Android架构思考(模块化、多进程)](http://blog.spinytech.com/2016/12/28/android_modularization/)

关于模块化(组件化)这个问题，大部分开发者可能都认真的思考过。随着项目的开发，业务不断壮大，业务模块越来越多，各个模块间相互引用，耦合越来越严重，同时有些项目还伴随着子应用单独包装推广，影子应用单独发布等等需求，重新调整架构迫在眉睫。作者介绍了自己公司项目的演进过程，文章写的很详细，架构也很实用，对大家合理架构项目很有帮助，强烈推荐大家阅读。

[深入剖析Android中的ArrayMap](http://droidyue.com/blog/2017/02/12/dive-into-arraymap-in-android)

数据集合在任何一门编程语言中都是很重要的一部分，在Android开发中，我们会实用到ArrayList，LinkedList，HashMap等。其中HashMap是用来处理键值对需求的常用集合。而Android中引入了一个新的集合，叫做ArrayMap，为键值对存储需求增加了一种选择。本文深度剖析了ArrayMap的实现原理。

[混淆的另一重境界](http://mp.weixin.qq.com/s/rpDFA-h5t2RA9Dih3gVqVA)

众所周知，我们开混淆打包后生成的apk里，Activity、自定义View、Service等出现在xml里的相关Java类默认都会被keep住，那么这对于app的保护是不足够好的，Mess就是来解决这个问题，把即使出现在xml文件中的Java类照样混淆。本文详细介绍了Mess的使用方法。

[教你一步步搭建MVP+Retrofit+RxJava网络请求框架](http://www.jianshu.com/p/7b839b7c5884)

MVP（Model View Presenter）其实就是一种项目的整体框架，能让你的代码变得更加简洁，说起框架大家可能还会想到MVC、MVVM。Retrofit是一个类型安全的用于Android和Java网络请求的客户端，其实就是一个封装好的网络请求库。本文作者详细介绍了如何使用MVP+Retrofit+RXJava的技术方案来搭建Android基础开发框架。


## 开源项目

**iOS**

[Interstellar](https://github.com/JensRavens/Interstellar)

一款简单轻量的函数响应式库，基于Swift。

[AnimatedCollectionViewLayout](https://github.com/KelvinJin/AnimatedCollectionViewLayout)

支持自定义转场动画组件。

[IBAnalyzer](https://github.com/fastred/IBAnalyzer)

IB 分析工具，可以方便地查找到未关联的 IBOutlet 和 IBAction

[XLActionController](https://github.com/xmartlabs/XLActionController)

样式丰富的 Action Sheet 组件。


**Android**

[LQRWeChat](https://github.com/GitLqr/LQRWeChat)

本项目高仿微信6.3.31，使用网易云信SDK 3.2.0版本完成主要的聊天功能（单聊、群聊）、好友关系管理、群组管理等功能。重要的是，作者还是一名在校学生。

[ListenerMusicPlayer](https://github.com/hefuyicoder/ListenerMusicPlayer)

一款优雅的遵循Material Design的开源音乐播放器，UI参考腾讯轻听音乐播放器,使用Lastfm Api与酷狗歌词Api。项目架构采用mvp-clean，基于Retrofit2 + Dagger2 + Rxjava + RxBus + Glide。

[SopCastComponent](https://github.com/LaiFeng-Android/SopCastComponent)

这是一个由纯java编写的项目。整个项目完成了采集、视音频处理、编码、数据发送前处理、数据发送的功能。整个项目支持flv封包，rtmp上传，当然也向外面提供了封包和上传的相关接口。

## 工作

> 有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**iOS/Android/前端高级工程师 by 新美大平台部门大前端**

坐标北京。维护美团App平台架构/业务，以及移动端和前端基础设施。高级工程师要求有一定的技术规划选型能力。薪资与BAT对标。简历发送至 luozexiang@meituan.com

## 活动

> 宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[QCon北京站2017](http://2017.qconbeijing.com/)

2017年4月16日北京举行。明年第一场最值得期待的综合性技术大会。QCon内容源于实践并面向社区，演讲嘉宾依据热点话题，面向5年以上工作经验的技术团队负责人、架构师、工程总监、高级开发人员分享技术创新和最佳实践。