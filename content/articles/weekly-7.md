+++
title = "移动开发每周阅读清单：第七期"
date = "2016-04-11T21:33:45+08:00"
description = "『移动开发每周阅读清单』第七期与大家见面了，这周我们学习其它优秀周报的经验，增加Job（工作）和Event（活动）两部分，欢迎大家关注~"
tags = ""
+++

​『移动开发每周阅读清单』第七期与大家见面了，这周我们学习其它优秀周报的经验，增加Job（工作）和Event（活动）两部分，欢迎大家关注~

## 新闻

[Google 表示可能会将 Swift 作为 Android 开发的头等语言](http://thenextweb.com/dd/2016/04/07/google-facebook-uber-swift/?%2BSandbox)

最近，Google，Facebook 和 Uber 的开发人员在伦敦对这门语言进行了一些讨论。Google 的相关人士表示正在考虑将 Swift 引入 Android 开发中，从而逐渐减少对 Oracle 和 Java 的依赖。Swift 在开源后，其一大优势就是能够在服务器和客户端使用统一的语言，在像 IBM 这样的企业的支持下，Swift 正在向着这一愿景前进。

[更加轻薄的 Apple Watch 第二代产品可能在 WWDC 上公布](http://www.macrumors.com/2016/04/08/apple-watch-2-debut-wwdc-june-brian-white/)

Apple Watch 初代产品虽然在同类竞品中算是佼佼者，但是远没有达到市场预期。有消息称 Apple 可能在今年 WWDC 发布 Apple Watch 的第二代产品。相比于现在的 Apple Watch，新版本在厚度上将会减少 20% ~ 40%，并可能配置可以进行 Facetime 的摄像头和更好的 WiFi 模块。

[Android Studio 2.0发布稳定版](http://chinagdg.org/2016/04/android-studio-2-0/)

Android Studio 2.0稳定版终于发布了，还在使用1.5版本或beta版的同学可以放心升级了。作为Google的官方IDE，Android Studio包括你构建应用时需要的所有东西，包括代码编辑器、代码分析工具、模拟器等等。最新的2.0稳定版带来了更快的构建速度和更快的模拟器，支持最新的Android和Google Play Services。

## 教程

**iOS**

[教你用Xtrace读懂Mantle源码](http://ios.jobbole.com/84471/)

[Xtrace](https://github.com/johnno1962/Xtrace) 是 iOS 开发中一个强大的调试框架，能详细打印出一个某个方法被调用的堆栈，方便调试时定位问题。这篇文章介绍了使用 Xtrace 追踪 [Mantle](https://github.com/Mantle/Mantle) 的调用，逐步帮助我们理解 Mantle 行为和源码的一个例子。


[Swift 2 throws 全解析 - 从原理到实践](https://onevcat.com/2016/03/swift-throws/)

throws 关键字和异常处理机制是 Swift 2 中新加入的重要特性。Apple 希望通过在语言层面对异常处理的流程进行规范和统一，来让代码更加安全，同时让开发者可以更加及时可靠地处理这些错误。这篇文章从 throws 的内部实现探索了 throws 的一些细节，并为我们带来了在日常开发中使用 Swift 异常机制的一些实践方法。

[Using Swift Extensions The “Wrong” Way](https://www.natashatherobot.com/using-swift-extensions/)

Swift 中 extension 一般用来表示类型对某个接口进行扩展，但是这并不是 extension 的唯一用法。匿名的 extension 也可以用来对代码进行更好地组织，使其清晰可读。这篇文章为我们介绍了那些关于 extension 的“错误”用法，虽然这些用法并没有实际去将类型按照某个接口进行扩展，但是这并不是一种反模式的代码设计行为。恰恰相反，使用这些方法能够让代码更加优雅。

[用更 Swifty 的代码遍历数据](http://blog.dianqk.org/2016/04/07/用更%20Swifty%20的代码遍历数据/)

在遍历一个 Array 的时候，我们可能会用 `for .. in`、`map`、`flatMap` 或者是 `forEach` 等等，这篇文章基于 `flatMap`，使用了一些模式匹配的方法来更好地处理 [T?] 。通过为 `SequenceType` 添加一些便利方法，我们可以用一种更易读和可维护的方式来更好地对存储可选值类型的数组进行遍历。

**Android**

[Retrofit分析-漂亮的解耦套路](http://www.jianshu.com/p/45cb536be2f4)

Retrofit是由square出品的的HTTP client。Retrofit与Volley相比，前者解耦更彻底，可以通过注解来配置请求参数，通过工厂来生成CallAdapter，Converter，可以使用不同的请求适配器(CallAdapter), 支持json、xml、protobuff等不同的反序列化工具(Converter)。本文详细讲解了Retrofit的解耦实现。Retrofit的源码在[这里](https://github.com/square/retrofit)。

[Airbnb：我们的安卓客户端是如何使用RxJava的](https://realm.io/cn/news/kau-felipe-lima-adopting-rxjava-airbnb-android/)

移动用户期望即时响应，而且还有在不同的线程间来回切换的需求。除了主线程，你还要做网络连接，同时你还需要在后台处理其他的各种不同的事情。最重要的是，你不能阻塞UI线程。RxJava很好的解决了这类问题，RxJava使得线程间的切换变得更加容易。本文来自知名房屋租赁平台Airbnb的员工之手，介绍了Airbnb中是如何使用RxJava的。

[NDK-JNI实战教程（四）再谈新工具及NDK开发调试](http://blog.csdn.net/yanbober/article/details/51027520)

Android开发工具的更新速度很快，基本上一年左右就需要更新工具以及自己的知识库。关于NDK的调试一直都是个坑，好在Google在大力布局Android Studio时开始来填坑了；以前NDK的调试都只能依赖于GDB命令行的调试，而现在却变得GUI化，方便了许多。本文是介绍关于NDK开发工具版本过度的文章，适合从事NDK开发的同学阅读学习。

[为什么Android要采用Binder作为IPC机制？](http://www.zhihu.com/question/39440766)

Android另起炉灶开发了Binder驱动，而没有采用已有的方案，而D-Bus这样的方案也可以实现Binder的功能，是出于什么原因和什么考虑？安全性？性能？阅读文章，看看大家是如何回答该问题的。

[这些小工具让你的Android开发更高效（下）](http://www.jianshu.com/p/03136bdb1e50)

本文收藏了大量Android开发工具，开发者可以根据自己的需求选择使用。

## 开源项目

**iOS**

[SwiftyMarkdown](https://github.com/SimonFairbairn/SwiftyMarkdown)

一个将 markdown 转换为 `NSAttributedString` 的框架。相比于其他一些 markdown 解析的框架，SwiftyMarkdown 使用的是 Cocoa 框架的 `NSScanner` 来进行的实现，因此代码相对简单。不过如果你需要处理较多的 markdown 内容，可能选择其他一些更底层的实现会更合适。

[SwiftSVG](https://github.com/mchoe/SwiftSVG)

解析和显示 SVG 的库，可以将输入的字符串，文件，URL 等来源的 SVG 资源转换为可以直接描画显示的 `UIBezierPath` 对象。另外，该框架还额外提供一个 `SVGView` 来帮助开发者在 Interface Builder 中显示和调试 SVG 资源。如果你的应用中有需要用到或者显示 SVG 矢量图片资源的话，这个库会是很好的选择。

[KMNavigationBarTransition](https://github.com/MoZhouqi/KMNavigationBarTransition)

用来统一管理导航栏转场以及当 push 或者 pop 的时候使动画效果更加顺滑的通用库。自定义 Navigation View Controller 导航栏的背景或者状态是 iOS 开发者一定会遇到的课题，这个框架帮助我们将复杂的操作细节进行了封装，而使用者只需要关心目标 view controller 的样式即可。

**Android**

[JJSearchViewAnim](https://github.com/android-cjj/JJSearchViewAnim)

一个实现了各种搜索交互动画的动画库,一共实现了8种不同的搜索交互动画。

[ActivityRouter](https://github.com/mzule/ActivityRouter)

这是一个通过给Activity定义URL，然后可以根据URL跳转到对应的Activity的库，支持在浏览器与App中跳入。我们也可以参考该项目来实现项目的解耦。

[Android CatLoadingView](http://androidone.io/info_10130.html)

这是一个非常有意思的加载动画，效果很赞。

## 工作

> 本周新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**高级iOS工程师 by 杭州擎怀科技有限公司**

杭州天使轮公司，车前后市场。找3-5年经验能独当一面的iOS工程师，薪资：14k～18k。简历投递邮箱：rea1108@163.com

**iOS工程师 by 香港全民科技有限公司**

带艺术和硅谷气质的创业公司，坐标深圳。负责iOS应用开发，在原来的工资上加薪20%。希望应聘者经常关注国外iOS技术动向。简历投至：Hr_quanmin@163.com

## 活动

> 新栏目之二，宣传一些线下活动，除了我们自办的GMTC大会之外，也宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[GMTC全球移动技术大会](http://gmtc.geekbang.org/)

上周新增两位实力派讲师：去哪儿技术总监、《App研发录》的作者包建强，演讲议题：Android插件化：从入门到放弃。百度Android资深工程师、《Android开发艺术探索》的作者任玉刚，演讲议题：Android开发之多进程架构。大会现在6折期间，5人以上团购更多优惠，欢迎购票参加。

[QCon移动开发与即时通讯专场](http://form.mikecrm.com/f.php?t=TcBJhw)

4月23日周六举行。限额100人免费报名。讲师及内容包括：起步科技联合创始人兼CTO宋兴烈等带来的《剖析WeX5开源高性能H5 App开发框架》和融云技术副总裁杨威带来的《移动端IM开发如何拥有SaaS级体验》等。欢迎报名。

-----

上周移动开发前线公众号精彩文章：

* [网易漫画Swift混编实践](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=403474677&idx=1&sn=5163adb2d80aa5b4f0099f79e6d783e1#rd)
* [豆瓣App混合开发实践](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=403327635&idx=1&sn=e95eaa8f25c206385bc6451af92829ef#rd)
* [实战Kotlin@Android（一）：项目配置和语言转换](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=403421478&idx=1&sn=ffaa512eaf23982c2da5e919694fd1ed#rd)
* [Weex——关于移动端动态性的思考、实现和未来](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=403315899&idx=1&sn=b9784e99df78fb4ccf900cb48b48517f#rd)
