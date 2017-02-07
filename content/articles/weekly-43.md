+++
date = "2017-01-10T23:07:47+08:00"
title = "移动开发每周阅读清单：第四十三期"
description = "Apple 发布 2017 年第一季度财报。连续三季度出现收入同比下跌后，Apple 本次获得不错成绩。财报显示，自 2016 年 9 月至 2016 年 12 月，Apple 季度营收达到 783.5 亿美元，同比年增长 3%"
+++


## 新闻

[因节假日 iPhone 卖得好，Apple 新一季财报成绩喜人](http://images.apple.com/newsroom/pdfs/Q1FY17DataSummary.pdf)

Apple 发布 2017 年第一季度财报。连续三季度出现收入同比下跌后，Apple 本次获得不错成绩。财报显示，自 2016 年 9 月至 2016 年 12 月，Apple 季度营收达到 783.5 亿美元，同比年增长 3%，每股收益达 3.36 美元。Apple CEO Cook 表示，该季度中，Apple 售出的 iPhone、Mac、Apple Watch，服务都创下了历史最高纪录。

[网易或在中国运营谷歌应用商店，已经开始谈判](https://view.inews.qq.com/a/TEC2017020700552607)

据外媒最新消息，谷歌正在和中国互联网公司网易进行接触，谷歌可能通过网易在中国经营Play商店。网易和谷歌目前正在就此事进行磋商，但是双方是否会达成合作尚未可知。谷歌母公司Alphabet的董事长施密特此前曾经表示，在中国市场，谷歌需要寻找到一个商业伙伴来开展自身的一些业务，尤其是负责和政府监管部门之间的沟通。

## 教程

**iOS**

[介绍一种 iOS 中实现完全自定义导航栏的思路](http://soledad.me/2017/01/18/about-tiptoes/)

本文作者参考 Unread 的 iOS 客户端导航栏交互，分享了一种定制导航栏的思路。

[Building a LISP from scratch with Swift](https://www.uraimo.com/2017/02/05/building-a-lisp-from-scratch-with-swift/)

用 Swift 来写一个 LISP 解释器，你可以从中了解到如何写一个解释器。

[iOS 创建对象的姿势](http://mp.weixin.qq.com/s/io9rzhtn9l8RYoHvH4tWyg)

本文介绍了通过 init 、 Designated initializer 、 Builder pattern 等创建对象方式，并对比其中的不同。

[『状态』驱动的世界：ReactiveCocoa](http://draveness.me/racsignal/)

本文从最简单的例子中了解 ReactiveCocoa 的工作原理以及概念，也是作者个人对于 RAC 学习的总结与理解。主要围绕 RAC 中核心概念 RACSignal 展开，详细了解其底层实现。



**Android**

[Android硬件加速原理与实现简介](http://tech.meituan.com/hardware-accelerate.html)

在手机客户端尤其是Android应用的开发过程中，我们经常会接触到“硬件加速”这个词。由于操作系统对底层软硬件封装非常完善，上层软件开发者往往对硬件加速的底层原理了解很少，也不清楚了解底层原理的意义，因此常会有一些误解，如硬件加速是不是通过特殊算法实现页面渲染加速，或是通过硬件提高CPU/GPU运算速率实现渲染加速。本文尝试从底层硬件原理，一直到上层代码实现，对硬件加速技术进行简单介绍，其中上层实现基于Android 6.0。

[Android热修复Tinker接入及源码浅析](http://mp.weixin.qq.com/s/WHYA4aTWIHcd8CQ95StwDg)

现在热修复的技术有阿里的AndFix、QZone的方案、美团提出的方案以及腾讯的Tinker等。而Tinker已运行在微信的数亿Android设备上，所以该方案已经非常成熟。本文介绍了tinker的接入方法，并且对tinker的大致的原理进行了分析。

[Android应用瘦身，从18MB到12.5MB](http://www.jianshu.com/p/31ba2d0e9a60)

App瘦身是每个Android开发者都需要面对的问题。本文作者介绍了自己将App从18MB瘦身到12.5MB的方法。作者主要从安装包组成、资源瘦身、Native库瘦身、代码瘦身入手。作者在文章中给出了瘦身用到的工具，希望对大家有所帮助。

[Android新特性介绍，ConstraintLayout完全解析](http://blog.csdn.net/guolin_blog/article/details/53122387)

ConstraintLayout是Android Studio 2.2中主要的新增功能之一，它和传统编写界面的方式恰恰相反，非常适合使用可视化的方式来编写界面，但并不太适合使用XML的方式来进行编写。另外，ConstraintLayout还有一个优点，它可以有效地解决布局嵌套过多的问题。

[Android 6.0 SSL通信](http://www.jianshu.com/p/fefeb1b310f1)

在Android平台上使用SSL，第一步就是要生成证书。因为JDK自带的keytool工具默认生成的密钥库是JKS类型的，而Android客户端只支持BKS类型的密钥库，所以必须先扩展keytool工具使其生成BKS密钥库。要扩展，则需要下载BouncyCastle库。本文给出了生成证书的方法并且提供了具体的实现代码。

[安卓逆向系列教程](http://blog.csdn.net/wizardforcel/article/details/54730253)

从事逆向工作的人并不是很多，但反编译过App的开发者应该不在少数。本文作者写了一个系列的文章专门介绍Android逆向的知识，学习逆向知识不仅仅是破解别人的App，更重要的是对于我们进行安防有一定的帮助。


## 开源项目

**iOS**

[lottie-ios](https://github.com/airbnb/lottie-ios)

Airbnb开源的渲染 After Effects 矢量动画组件，支持iOS、Android、React Native，这是iOS版本。

[chromium-ios](https://chromium.googlesource.com/chromium/src.git/+/master/ios/)

Google 在春节期间开源了 Chrome for iOS，加入了Chromium开源项目，Chromium现在同时支持Webkit和Blink引擎了。

[MobileTerminal](https://github.com/steventroughtonsmith/MobileTerminal)

使用 MobileTerminal 可以在 iOS 上进行一些简单的命令操作。

[Guaka](https://github.com/oarrabi/Guaka)

兼容 POSIX 命令行 Swift 框架。


**Android**

[lottie-android](https://github.com/airbnb/lottie-android)

Airbnb开源的渲染 After Effects 矢量动画组件，支持iOS、Android、React Native，这是Android版本。

[Android-SplashView](https://github.com/jkyeo/Android-SplashView)

该项目可以帮助开发者通过简单的几行代码管理闪屏页或广告页。

[walle](https://github.com/Meituan-Dianping/walle)

Android Signature V2 Scheme签名下的新一代渠道包打包神器。walle通过在Apk中的APK Signature Block区块添加自定义的渠道信息来生成渠道包，从而提高了渠道包生成效率，可以作为单机工具来使用，也可以部署在HTTP服务器上来实时处理渠道包Apk的升级网络请求。

## 工作

> 有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**iOS/Android工程师 by 爱奇艺**

坐标北京或上海。维护爱奇艺及旗下app的架构和业务，以及移动端和前端基础设施，薪资就能力浮动。要求：本科以上,工作经验两年左右。简历发送至：jinkai@qiyi.com

**中高级Android/iOS开发工程师 by 小红书**

坐标上海。负责参加小红书主App开发。要求三年以上相关经验，有App优化实践经验，有一定框架和架构开发经验。简历至：fzhang@xiaohongshu.com，主题格式：*应聘：（Android/iOS）开发工程师-姓名-当前公司*

**高级Android工程师 by 北京九轮网络科技**

坐标北京昌平。开发海外市场社交App。要求开发经验5-10年。薪资面谈。简历发送至 laowei@biulove.com

**iOS/Android/前端高级工程师 by 新美大平台部门大前端**

坐标北京。维护美团App平台架构/业务，以及移动端和前端基础设施。高级工程师要求有一定的技术规划选型能力。薪资与BAT对标。简历发送至 luozexiang@meituan.com

## 活动

> 宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[QCon北京站2017](http://2017.qconbeijing.com/)

2017年4月16日北京举行。明年第一场最值得期待的综合性技术大会。QCon内容源于实践并面向社区，演讲嘉宾依据热点话题，面向5年以上工作经验的技术团队负责人、架构师、工程总监、高级开发人员分享技术创新和最佳实践。