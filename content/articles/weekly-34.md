+++
title = "移动开发每周阅读清单：第三十四期"
date = "2016-11-07T21:33:45+08:00"
description = "谷歌于11月3号宣布停止对集成开发环境（IDE）Eclipse的支持，而主推自家的Android Studio。今年9月份谷歌发布了Android Studio 2.2版本，谷歌称Eclipse上的所有特性，都已集成到Android Studio中，如果有所缺失，开发者也可以通过反馈模块进行反馈"
tags = ""
+++


## 新闻

[Apple 下调部分 USB-C 转接器配件价格](http://www.macrumors.com/2016/11/04/apple-lg-display-major-price-cut/)

由于新 MacBook Pro 采用了 Thunderbolt 3 接口，导致不少用户抱怨需要购买各种 USB-C 转接器才能正常使用，为此苹果下调了部分官方转接器的价格，活动只持续到年底。同时，Apple 还将两款新显示器 LG UltraFine 4K/5K 的价格下调了 25%。买买买链接：Mac 配件。

[谷歌结束对Eclipse开发工具支持，主推Android Studio](http://www.ithome.com/html/android/269467.htm)

谷歌于11月3号宣布停止对集成开发环境（IDE）Eclipse的支持，而主推自家的Android Studio。今年9月份谷歌发布了Android Studio 2.2版本，谷歌称Eclipse上的所有特性，都已集成到Android Studio中，如果有所缺失，开发者也可以通过反馈模块进行反馈。


## 教程

**iOS**

[iDev 大会会后演讲稿](https://github.com/devlinkcn/ppts_for_idev2016/tree/master/PDF)

前两天由社区 iDev 大会顺利进行，会后发布了演讲PPT，内容涉及链接器、响应式编程、React Native 、macOS 内核、单元测试、Swift 服务端、逆向工程、直播、函数式、组件化、HomeKit 等内容。

[Swift 反射 API 及用法](http://swift.gg/2015/11/23/swift-reflection-api-what-you-can-do/)

尽管 Swift 一直在强调强类型、编译时安全和静态调度，但它的标准库仍然提供了反射机制。文章的内容是基于作者在德国法兰克福 Macoun 会议上的一次演讲，它对 Swift 的反射 API 做了一个概述。

[iOS 端数据库解决方案分析](https://mp.weixin.qq.com/s?__biz=MzI5MjEzNzA1MA==&mid=2650264198&idx=1&sn=35c6d49a70294c80bc028ed4d4fddce4&chksm=f40683b3c3710aa53a7c2f2e7185da72db59d1b66a1c3dd5aef4365ed02e0e990ae71d548f94&scene=0&key=cde9f53f8128acbd779135b3277570c660cf6db3e0c889ca68e0b3db7e59436b7cd64105e9d66ee1748b14d77d473fbd&ascene=0&uin=MzA1Mjc1&devicetype=iMac+MacBookPro11%2C4+OSX+OSX+10.12.1+build%2816B2555%29&version=12000510&nettype=WIFI&fontScale=100&pass_ticket=MRuleTqfdiJNWUanddnk0sdWCIBFVeFCuQIPvtOHlU8%3D)

本文总结了移动端数据库的一些重要知识点，并综合对比下 sqlite 和 Core Data 的优缺点，希望能帮助一些这方面经历较少的同学少走一些弯路。

[Xcode8 调试黑科技：Memory Graph 实战解决闭包引用循环问题](http://www.jianshu.com/p/f792f9aa2e45)

本文介绍了 Xcode 8 新特性 Memory Graph 的使用，它是一个可视化的内存调试工具。


**Android**

[微信小程序开发思考总结——腾讯“信用卡还款”项目实践](http://mp.weixin.qq.com/s?__biz=MzA3NTYzODYzMg==&mid=2653578147&idx=1&sn=dc8ed8974bd7086389155eecc82e524d&chksm=84b3b1a4b3c438b275dc04bc454b1177fce1e3175841bd09a3be23ca8bf17679e3be90556d68&mpshare=1&scene=1&srcid=1104Ex2hHjmwExmmOASLZuRf#rd)

微信小程序是一种介于原生app、和web app的hybrid。通过微信进行加载，实现类似原生app的流畅。微信团队本周对外宣布，微信小程序开放公测。开发者可登陆微信公众平台申请，开发完成后可以提交审核，公测期间咱不能发布。本文详细介绍了微信小程序的开发流程及技术细节。

[五分钟带你看懂Android NestedScrolling嵌套滑动机制](http://blog.flight.dev.qunar.com/2016/11/04/android-nestedScrolling/)

Android在发布5.0之后加入了嵌套滑动机制NestedScrolling，嵌套滑动作为官方推出的一套更加方便的处理滑动的工具，可以说是很大程度上减少了我们在出来这方面问题上的复杂性。本文对嵌套滑动机制进行详细的分析。

[dex文件结构及其应用](http://zjutkz.net/2016/10/27/dex%E6%96%87%E4%BB%B6%E7%BB%93%E6%9E%84%E5%8F%8A%E5%85%B6%E5%BA%94%E7%94%A8/)

做Android的同学对dex文件一定不会陌生，它其中包含了我们一个工程所有的类，方法，字段等等的信息。通过对dex文件格式的学习，我们可以收获到的东西是非常多的。可能很多同学一想到文件格式这类的内容都会觉得头大，认为这是一个很高深的内容。本文作者一开始接触这方面东西的时候也有这样的抵触情绪，不过随着学习的深入，发现其实整个架构是很清晰的，所以写了这篇文章，总结了关于dex的一些知识点。

[途牛APK压缩最佳实践](http://mp.weixin.qq.com/s?__biz=MzAwOTE0ODEwMQ==&mid=2650686686&idx=1&sn=192f968e71621fa9fdf20f22c014e893&chksm=836ee774b4196e624e57308b1807fd5328271c80af7393b34f96e392ed4dcf30bc62b389d6b0&mpshare=1&scene=1&srcid=11047fPZims2Q9KIEfojkjCU#rd)

途牛App自2013年诞生，只有单品到如今发展成多产品平台。技术上从纯原生技术到如今接入了React Natvie方案，其客户端技术一直在不段的更新、升级。本文详细介绍了途牛App三年多的技术选型及发展之路。


## 开源项目

**iOS**

[AwaitKit](https://github.com/yannickl/AwaitKit)

参考 SCMAScript 2017 实现以同步方式处理异步代码框架。

[Hypertext](https://github.com/sahandnayebaziz/Hypertext)

生成 Html 文本的 Swift 框架，强类型，代码优美。

[sudo-touchid](https://github.com/mattrajca/sudo-touchid)

新版MacBook Pro配置了Touch ID，开发人员马上想出它的有趣的玩法，这是以 Touch ID 代替输入管理员密码的项目。



**Android**

[ChipsLayoutManager](https://github.com/BelooS/ChipsLayoutManager)

这是一款支持标签管理的LayoutManager，包括了RecyclerView的基本特性，并且支持标签自动换行。

[android-TNRAnimationHelper](https://github.com/thunderrise/android-TNRAnimationHelper)

该项目封装了Android常用的四种动画，开发者引入该库后，只需通过几行代码就可以创建一个动画效果。

[AlphaTabsIndicator](https://github.com/yingLanNull/AlphaTabsIndicator)

高仿微信底部状态栏的轻量级库，没有MagicIndicator那么臃肿，符合大多数BottomTab应用需求。




## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

本期暂无工作推荐。



## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

----

[ArchSummit全球架构师峰会](http://bj2016.archsummit.com/)

地点北京。ArchSummit秉承“实践第一、案例为主”的原则，展示新技术在行业应用中的最新实践，技术在企业转型中的加速作用，帮助企业技术管理者、CTO、架构师做好技术选型、技术团队组建与管理，并确立技术对于产品和业务的关键作用。

[2016 Google开发者大会 中国版](http://mp.weixin.qq.com/s?__biz=MzAwODY4OTk2Mg==&mid=2652039994&idx=1&sn=01d0e9c687c0fab258c0c3c83384929a&chksm=808d4b7fb7fac26923c785988c7683d989dc49987e4b634513a9e2cffd41a62be4a3b85914e8&mpshare=1&scene=1&srcid=1107qS5pHobbBA1ZdEZ94Gfi#wechat_redirect)

2016 Google 开发者大会（Google Developer Day - GDD）登陆中国，旨在与开发者们和科技行业翘楚们分享 Google 的最新科技和开放平台。大会将于 2016 年 12 月 8 日在北京，2016 年 12 月 14 日在上海分别举办。
