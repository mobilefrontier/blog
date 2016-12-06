+++
title = "移动开发每周阅读清单：第三期"
date = "2016-03-14T21:35:45+08:00"
description = "『移动开发每周阅读清单』第三期与大家见面了，上周移动领域让大家比较惊讶的就是Apple为WWDC 15添加中文字幕，以及Google提前发布了Android N预览版。"
tags = ""
+++

『移动开发每周阅读清单』第三期与大家见面了，上周移动领域让大家比较惊讶的就是Apple为WWDC 15添加中文字幕，以及Google提前发布了Android N预览版。

## 新闻

[Apple 为 WWDC 15 和 Apple TV Tech Talks 添加中文字幕](https://developer.apple.com/cn/)

观看 WWDC 的 session 视频一直是学习和提高 iOS 开发技术的最好途径。本周，Apple 为 WWDC 15 的所有 session 和前不久举行的 Apple TV Tech Talks 的视频添加了中文字幕，以方便中国开发者观看和学习。作为世界上最大的 iOS 开发者群体，中国的开发者们正在扮演者越来越重要的角色，同时也得到了越来越多的关注。

[2016 春季发布会时间确定，媒体已接收到邀请函](http://www.ithome.com/html/iphone/211055.htm)

Apple 2016 春季发布会的时间已经确定，发布会将于太平洋时间 3 月 21 日上午 10 点进行。这次邀请函上的标语是 “Let us loop you in.”，让人难以捉摸。本次发布会上确定会发布新的 9.7-inch iPad 升级版，新的 4-inch 手机 iPhone SE 以及一款新的 Apple Watch 表带。另外据称，即便不是立即发售，Apple 也很有可能在发布会上宣布新的 Mac 产品线的升级。

[Android N预览版已发布：分屏多任务功能是最大亮点](http://www.techweb.com.cn/world/2016-03-11/2294316.shtml)

谷歌近日发布了新的安卓系统开发者预览版，代号Android N，并正式面向开发者开放下载。目前发布的新功能中，分屏多任务应该是最大的亮点。Android掌门人Hiroshi Lockheimer在接受采访时表示：现在虽然还无法给出Android 7.0正式版发布的确切时间，但可以肯定的是，会比以往的时间早很多，预计在今年夏季。

[谷歌修正Android远程执行缺陷](http://app.myzaker.com/news/article.php?app_id=5&_appid=AndroidPhone&_version=6.43&_bsize720_1280&sharechannel=wx&pk=56de716e9490cba754000006)

谷歌发布了16 款Android补丁软件，其中包括一款修正媒体服务器中远程执行缺陷的补丁软件。更新包将通过无线方式发布给谷歌Nexus设备。谷歌向合作伙伴通报发布这些补丁软件的时间不晚于2月1日，使它们有逾1个月时间进行准备工作。

## 教程

**iOS**

[iOS VoiceOver Programming Guide](http://geeklu.com/2016/03/ios-voiceover-programming-guide/)

VoiceOver 是苹果“读屏”技术的名称，属于辅助功能的一部分。VoiceOver可以读出屏幕上的信息，以帮助盲人进行人机交互。 这项技术在苹果的各个系统中都可以看到，OS X，iOS，watchOS，甚至 tvOS。作为一个平时不太被我们关注的技术，大家可能对 VoiceOver 的使用和适配并不熟悉。本文介绍了 VoiceOver 相关的编程技术。

[View controller lifecycle behaviors](http://irace.me/lifecycle-behaviors)

本文扩展了 [Many Controllers Make Light Work](http://khanlou.com/2016/02/many-controllers/) 一文中对于拆分 View Controller 的想法，使用 behaviors 的方式对 View Controller 的生命周期方法进行了一些扩展。

[Being Lazy](http://alisoftware.github.io/swift/2016/02/28/being-lazy/)

lazy 关键字和 `LazySequence` 是 Swift 中延迟加载和运行的两种方式，合理使用 lazy 有时可以巧妙地绕开一些限制，并给出更优化的实现。本文解析了使用 lazy 的一些常见场景和方法。

**Android**

[EventBus3.0源码解析](http://yydcdut.com/2016/03/07/eventbus3-code-analyse/)

EventBus 是Android上的以发布\订阅事件为核心的库。事件 (event) 通过post()发送到总线，然后再分发到匹配事件类型的订阅者。订阅者只有在总线中注册了才能收到事件，注销之后就收不到任何事件了。 EventBus3与之前的相比，其主要差别在于订阅方法可以不再以onEvent开头了，改为用注解。本文针对EventBus源码进行了详解，能够帮助我们了解EventBus的工作原理。

[浅谈Android编程思想和架构](https://drakeet.me/mvp-and-thinking-in-android)

作者认为今年Android开发的技术趋势，一是RxJava会继续被更多人接受进而开始使用，二是谷歌花了不少心思的Data Binding很可能会迎来正式版，data binding是实现MVVM架构的重要组成部分，介于它还不够完善而且目前还无法提供双向绑定，暂时不太适合应用到生产环境。本文介绍了面向抽象编程、 面向接口的好处，文章中给出了作者对于接口、模块化、MVP的一些心得。

[由Android 65K方法数限制引发的思考](http://jayfeng.com/2016/03/10/%E7%94%B1Android-65K%E6%96%B9%E6%B3%95%E6%95%B0%E9%99%90%E5%88%B6%E5%BC%95%E5%8F%91%E7%9A%84%E6%80%9D%E8%80%83/)

65K 方法数限制应该是Android开发者遇到的最频繁的一个坑了。如果目前还没有，只要你的App一直在加新功能，迟早会有那么一天。解决65K方法数限制 的途径有好几种，特别是使用Android Studio的同学，简单配置就可以搞定。但解决了问题不代表找到了问题的原因，本文作者面对65K方法数限制给出了自己的思考，这种学习精神值得我们学习。

## 项目

**iOS**

[Injection Plugin for Xcode](https://github.com/johnno1962/injectionforxcode/)

一个通过注入 Objective-C 和 Swift 运行时来实现将对代码的修改动态反应到运行中的 app 中的 Xcode 插件。通过使用这个插件，你可以避免很多重新编译和运行，从而提高开发效率。

[navigation-stack](https://github.com/Ramotion/navigation-stack)

Push 的导航方式在 iOS 中十分常见，但是这种模式有一个比较致命的不足，那就是在导航栈十分深的时候，想返回到最初的 View Controller 将非常麻烦。这个框架提供了一种在导航栈中快速返回的方法，使用类似系统的 App Switcher 的视图，来方便用户进行迅速切换。

[Stevia](https://github.com/s4cha/Stevia)

AutoLayout 已经是现在 iOS 开发中的标配，但是如果不使用 Interface Builder 的话，代码使用 AutoLayout 是一件非常繁琐的事情。Apple 提供了一种[可视化的代码方式](https://developer.apple.com/library/prerelease/ios/documentation/UserExperience/Conceptual/AutolayoutPG/VisualFormatLanguage.html)来简化这个流程，然而也并不好用。这个框架巧妙地使用操作符重载的方法提供了一种类型安全的可视化语言的方式实现 AutoLayout。

**Android**

[Android_Data](https://github.com/Freelander/Android_Data/blob/master/Android-Librarys-Top-100.md)

本项目主要对目前GitHub上排名前100的Android开源库进行简单的介绍，排名是根据GitHub搜索 Java语言选择（Best Match）得到的结果，然后过滤了跟Android不相关的项目。

[HitBlockRefresh](https://github.com/Hitomis/HitBlockRefresh)

这是一个非常有意思的下拉刷新组件，下拉后支持两种模式：打砖块和打坦克。相信大部分的开发同学都玩过这种黑白游戏。

[PoiShuhui-Kotlin](https://github.com/wuapnjie/PoiShuhui-Kotlin)

这是一个用Kotlin写的简单漫画APP，项目功能比较完整，有助于我们学习Kotlin。
