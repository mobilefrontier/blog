+++
title = "移动开发每周阅读清单：第三十七期"
date = "2016-11-28T21:33:45+08:00"
description = "11月23日消息，谷歌刚刚推出了安卓7.1第二个开发者预览版，这也将是安卓7.1最后一个预览版，之后谷歌会推出安卓7.1.1正式版。安卓7.1开发者预览版支持Nexus5X、Nexus6P、Nexus9和Pixel C，据谷歌表示，安卓7.1开发者预览版2在系统稳定性和UI方面接近“完全体”"
tags = ""
+++


## 新闻

[Apple 停止了 AirPort 产品线开发](https://www.zybuluo.com/DianQK/note/582756)

根据彭博社报道，Apple 已经停止包括 AirPort Express、AirPort Extreme 等无线路由产品的开发。Apple 希望可以将人手用在带来收益更高的下一代苹果产品中。不过并不清楚苹果会在什么时间点停止生产这些产品，目前这些产品还可以买到，如果你想要买一款留做纪念，可能要抓紧了。

[安卓7.1开发者预览版Beta2放出：更接近完全体](http://www.ithome.com/html/android/274815.htm)

11月23日消息，谷歌刚刚推出了安卓7.1第二个开发者预览版，这也将是安卓7.1最后一个预览版，之后谷歌会推出安卓7.1.1正式版。安卓7.1开发者预览版支持Nexus5X、Nexus6P、Nexus9和Pixel C，据谷歌表示，安卓7.1开发者预览版2在系统稳定性和UI方面接近“完全体”。


## 教程

**iOS**

[iOS多线程到底不安全在哪里？](http://mp.weixin.qq.com/s/Pz1XdrAYDLrLeq97niT15g)

iOS 多线程安全的概念在很多地方都会遇到，为什么不安全，不安全又该怎么去定义，其实是个值得深究的话题。共享状态，多线程共同访问某个对象的 property ，在 iOS 编程里是很普遍的使用场景。本文从 Property 的多线程安全说起，分享了对 memory layout 和原子性的理解，并解释了 atomic 和 nonatomic 的区别。

[Swift: UserDefaults protocol](https://medium.com/swift-programming/swift-userdefaults-protocol-4cae08abbf92#.pcevrk2bt)

一篇类似[SwiftyUserDefaults](https://github.com/radex/SwiftyUserDefaults)框架的分享，介绍了如何在 Swift 中合理的使用 protocol 场景。

[APP 缓存数据线程安全问题探讨](http://blog.cnbang.net/tech/3262/)

本文探讨了在多线程下如何处理 Cache 的问题，分享了三种解决方案：加锁、分线程 cache 、 数据不可变。

[预加载与智能预加载](http://draveness.me/preload/)

本文介绍了 iOS 中几种预加载的方案，以及 ASDK 中是如何处理预加载的。


**Android**

[Redex初探与Interdex：Andorid冷启动优化](http://mp.weixin.qq.com/s?__biz=MzA3NTYzODYzMg==&mid=2653578240&idx=1&sn=b6a721e3eb0b3b0ee3ecb427452ef60e)

早在去年10月份，facebook就发布了介绍redex的文章，这个据说可以直接对apk做处理，既提高启动性能，又可减少安装包的利器让安卓开发者们都心动不已。直到今年4月，redex终于开源了，作者第一时间对redex做了研究。虽然由于坑多，最终没有接入到项目构建中，但受Interdex启发，在应用冷启动速度优化方面有了新的收获。

[使用Buck构建Android工程](http://mp.weixin.qq.com/s?__biz=MzI1NjEwMTM4OA==&mid=2651232278&idx=1&sn=cd22311ea309c09cbab7f122853f71f2)

Buck构建工具，其实早已不是什么新奇的事物，它是一款由Facebook开发、维护并开源的性能强大的构建工具。不仅在Facebook的全系列产品中广泛应用，而且在国内的微信团队也有使用。其构建的目标代码相当广泛，且对Android工程有所优化，核心思想是多任务并发的构建策略，充分发挥多核优势，Buck可以极大的加快Android工程全量构建的速度，是目前Android全量构建策略中的不二选择。

[如何构建Android MVVM应用框架](https://zhuanlan.zhihu.com/p/23772285)

说到Android MVVM，相信大家都会想到Google 2015年推出的DataBinding框架。然而两者的概念是不一样的，不能混为一谈。MVVM是一种架构模式，而DataBinding是一个实现数据和UI绑定的框架，是构建MVVM模式的一个工具。那么在Android中是如何通过DataBinding去构建MVVM的应用框架的？View、ViewModel、Model每一层的职责如何？它们之间联系怎样、分工如何、代码应该如何设计？本文给出了答案。

[Writing-Better-Adapters 译文及示例](http://www.diycode.cc/topics/455)

对于Android开发者来说，实现Adapter是最频繁的工作之一。Adapter是所有列表的基本，而列表也是很多App的基本组成。编写一个列表控件的方法大多数时间都是一样的：用一个绑定了Adapter的View来展示数据。然而一直这样会让我们对自己编写的代码变得盲目或者说我们一直在重复创造低级代码。阅读文章，看看作者是如何提高Adapter代码质量的。


## 开源项目

**iOS**

[Apple 开源 macOS 10.12 Sierra Darwin 代码](https://opensource.apple.com/release/os-x-1012.html)

Apple 公布了 macOS 10.12 Sierra 的开源 Darwin 代码，代码包含了 macOS、iOS、watchOS 和 tvOS 基于的 Unix 组件的核心集合，包括驱动程序和未加密的内核及其 BSD 部分。

[RocketData](https://github.com/linkedin/RocketData)

LinkedIn 的数据缓存框架，针对不可变Model。

[Swimat](https://github.com/Jintin/Swimat)

快捷对代码排版的 Xcode Extensions 。

[StatefulViewController](https://github.com/aschuch/StatefulViewController)

带状态 ViewController ，方便快速添加各种状态视图。

**Android**

[update](https://github.com/czy1121/update)

一款清晰灵活简单易用的Android应用更新库。

[blurkit-android](https://github.com/wonderkiln/blurkit-android)

这是一款使用简单的模糊工具，可以通过XML来配置。

## 工作

> 有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**Android&iOS研发工程师 by QQ**

坐标深圳。负责QQ上视频直播、短视频分享和QQ群相关的开发工作，欢迎对新技术有热情并好学的同学。简历发送至 cppgohan@qq.com

**企业产品iOS开发工程师 by QQ**

坐标上海。负责企点、企业QQ、手机QQ iOS平台的企业功能开发工作。要求3年以上iOS平台软件开发经验。简历发送至 sunnylyme@163.com


## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

----

[ArchSummit全球架构师峰会](http://bj2016.archsummit.com/)

地点北京。ArchSummit秉承“实践第一、案例为主”的原则，展示新技术在行业应用中的最新实践，技术在企业转型中的加速作用，帮助企业技术管理者、CTO、架构师做好技术选型、技术团队组建与管理，并确立技术对于产品和业务的关键作用。

[中国技术开放日广州站](https://jinshuju.net/f/lV70qu#utm_source=infoq&utm_campaign=techday&utm_medium=wechat&utm_term=1125&utm_content=android)

12月9日广州举行。主题为移动开发前沿。我们邀请了来自腾讯、阿里、百度、唯品会的技术专家前来分享一线开发实践。
