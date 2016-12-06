+++
title = "移动开发每周阅读清单：第十四期"
date = "2016-05-30T21:33:45+08:00"
description = "『移动开发每周阅读清单』第十四期与大家见面了，上周Google与甲骨文的官司终于尘埃落定，Google胜诉，这一判决非常具有历史意义，将作为判决之后类似官司的重要依据。"
tags = ""
+++

『移动开发每周阅读清单』第十四期与大家见面了，上周Google与甲骨文的官司终于尘埃落定，Google胜诉，这一判决非常具有历史意义，将作为判决之后类似官司的重要依据。

## 新闻

[谷歌与甲骨文的官司花了6年终于打完了](http://tech.hexun.com/2016-05-27/184098668.html)

谷歌和甲骨文的官司在6年之后终于打完了，结果是谷歌大获全胜，不过甲骨文表示会继续上诉。近日，美国旧金山联邦法庭陪审团就谷歌与甲骨文的版权案进行判决，认定谷歌Android系统没有侵犯甲骨文版权，驳回了甲骨文索赔90亿美元的诉讼请求。陪审团认为，谷歌使用Java进行了创新，而非简单地抄袭代码，属于合法使用Java软件代码。

[Intel 将为 Apple 的 iPhone 7 设备提供 50% 的 LTE 芯片](http://www.macrumors.com/2016/05/17/intel-to-supply-up-to-half-lte-chips-iphone-7/)

在过去三年里，高通一直是 Apple iPhone 设备通讯芯片的独家供货商，但是这一状况可能在今年的 iPhone 7 上有所改变。Apple 可能会更多地转向 Intel，而后者可能会为 iPhone7 提供 50% 左右的更快的适配 LTE Advance 的通讯芯片。移动设备的通讯速度在很大程度上决定了 app 的使用场景。在更快速度的平台上，可能之前一些无法实现的服务都将变为可能。

[Android N命名投票 Neyyappam暂排第一](http://tech.sina.com.cn/n/k/2016-05-30/doc-ifxsqxxu4640009.shtml)

Android N的命名征集活动将持续到6月9日截止，来自印度的甜点Neyyappam目前票数最多的名称了。据悉，Neyyappam是印度克勒拉省的传统甜点，是一种把米磨成粉后，拌上棕榈糖、椰子和酥油制作而成的圆形咖啡色甜点。按照Android的命名惯例，这一代的Android N名称应该是一个以N开头的甜点，而印度的Neyyappam刚好符合这个标准。



## 教程

**iOS**

[Clang Attributes 黑魔法小记](http://blog.sunnyxx.com/2016/05/14/clang-attributes/)

Clang Attributes 是 Clang 提供的一种源码注解，方便开发者向编译器表达某种要求，参与控制如 Static Analyzer、Name Mangling、Code Generation 等过程，一般以 `__attribute__(xxx)` 的形式出现在代码中。这篇文章为我们介绍了几个很有意思的“黑魔法” attribute，有时候灵活并正确地使用它们会给你带来不少便利。

[从ReactiveCocoa中能学到什么？不用此库也能学以致用](http://www.jianshu.com/p/39e27fef38fa)

类似 ReactiveCocoa 或者 RxSwift 这样的响应函数式编程在 iOS 开发中已经有些时日了，但是可以说一直没有大规模流行起来。究其原因，它需要使用者对程序设计有相对较高的理解和完善的技能，学习曲线也稍微陡峭一些。但这并不妨碍我们了解这种编程思想，并取其精华将它部分使用在最合适的场景。这篇文章就从这个角度为我们剖析了 ReactiveCocoa，并通过例子说明了如何使用响应式的理念改善现有的程序设计。

[Animating text layers using CoreAnimation and CoreText frameworks in iOS SDK](http://vormlab.com/animating-text-layers-using-coreanimation-coretext-frameworks-ios-sdk/)

一篇关于使用 CoreAnimation 和 CoreText 来实现文字渲染动画的文章。iOS 平台的 app 如果能够精于交互，力求用完美的表现将自己呈现给用户的话，相信也能够得到用户的好评和喜爱。而提升用户体验的最立竿见影的方式就是使用合适的动画效果。本文为我们讲述了一种使用动画来呈现文字的方式，你可以举一反三，来实现很多类似的漂亮的展示效果。

**Android**

[英语流利说Android 架构演进](https://mp.weixin.qq.com/s?__biz=MzI0NjIzNDkwOA==&mid=2247483673&idx=1&sn=ba9cf498ab78646f1a9c9e711f65c360&scene=1)

本文的分享来自英语流利说的Android开发者，给大家分享了英语流利说Android端代码架构的演进。英语流利说的整个演进过程，也是借鉴了业界很多大型应用在架构上的沉淀以及思想，可能有些东西还有点老生常谈，但依然干货满满。

[深入浅出Android打包](http://geek.csdn.net/news/detail/76488)

Android市场的渠道分散已不是什么新鲜事，但如何高效打包仍是令许多开发者头疼的问题。本篇文章着重介绍了目前最新的三种打包方案，并且从安全方面对这三种方案进行点评，相信会给开发者带来新的助力。

[你需要知道的Android拍照适配方案](http://www.jianshu.com/p/f269bcda335f)

说起调用系统相机来拍照的功能，大家肯定不陌生，如今几乎每一款应用都涉及到拍照这个功能。例如最基本的用户拍照上传头像。但是由于Android的设备型号太多，并且手机的第三方ROM标准也不统一，导致给拍照这个功能的实现带来很多头疼的问题。本文针对该问题给出了一些解决方案。

## 开源项目

**iOS**

[Expanding Collection](https://github.com/Ramotion/expanding-collection)

一个使用 Collection View 实现的卡片的展开和收起的动画效果。作者提供的不仅仅是一个特定例子的实现，也包括了如何复用这个已经高度定制过的动画效果的方法。通过巧妙使用 Collection View，你可以相对容易地将这样的动画集成到你自己的 app 中去。

[FastStub-Xcode](https://github.com/music4kid/FastStub-Xcode)

一个 Xcode 插件，可以用来根据头文件或者协议的声明，自动在实现文件中将缺失的方式进行补全。在像 AppCode 这样的 IDE 中可能这个功能是自带的，但是 Xcode 现在暂时并没有提供相应的功能，这个插件能够让你的生活变得轻松一些。

[fantastic-ios-animation](https://github.com/onmyway133/fantastic-ios-animation)

一个 awesome 式的收集类的仓库。维护者使用分类的方式将很多开源的 iOS 动画的实现进行了整理。如果你在制作属于自己的 app 时，又苦于没有美术的动画设计和用户交互设计为你提供界面元素和交互方式的话，参考这里的例子来获取灵感也许会是不错的选择。

[PrediKit](https://github.com/KrakenDev/PrediKit)

`NSPredicate` 是 iOS 开发者常用的一个类。不论是和 Core Data 打交道，或者是对集合进行过滤，可能都会使用到 `NSPredicate`。但是 `NSPredicate` 使用了大量的字符串和键值编程，其本身的语法是很不安全的。这个框架对 `NSPredicate` 进行了一些封装，使开发者能够通过使用闭包和相对安全易读的语句来使用谓词。如果你在项目中使用了很多 `NSPredicate` 的话，这个框架将能显著提高你的代码质量，并让它们更加容易理解。

**Android**

[LuaViewSDK](https://github.com/alibaba/LuaViewSDK)

这是阿里聚划算团队开源的一个项目。LuaView 是一种运行在一个 ViewController/Activity中，可以灵活加载Lua脚本，并能够按照Native的方式运行的一种面向业务的开发技术方案。可以快速开发电商应用中既要求体验又要求灵活性的页面功能，例如首页，类目首页，垂直频道，大促活动会场等。

[advancedtextview](https://github.com/oktayayr/advancedtextview)

这是一个自定义TextView，支持自定义字体而不需要引入ttf文件，还包括自动适应大小等功能。

[LoadingDrawable](https://github.com/dinuscxj/LoadingDrawable/blob/master/README-ZH.md)

该项目包含了一系列的加载动画实现，每一个动画效果都很赞。


## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

本期暂无工作介绍，你可查看往期介绍。

## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[GMTC全球移动技术大会](http://gmtc.geekbang.org/?utm_source=zhoubao&utm_medium=xuachuan02&utm_campaign=0530)

6月24-25日北京举办。来自BAT、携程、滴滴、微博、和社区的技术专家联袂分享，主题包括应用架构、性能优化、动态化、插件化、Swift、React Native、Weex等，为中高级移动开发工程师献上一场技术盛宴！在移动开发前线公众号回复“大会”可获得购票优惠码。

----

上周移动开发前线公众号精彩文章：

* [CocoaPods 1.0发布：廉颇老矣，尚能饭否？](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112301&idx=1&sn=837a66540e083eaefa71562c426d3bfc#rd)
* [蘑菇街App Chromium网络栈实践](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112324&idx=1&sn=34b15399d6519340f66410445f033e85#rd)
* [Android Instant Apps：改变应用的使用方式](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112329&idx=1&sn=40f075c425970a08817ea4106e766508#rd)

阅读更多移动开发好文，欢迎关注『移动开发前线』公众号。
