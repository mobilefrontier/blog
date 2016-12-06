+++
title = "移动开发每周阅读清单：第十五期"
date = "2016-06-06T21:33:45+08:00"
description = "『移动开发每周阅读清单』第十五期与大家见面了，下周就是WWDC了，除了我们都已经知道的Swift 3.0，不知道苹果这次会给开发者带来什么惊喜呢？请拭目以待。"
tags = ""
+++

『移动开发每周阅读清单』第十五期与大家见面了，下周就是WWDC了，除了我们都已经知道的Swift 3.0，不知道苹果这次会给开发者带来什么惊喜呢？请拭目以待。

## 新闻

[WWDC 16 临近，Apple 推出新的 WWDC 应用](http://www.macrumors.com/2016/06/03/apple-updates-wwdc-app-for-2016/)

WWDC 16 将于一周后召开，最近 Apple 升级了 WWDC 的应用。新版本中采用了开发者们普遍喜爱的暗色主题，你也可以使用这个应用下载和观看之前几年的 WWDC 视频。除此之外，新版本还支持新一代的 Apple TV，也针对 iPad 进行了多任务的适配。

[Swift 3.0 Preview 1 短暂发布后被撤回](https://swift.org/download/#releases)

WWDC 16 上应该会公布 Swift 3.0 的相关消息。本周，Apple 曾经发布了第一个 Swift 3.0 的预览版本，其中这一年来的大部分被接受的提案都已经被实现了。但是随后这个版本就被替换回了 2.2 的开发分支的快照版本。可能最终 Swift 3.0 预览版还是要等到 WWDC 召开才会和 Xcode 8 beta 一同发布，如果你有计划将应用或者框架尽快升级适配 Swift 3.0 的话，最好尽早开始准备和关注。


[中文Android 7.0体验：改进不明显，升级需慎重](http://www.ithome.com/html/android/230173.htm)

谷歌早前已经放出了Android N（安卓7.0）的第三个预览版，整体功能改进已经成形，之后应该就只是小修小补了。Android 7.0的一些重要改进包括多任务窗口模式、快速回复通知消息、DayDreamVR模式（目前还不能体验）、快速切换最近应用、新Emoji等，那么现在值不值得升级呢？国内已经有人体验了升级Android N后的Nexus6P，得出的结论是目前该版本还存在较多的bug，并且相较国内其它ROM功能改进并没有新意，建议用户谨慎升级。


## 教程

**iOS**

[使用 CocoaPods 模块化iOS应用](http://www.jianshu.com/p/a8db4fa6d155)

很多开发者会使用 CocoaPods 来作为第三方框架的依赖管理工具，但是 CocoaPods 的用途绝不仅限于此。我们可以在开发中将复杂的程序的各个模块进行拆分，以降低开发难度和代码耦合，然后使用 CocoaPods 把这些模块聚合在一起，来构建更完整和强大的应用程序。这篇文章就针对 CocoaPods 的该使用场景进行了介绍。

[iOS 启动连续闪退保护方案](http://wereadteam.github.io/2016/05/23/GYBootingProtection/)

iOS 应用有时可能遇到启动必 crash 的绝境：也就是每次打开应用都闪退，无法正常使用。这可以说是最差的用户体验，也必然意味着很多一星评论。尽量避免这种情况的发生，或者当发生启动时崩溃的时候，采取一些补救措施，可能可以挽救你的应用的口碑。本文介绍了一种对连续闪退问题的产生原因进行检测和修复机制方式，通过引入 GYBootingProtection，可以让你的应用具备一些自修复的功能。

[Avoiding the overuse of @objc in Swift](http://www.jessesquires.com/avoiding-objc-in-swift/)

作者在迁移到 Swift 2.2 的过程中发现了新加入的 `#selector` 语法和原来的 `Selector("method:")` 的不同。对于纯 Swift 的内容，如果不添加 `@objc` 的话将失去一些与 Objective-C 运行时相关的特性。但是 `@objc` 关键字又很容易扩散到项目的其他地方，作者通过组合两个协议来巧妙地实现了原来的意图。

**Android**

[深入浅出Retrofit](https://mp.weixin.qq.com/s?__biz=MzA3NTYzODYzMg==&mid=2653577186&idx=1&sn=1a5f6369faeb22b4b68ea39f25020d28&scene=1)

Android开发中，从原生的HttpUrlConnection到经典的Apache的HttpClient，再到对前面这些网络基础框架的封装，比如Volley、Async Http Client，Http 相关开源框架的选择还是很多的，其中由著名的Square公司开源的Retrofit 更是以其简易的接口配置、强大的扩展支持、优雅的代码结构受到大家的追捧。本文详细解析了Retrofit的使用方法及实现原理。

[Android用户引导库MaterialIntroView使用及源码分析](http://www.jianshu.com/p/1d2dcbc1e0f2)

由于新功能引导在各个发布版间表现各异，几乎难以统筹。其次，功能引导具有塑造艺术的可能，直接导致每一个版本都需要单独沟通，而且变更几率较大，难以一次性审校通过。MaterialIntroView是一款能解决这个痛点的开源项目，本文介绍了MaterialIntroView的实现原理。

[浅谈AndroidTV开发与常规APP开发的异同点](http://blog.csdn.net/u012673089/article/details/51592352)

如今Android电视、Android盒子已经逐渐被人们接受，国内已经有多家厂商生产这些产品。随着Android TV销售渠道的打开，开发TV App必然是另一个新的机会。虽然手机App与TV App都是基于Android SDK进行开发，但也有一些不同之处，本文作者根据自己几个月的TV App开发经验，总结了一些AndroidTV开发与常规APP开发的异同点。

[如何调试Android Framework？](http://weishu.me/2016/05/30/how-to-debug-android-framework/)

要想精通Android开发，仅仅能熟练使用SDK是远远不够的，Android Framework层的知识是也必须学习。学习Framework层有助于我们理解Android的运行机制，能够帮助我们写出更加高效、优雅的代码。学习Framework层时，调试技能显的尤为重要，本文为大家介绍了如何调试Android Framework。

## 开源项目

**iOS**

[ScrollableGraphView](https://github.com/philackm/Scrollable-GraphView)

一个非常漂亮的带有动画的图表框架。你可以用它来制作无限滚动的条形图或者曲线图。该框架也提供了很多可自定义的要素，使用起来非常容易。这个框架很适合用来进行简单的数据展示，原型设计等。

[Stellar](https://github.com/AugustRush/Stellar)

Stellar 是一个 Swift 的物理动画框架，它基于 Apple 的 UIDynamic，并对其进行了一些高层次的封装，是我们能以很简单的 API 来制作常见的动画效果。这个框架使用了类似 Promise 的层联方法来组织动画，并且全面适配和利用了 Swift 的语法特点。同时，框架还为我们提供了一些 Playground 的例子，让我们能够很直观和迅速地调试动画，非常方便。

[Atlas](https://github.com/layerhq/Atlas-iOS)

如果你需要在应用中制作一个和系统的信息应用类似的交流工具的聊天界面的话，Atlas 可能会是最快的选择了。你可以通过简单地实现 Atlas 的 data source 来迅速搭建一个聊天界面，也可以使用内建的众多组件来实现像是联系人查找，消息排序等功能。如果有需要，你也可以对界面元素进行自定义，以满足业务需求。

**Android**

[RocooFix](https://github.com/dodola/RocooFix)

该项目是HotFix项目作者的又一新作。之前的HotFix项目太过简单，也有很多同学用Nuwa遇到很多问题，作者也不再修复，所以重新构建了一套工具。

[material-tip](https://github.com/fcannizzaro/material-tip)

这是一个自定义的选择提示框，根据Google的[offer education](https://www.google.com/design/spec/growth-communications/onboarding.html#onboarding-quickstart)编写。

[material-design-dimens](https://github.com/DmitryMalkovich/material-design-dimens)

该项目封装了Material Design指南上要求的颜色、尺寸等信息。使用该项目可以让我们在适配Material　Design时，减少一些细节操作。


## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**iOS 高级/资深工程师 by 饿了么**

地点上海。要求能独立完成开发主管分配的开发任务，并对质量负责，参与iOS应用架构的设计和规范化工作。薪资面议。简历投递邮箱：zhongdan.wei@ele.me

## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[GMTC全球移动技术大会](http://gmtc.geekbang.org/?utm_source=zhoubao&utm_medium=xuachuan02&utm_campaign=0606)

6月24-25日北京举办。来自BAT、携程、滴滴、微博、和社区的技术专家联袂分享，主题包括应用架构、性能优化、动态化、插件化、Swift、React Native、Weex等，为中高级移动开发工程师献上一场技术盛宴！在『移动开发前线』公众号回复“大会”可获得购票优惠码。

----

上周移动开发前线公众号精彩文章：

* [2016年，你要学习这些移动开发技术](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112337&idx=1&sn=3f5e09f1894de4111c0e41d6f230d18a#rd)
* [Android新布局方式ConstraintLayout介绍与学习资料](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112342&idx=1&sn=7e8ceacb00e9facb2adc399d29ed99c1#rd)
* [LuaView：基于Lua的移动端跨平台动态化方案](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112345&idx=1&sn=a910fb11d5478acec4dd99dcd1967b44#rd)

阅读更多移动开发好文，欢迎关注『移动开发前线』公众号。
