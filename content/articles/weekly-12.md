+++
title = "移动开发每周阅读清单：第十二期"
date = "2016-05-16T21:33:45+08:00"
description = "『移动开发每周阅读清单』第十二期与大家见面了，上周苹果投资了滴滴，给我们搞了大新闻；本周Google IO将会召开，且看本届大会Google会给我们带来哪些眼前一亮的东西。"
tags = ""
+++

『移动开发每周阅读清单』第十二期与大家见面了，上周苹果投资了滴滴，给我们搞了大新闻；本周Google IO将会召开，且看本届大会Google会给我们带来哪些眼前一亮的东西。

## 新闻

[Apple 加速应用商店审核过程，平均时间由九天下降为两天](http://www.bloomberg.com/news/articles/2016-05-12/apple-shortens-app-review-times-in-push-to-boost-service-sales)

审核周期过长一直是 App Store 生态中的一个严重问题，这使得第三方开发者难以快速迭代和更新版本。不过这也让开发者们对于 iOS app 的提交更加谨慎。最近，开发者发现 Apple 明显加快了应用审核的速度，之前对于一个应用的审核一般需要一周还多，而现在往往在提交第二天就能得到结果。这被认为是 Apple 希望开发者忠于平台，并且能以更快速度递交应用的重要举措。

[Apple 向滴滴打车投资 10 亿美元](http://chinese.engadget.com/2016/05/12/apple-invested-diditaxi/)

本周滴滴打车宣布了其新一轮融资的进展，其中 Apple 公司以 10 亿美元（约合人民币 65.21 亿）投资滴滴，是滴滴迄今为止获得的单笔最大投资。另外也有消息表明，Apple 可能在中国版的 iOS 10 中将滴滴打车作为系统预装软件推出，或是在 CarPlay 上进行整合。如果属实，这将是 Apple 在中国市场的一次重要布局。

[Google IO来临之际 Cardboard继承者初露端倪](http://games.qq.com/a/20160513/032688.htm)

Google Cardboard 可能有更加强大的继承者，根据一份软件开发工具说明文档所示，似乎称为 Android VR。事实上，Google IO 大会的第二天会开展一个被称为“VR at Google”的会议，恰好跟两年前宣布 Google Cardboard 一样。

## 教程

**iOS**

[用 ReactiveCocoa 事半功倍的写代码](http://fengjian0106.github.io/2016/04/17/The-Power-Of-Composition-In-FRP-Part-1/)

函数式响应编程是一门学习曲线比较陡峭的技术，作者结合自己的学习过程和使用经验，为我们带来了一个完整的使用 ReactiveCocoa 实践函数式编程的系列教程。我们很难脱离代码和实际使用场景来将函数式响应编程的原理讲清楚，而在明白原理后，往往也会不知道如何使用这个强大的工具来处理开发中遇到的现实问题。作者在这个系列教程里通过一些 demo 向我们完整展示了可能的使用场景和对应方法，非常值得一看。

[Building Slack Bots In Swift](https://medium.com/@pvzig/building-slack-bots-in-swift-b99e243e444c#.8zzsw955h)

Swift 现在已经是一门跨平台的语言，这极大拓展了 Swift 的使用场景，以及 Swift 开发者们能够做的事情。这篇文章讲述了作者自己使用 Swift 开发一个 Slack 聊天机器人的过程，其中用到了不少 Swift 服务器开发的基础技术，从中你可以一窥 Swift 服务器端开发的门径。

[CocoaPods 1.0](http://blog.cocoapods.org/CocoaPods-1.0/)

CocoaPods 可以说是 iOS 开发者最常依赖的一款包管理工具，本周，在 CocoaPods 正式公布五年之后，这款工具终于迎来了 1.0 正式版。1.0 中包含了更准确和完善的 Podfile DSL 描述，自动反集成，通过将框架集成至实际项目来检查可用性等等一系列新特性。CocoaPods 的这篇官方博客为我们详细介绍了 1.0 版中的新功能以及我们所需要做出的改变。

**Android**

[Google开源的FlexboxLayout](https://mp.weixin.qq.com/s?__biz=MzA4NTQwNDcyMA==&mid=2650661681&idx=1&sn=b151aba0c5fb702492f6bbd82211988d&scene=1)

最近Google开源了一个项目叫FlexboxLayout，简单来说Flexbox是属于web前端领域CSS的一种布局方案，是2009年W3C提出了一种新的布局方案，可以简便、完整、响应式地实现各种页面布局，并且React Native也是使用的Flex布局。我们可以简单的理解为Flexbox是CSS领域类似Linearlayout的一种布局，但是要比Linearlayout要强大的多。阅读文章，了解FlexboxLayout的具体使用方法。

[基于TLS1.3的微信安全通信协议mmtls介绍](https://mp.weixin.qq.com/s?__biz=MzAwNDY1ODY2OQ==&mid=2649286266&idx=1&sn=f5d049033e251cccc22e163532355ddf&scene=0)

本文来自微信团队的分享。微信现有的安全通信协议是基于用户登录的时候派发的SessionKey对应用数据进行加密的，该协议在工程实现上，已经过多次迭代优化，但是仍然有一些缺点。微信需要一套能够加密保护Client到Server之间所有网络通信数据、且加密通信保护必须对业务开发人员透明的安全通信协议，由此诞生了mmtls。本文对mmtls进行了详细解析。

[Android Studio提示与技巧（官方文档翻译）](https://mp.weixin.qq.com/s?__biz=MzA4MTg4MjkzMw==&mid=2654313326&idx=1&sn=49f4ffdc2888110243a1c33d624c4417&scene=0)

Android Studio的版本已经更新到了2.1，如果你对Android Studio和Intellij IDEA的界面很陌生的话，这篇文章提供的一些技巧会对你有所帮助。本文介绍了一些最常用的技巧，能使我们更新熟练的使用Android Studio，从而提高生产率。

## 开源项目

**iOS**

[Render](https://github.com/alexdrone/Render)

React 在前端开发中的地位现在如日中天，先不论 React 是否真的是万灵丹，它将 UI 进行组件化的思想如此受欢迎，想必是有其值得借鉴之处的。Render 是一次将 React 的开发方式带到 iOS 应用开发中的尝试。与传统的 UI 构建方式相比，组件化的 UI 可以用来描述某个状态下的 UI 情况，这在一定程度上可以使 Controller 与 UI 分离，是一种值得探索的界面开发方式。

[Build Time Analyzer for Xcode](https://github.com/RobertGummesson/BuildTimeAnalyzer-for-Xcode)

一款 Xcode 插件，可以用来统计项目中的文件的编译时间，帮助你找到编译花费时间最长的源文件和方法。对于大型项目来说，编译时间太长是导致开发效率降低的最主要和最直接的原因，如果我们能够压缩编译时间，那么工程师也就会更有动力进行多次部署和调试。你可以通过这款插件的统计，有目的地对源码进行优化，以提高开发效率。

[Interpolate](https://github.com/marmelroy/Interpolate)

一个用来创建交互式手势动画的插值框架。Interpolate 把所有的动画都看作是属性值随着时间进行改变的插值，并以类型安全的方式来创建随时间变化的动画属性值。这个框架在制作交互式教程或者一些复杂的手势动画时会十分灵活有用。

**Android**

[UpdatePlugin](https://github.com/yjfnypeu/UpdatePlugin)

几乎每个Apk都会有自动更新功能，很多第三方的公司也提供自动更新的组件。该项目实现了一个比较完整的自动更新功能，提供多种策略的更新方式。

[paper-onboarding-android](https://github.com/Ramotion/paper-onboarding-android)

这是一个适用于Android 5.0以上系统的引导页，集成简单方便，效果也很赞。

[pull-to-make-soup](https://github.com/Yalantis/pull-to-make-soup)

这是一个非常漂亮的下拉刷新动画，能够方便的集成到RecyclerView中。

## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**iOS/Android开发工程师 by 海尔旗下全资金融子公司**

地点上海。Android和iOS都要，开发金融类应用，要求完整项目经验，懂一些HTML5，能力优先，薪资面议。简历发送至zhangjiahuan@kjtpay.com.cn

**Android架构师 by 聚美优品**

地点北京或成都。负责开发维护客户端基础架构、公用组件，主持重构工作、技术分享交流，完善开发流程。要求5年以上Android经验2年架构经验，优秀者可放宽。简历发送至 feibiaoz@jumei.com

## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[GMTC全球移动技术大会](http://gmtc.geekbang.org/?utm_source=zhoubao&utm_medium=xuachuan02&utm_campaign=0516)

6月24-25日北京举办。来自BAT、携程、滴滴、微博、和社区的技术专家联袂分享，主题包括应用架构、性能优化、动态化、插件化、Swift、React Native、Weex等，为中高级移动开发工程师献上一场技术盛宴！本周为8折促销期间，5人以上团购更多优惠，欢迎购票参加。

[MDay 第五季](http://mday.mogu.io/?from=timeline&isappinstalled=0)

5月21日杭州举行。MDay 是由蘑菇街发起的面向移动开发者的分享交流会，目前已成功举办四届。会邀请一线的资深开发工程师来分享日常开发中遇到的种种问题、解决思路、经验总结、最佳实践等。

----

上周移动开发前线公众号精彩文章：

* [Weex详解：移动端高性能动态化方案](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112231&idx=1&sn=4578ff1009ee774093c45a3d8c19dd58#rd)
* [高二Android大牛是这样炼成的](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112235&idx=1&sn=9cd25a5c2bf572560776d0b140521426#rd)
* [Swift的响应式编程革命](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112245&idx=1&sn=6536b90c09651380ec2009eb46ed9281#rd)
* [手游直播背后的技术（附福利）](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112249&idx=1&sn=609de675ba61229c751ee407dc5b99b2#rd)
* [群分享：移动端SDK的优化之路](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112265&idx=1&sn=23fa0e84cfc9aaad0e33232d12868c07#rd)

阅读更多移动开发好文，欢迎关注『移动开发前线』公众号。
