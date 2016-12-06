+++
title = "移动开发每周阅读清单：第二十七期"
date = "2016-09-05T21:33:45+08:00"
description = "Apple 正式确定今年的秋季发布会召开时间，为 9 月 7 日上午 10 时（北京时间 8 号凌晨 1 点），地点在旧金山的 Bill Graham Civic 礼堂。苹果将在此次发布会上推出全新的的 iPhone 和 Apple Watch 产品。可能发布新版 iPad 和 MacBook Pro 。"
tags = ""
+++


## 新闻

[Apple 将于 9 月 7 号举行秋季发布会](http://www.apple.com/apple-events/september-2016/)

Apple 正式确定今年的秋季发布会召开时间，为 9 月 7 日上午 10 时（北京时间 8 号凌晨 1 点），地点在旧金山的 Bill Graham Civic 礼堂。苹果将在此次发布会上推出全新的的 iPhone 和 Apple Watch 产品。可能发布新版 iPad 和 MacBook Pro 。

[谷歌为安卓手机推出内容搜索工具In Apps，LG V20首发](http://www.ithome.com/html/android/254111.htm)

谷歌宣布针对Android智能手机推出一种内容搜索工具，这种名为“In Apps”的工具能让用户找到深藏于手机上安装的应用内部的内容。举例来说，用户可直接通过这个工具搜索查找特定歌曲、好友或注释，而不是非要首先打开相关应用才能搜索。用户可在谷歌搜索应用点击一个新的“In Apps”标签来获取这种功能，该工具可通过Gmail、Spotify和YouTube进行分析。

## 教程

**iOS**

[【Swift 脑洞系列】并行异步运算以及 100 行的PromiseKit](http://www.jianshu.com/p/656bebe7aa6e)

本文作者利用 Swift 的函数式特性，通过实现特殊的 High Order Function，提供了一种新的方式来建模异步操作的串行与并行。并在最后给出了一种 PromiseKit 的简洁实现。

[用 Swift 搭建数据驱动型 iOS 架构](http://mrpeak.cn/blog/swift-dda/)

本文作者尝试来用 Swift 搭建一个完整的数据驱动型架构，介绍了一种更清晰的层次结构和数据流向应用架构，该架构也能支撑更复杂的业务系统。其核心思想是基于数据驱动的观察者模型，称之为 Data Driven Architecture 。


**Android**

[Android wear开发初探](http://chuansong.me/n/651634851225)

Android Wear从2014年3月发布到现在已经从1.0发展到2.0（目前还没正式发布）。其产品定位也发化了巨大变化。Android wear 2.0支持的通讯方式有蓝牙，Wifi,3G/4G等方式，现在可以完全摆脱手机使用。目前官方也推荐将数据通过wifi或者3G/4G的方式进行传输，而不是蓝牙。本文为我们简单介绍了Android wear应用从构建到发布的整个过程。

[Android利用APT技术在编译期生成代码](http://brucezz.itscoder.com/articles/2016/08/06/use-apt-in-android/)

APT(Annotation Processing Tool 的简称)，可以在代码编译期解析注解，并且生成新的Java文件，减少手动的代码输入。现在有很多主流库都用上了APT，比如 Dagger2, ButterKnife, EventBus3 等。本文通过一个简单的View注入项目ViewFinder，介绍了APT相关内容，简单实现了类似于ButterKnife中的两种注解@BindView和@OnClick。

[深度理解Android InstantRun原理系列](http://mp.weixin.qq.com/s?__biz=MzA4MjA0MTc4NQ==&mid=2651574039&idx=1&sn=23e944c522ca55169279b8317c36752a&scene=1&srcid=0827t6aBnCuSjJCZlasyAsdD#rd)

Instant Run是Android Studio2.0以后新增的一个运行机制，能够显著减少你第二次及以后的构建和部署时间。简单通俗的解释就是，当你在Android Studio中改了你的代码，Instant Run可以很快的让你看到你修改的效果。作者通过一个系列的文章，为我们详解了InstantRun的工作原理。



## 开源项目

**iOS**

[IBAnimatable](https://github.com/IBAnimatable/IBAnimatable)

IBAnimatable 是一个帮助我们在 Interface Builder 和 Swift Playground 里面设计 UI, 交互, 导航模式, 换场和动画的开源库。在最新的 2.7 版本增加了两大功能：在 Interface Builder上设计 Presentation 的转场动画以及在 IB 上设计Activity Indicator 。支持 Swift 2.2 和 Swift 2.3 版本。

[Retry](https://github.com/icanzilb/Retry)

错误处理除了 try 有没有更好的方案？Retry 是一个灵活易用的错误处理库，提供了同步和异步的错误处理，支持自定义 retry 次数、自定义间隔时间 retry 等定制功能。

[BonMot](https://github.com/Raizlabs/BonMot)

支持链式调用处理的富文本框架，支持 Swift 和 Objective-C 。

**Android**

[RecyclerViewSnap](https://github.com/rubensousa/RecyclerViewSnap)

使用RecyclerView实现横向排列、纵向列表效果。

[SuperIndicator](https://github.com/hejunlin2013/SuperIndicator)

仿爱奇艺视频，腾讯视频，搜狐视频首页推荐位轮播图，支持无限循环、自动轮播。

[EncryptedPreferences](https://github.com/PDDStudio/EncryptedPreferences)

升级版的SharedPreferences，采用AES-256 encrypted。

## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**Android开发工程师 by 淘汽互联网科技有限公司**

坐标福州。负责参与客户端开发和优化。要求2年以上Android经验，承担过App核心功能开发。薪资8-15K。简历发送至 zongwu@taoqicar.com

## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[高德Inside技术沙龙](http://form.mikecrm.com/2zCvh0)

9月10日北京举行。由InfoQ与高德开放平台联合举办的高德Inside技术沙龙活动，将邀请来自高德开放平台及游戏行业用户的专家，介绍如何利用高德地图SDK与定位SDK来解决LBS手游开发难题，分享游戏开发结合地图定位技术背后的经验教训与实践成果。活动免费，名额有限。

----
