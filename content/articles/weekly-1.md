+++
title = "移动开发每周阅读清单：第一期"
date = "2016-03-14T21:33:45+08:00"
description = "大家好，第一期『上周速报』与大家见面了，这是我在InfoQ iOS周报和Android周报的基础上编辑整理而来，内容包括上周移动开发领域的新闻资讯、教程文章、开源项目等。每周一与您见面！"
+++

大家好，第一期『上周速报』与大家见面了，这是我在InfoQ iOS周报和Android周报的基础上编辑整理而来，内容包括上周移动开发领域的新闻资讯、教程文章、开源项目等。每周一与您见面！

如果有更好的建议欢迎留言~

## 新闻


[Apple 春季发布会时间更改](http://recode.net/2016/02/27/remark-your-calendars-apples-product-event-will-week-of-march-21/)

之前媒体预测 Apple 将在 3 月 15 日召开春季的新品发布会，而最近通过某些 Apple 员工的日常安排来看，其实实际发布会的日期可能是 3 月 21 日。据称 Apple 在这次发布会上会公布新的 4-inch iPhone，iPad Air 3 以及一款 Apple Watch 表带。会不会还有出人意料的 One More Thing，让我们拭目以待。

[IBM 建立 Swift Package 分类索引](https://swiftpkgs.ng.bluemix.net)


IBM 在 Swift 上一直在紧跟 Apple 脚步，最近 IBM 建立了一个 Swift Package 分类索引的网站。该站点收录了支持 Swift Package Manager 的开源项目，并按照分类和一些规则进行了排序。如果你现在就有使用 Swift Package Manager 进行开发的需求，那在这个站点上寻找需要的依赖会是不错的选择

[安卓7.0首批截图公布：惊现汉堡菜单](http://www.ithome.com/html/android/208573.htm)


2 月26日消息，谷歌在开发者页面公布了首批Android N（安卓7.0）截图，从截图中能够了解到的一点是安卓7.0设置界面中会添加汉堡式菜单，但并不清楚是否汉堡菜单会贯穿全系统。当然，最终这个特性会不 会出现在安卓7.0中也不能确定。另外还有消息称，安卓7.0将取消应用抽屉。

[微软正式宣布移植Android应用计划流产](http://www.cocoachina.com/android/20160226/15449.html)


2 月26日上午，微软宣布将停止为开发者提供Android应用导入工具，意味着他们无法借助微软提供的官方工具将Android应用导入 Windows 10。微软最早在去年的Build开发者大会上宣布了这个名为Project Astoria的项目，同时还发布了一项类似的计划，可以将iOS应用转换到Windows 10平台，这个项目目前还安好，不过未来就不好说了。

## 教程

[Apple TV Tech Talks Videos](https://developer.apple.com/videos/techtalks-apple-tv/)


从去年开始 Apple 在世界各地的 Apple Store 举办了多场 Apple TV 的技术培训，向开发者介绍 Apple TV 开发的必备技术和注意事项。现在 Apple 将这些演讲的视频进行了公开，所以如果你没有能够到现场参加的话，这是个补课的好机会。

[MLeaksFinder：精准 iOS 内存泄露检测工具](http://wereadteam.github.io/2016/02/22/MLeaksFinder/)

在 iOS 开发中，稍不注意就会导致内存泄露的问题，MLeaksFinder 相较于 Instrument，为我们提供了更方便易用的内存泄露检测方案。这篇文章介绍了该工具的使用方式。

[@Swift 会议视频](http://www.imooc.com/learn/600)

今年一月在北京召开了由开发者举办且面向开发者的国内首次 Swift 技术会议。在会议上 8 位演讲者为我们从各个方面带来了一些他们在 Swift 实践中的心得体会。现在会议上各 session 的视频已经发布，如果你对此有兴趣的话，不妨去看看。

[Android：我为何要封装DialogFragment？](http://www.jianshu.com/p/af6499abd5c2)

Dialog 在实际使用中会存在一些问题，比如在手机配置发生变化后（比如屏幕旋屏），无法恢复Dialog的状态。DialogFragment是在 Android3.0被引入的，从其名字可以很直观的看出它是一种基于Fragment的Dialog，可以用来创建对话 框，DialogFragment是用来替代Dialog的。本文作者解释了为什么抛弃Dialog而使用DialogFragment，并且详解了对 DialogFragment的封装过程。

[Android Support Library 23.2介绍](http://2.rogerbolg.sinaapp.com/?p=191)


上周Google发布了Android支持库的23.2版本。当我们说起 Android Support Library时，必须清楚的认识到这不仅仅只是一个库，而是一个能对API向后兼容的，提供独特的功能而不需要最新平台（plathform）支持的库的集合。23.2版本在许多现有库的基础上增加一些新的支持以及功能。本文是对该库的一个简单介绍，有助于我们更加了解该库的新特性。

[开发一流的Android SDK：Fabric SDK的创建经验](https://realm.io/cn/news/oredev-ty-smith-building-android-sdks-fabric/)

Twitter的Fabric是知名的注重质量的SDK，并已部署在数十亿的设备。来自Twitter的Ty Smith，揭示了Fabric团队创建Fabric的各种原则，特别是在Android方面。通过深入参与技术决策团队，Ty了解到很多信息，他展示了
团队在创建这个SDK过程中学到的各种经验心得，关于稳定性、性能、SDK体积控制、以及对于一些特殊情况的处理这些方面。无论你现在或将来想要建设一个SDK，通过本文（文中附视频）你将收益很多关于设计SDK的伟大想法。

[最详细的Toolbar开发实践总结](http://www.jianshu.com/p/79604c3ddcae)


Toolbar 是在Android 5.0开始推出的一个Material Design风格的导航控件，Google强烈推荐大家使用Toolbar来作为Android客户端的导航栏，以此来取代之前的Actionbar。与 Actionbar相比，Toolbar明显要灵活的多。它不像Actionbar一样，一定要固定在Activity的顶部，而是可以放到界面的任意位 置。除此之外，在设计Toolbar的时候，Google也留给了开发者很多可定制修改的余地，这些可定制修改的属性在API文档中都有详细介绍。本文详 细讲解了Toolbar的使用方法，能够帮助我们快速上手Toolbar。

## 开源项目

[Kitura](https://github.com/IBM-Swift/Kitura)

自 Swift 开源并能运行在 Linux 系统后，使用 Swift 写服务器的热潮就没有退却过，大家都在期待这门为 app 而生的语言在其他方面会有何表现。本周 IBM 公开了 Kitura 项目，这是另一个使用 Swift 架构的服务器框架。相比于其他的框架，Kitura 更注重中间件的结构，并且有大企业进行维护，相信质量也会很有保证。

[Vinyl](https://github.com/Velhotes/Vinyl)

网络请求可能是绝大多数 app 中一定会用到的，如何对网络部分进行可靠的单元测试一直不简单。因为服务器端的实现经常会发生变化，因此传统的使用 mock 和 stub 的方式测试网络实际上并不能保证当前网络部分的正确性。Vinyl 借鉴了 DVR 和 VCR的思路，来保证你的测试可以与服务器实现同步。

[RealReachability](https://github.com/dustturtle/RealReachability)

监视网络状况的改变并在 UI 上进行合适的对应，可以提供良好的用户体验。我们一般都使用 Reachability 来对网络状况进行监视。但是现有方案存在一个问题，那就是它只监视本地连接是否有效，而并不关心到远端的网络连接是否真的能接收到数据。RealReachability 就是为了解决这个问题的改进版实现，它使用 ping 模型来保证本地连接和到远端的连接是同时有效的，相比原版是一种更可靠的方案。项目作者还在本公众号讲述了具体的原理和使用，查看历史文章可见。

[Greedo Layout](https://github.com/500px/greedo-layout-for-ios)

500px 开源的一个根据图片大小来计算 colloection view cell 尺寸的框架。它会保证 cell 的高度一致，然后依据图片尺寸进行合适地缩放。相比起常见的瀑布流的 collection view 布局，这种方式可以让图片展示页面显得更有序。如果有在做图片展示 app 的话，可以作为不错的参考。

[Douya](https://github.com/DreaminginCodeZH/Douya)

Douya是一款开源的豆瓣客户端，项目采用了Material Design的设计风格。

[SwipeCardView](https://github.com/xiepeijie/SwipeCardView)

SwipeCardView是一个带渐变层叠动画的左右滑动效果（类似于探探左右刷脸效果）。

[CoolAndroidAnim](https://github.com/TomWithJerry/CoolAndroidAnim)

一个酷炫的android loading效果，作者的想法来源于nexus6.0系统的开机动画，也是对于它的一个模仿：从四个小球的 不同的组合动画演变成loading字样的效果。
