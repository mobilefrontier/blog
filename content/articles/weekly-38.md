+++
date = "2016-12-06T23:07:47+08:00"
title = "移动开发每周阅读清单：第三十八期"
description = "Apple 在官网上发布了关于 iPhone 意外关机的调查结果，称：少数于 2015 年 9 月到 10 月期间生产的 iPhone 6s 设备中，某项电池元件被装进电池包之前在受控环境空气中暴露时间过长，使电池电量消耗速度快于正常水平，导致意外关机」并且强调这并不是安全问题，同时 Apple 称它们有意将 iPhone 设计为在某些情况下会自动关机，是为了保护零件不受损伤"
+++


## 新闻

[有关 iPhone 及意外关机的信息](https://support.apple.com/zh-cn/HT207414)

Apple 在官网上发布了关于 iPhone 意外关机的调查结果，称：少数于 2015 年 9 月到 10 月期间生产的 iPhone 6s 设备中，某项电池元件被装进电池包之前在受控环境空气中暴露时间过长，使电池电量消耗速度快于正常水平，导致意外关机」并且强调这并不是安全问题，同时 Apple 称它们有意将 iPhone 设计为在某些情况下会自动关机，是为了保护零件不受损伤。

[Android现新病毒，超100万账号被控制](http://www.leiphone.com/news/201612/RI7xjclktZ6NaNmN.html)

据外媒报道，互联网安全公司Check Point今日发布报告称，一款名为“Gooligan”的特洛伊木马程序将自己伪装成合法应用来入侵Android智能手机和平板，自8月份以来100多万个谷歌账号已被病毒控制。


## 教程

**iOS**

[用 Swift 搭建一个微型编译器](https://realm.io/cn/news/tryswift-samuel-giddins-building-tiny-compiler-swift-ios/)

对绝大多数开发者来说，尽管我们每天都要与编译器打交道，然而实际上编译器对我们来说仍然像一个神秘的黑盒。在本次 try! Swift 的分享中，Samuel Giddins 从头搭建了一个全新的微型编译器，用来编译他自制的一门编程语言，从而借此去学习编译器的基本工作机制。他还讲述了 Swift 是如何为复杂问题（例如语义解析、词法分析和代码生成）提供优雅的解决方案的。最后，我们将实现一门全新的编程语言，并完成对它的编译工作。

[真实世界中的 Swift 性能优化](https://realm.io/cn/news/real-world-swift-performance/)

有太多的因素会导致您的应用变得缓慢。在本次讲演中，我们将自底向上地来探索应用的性能优化。来看一看在真实世界中进行数据解析、数据映射和数据存储的时候，Swift 的特性（协议、泛型、结构体和类）是如何影响应用性能的，我们将确定影响性能提升的瓶颈所在，并体验 Swift 带来的「迅捷」体验。

[美团大众点评 Hybrid 化建设](http://mp.weixin.qq.com/s?__biz=MzA3NTYzODYzMg==&mid=2653578296&idx=2&sn=03cc579cb7e016f8bfd4ba994b0a5947)

本文介绍了美团大众点评为什么要做一个 Hybrid 化这样一个东西，以及美团大众点评在 Hybrid 上实践的一些方案。

[iOS 持续集成系列 - 自动化 Code Review](https://shengpan.net/auto-code-review/)

为了保证代码质量，Code Review 是非常重要的一环。细到 `*` 的位置是否正确，大到代码的结构是否符合了软件开发的一些基本原则，都在这项工作的范围内。受限于现实情况，大多数团队没有足够的时间进行 Code Review，那么只能把一部分 CR 工作交给计算机去完成了。本文介绍了如何使用 OCLint 搭配 CI 进行一部分的自动化 Review 。

[大规模重构——重写 Instagram Feed 的经验之谈](https://realm.io/cn/news/tryswift-ryan-nystrom-refactoring-at-scale-lessons-learned-rewriting-instagram-feed/)

在 Instagram 团队重写他们全新的 iOS Feed 的过程中，他们积累了大量的经验，遇到的坑无疑已经超出了他们的预料，比如说集合视图、差异化 (Diffing) 以及冗长代码所带来的危险之处。本文 Ryan Nystrom 向我们分享了如何才能进行一次成功的重构，并且向我们介绍了 Instagram 的一个很赞的开源组件：IGListKit。


**Android**

[ART下的方法内联策略及其对Android热修复方案的影响分析](https://mp.weixin.qq.com/s?__biz=MzAwNDY1ODY2OQ==&mid=2649286426&idx=1&sn=eb75349c0c3663f10fbdd74ef87be338)

为了解决ART模式下的占用Rom空间问题，Tinker曾经花了一个半月时间实现分平台合成。Android N后对内联的新发现，似乎再一次认证了"热补丁不是请客吃饭"这句话。研究或填坑的路可能永远不会停，但Tinker团队有决心与信心可以陪大家一起走下去。

[Android M封装过的运行时权限处理](http://www.jianshu.com/p/5675c5230052)

Android M运行时权限想必大家已经不陌生了。Google官方也提供了帮助处理的第三方库[EasyPermission](http://www.jianshu.com/p/2b3661928e66)。所有的封装和处理都是由开发中出现的各种问题而推动的。很明显，权限处理的代码缺点就是你不能处理一次就行了。本文对Android M的运行时权限进行了代码封装，有助于项目开发业务代码中大面积的出现重复的运行时权限处理代码.

[Android 应用内存泄漏的定位、分析与解决策略](http://www.jianshu.com/p/96c55ea3446e)

作者做内存泄漏分析的一些心得总结，包括流程、工具等。

[Android中的线程池使用](https://ghui.me/post/2016/11/thread-pool-in-android/)

线程池，顾名思义就是一个线程池管理一池子的工作线程（工作线程的数量依赖于具体的线程池实现）。线程池是一个强大的任务处理框架，它可以多个任务同时保存在队列中，支持任务取消，以及优先级切换。本文覆盖了线程池、线程池Executor，以及它们在Android中的使用，有助与我们了解线程相关的知识。

[轻松自制flyme悬浮球](https://halfstackdeveloper.github.io/2016/11/27/%E8%BD%BB%E6%9D%BE%E8%87%AA%E5%88%B6flyme%E6%82%AC%E6%B5%AE%E7%90%83/#more)

最早使用悬浮球的手机应该是苹果，现在市面上的大量安卓手机也都支持了该功能。并且功能比苹果的还要强大。可以左右滑动切换应用、上拉返回桌面、下拉打开通知栏、轻触返回等。本文是一篇关于制作类似于flyme悬浮球的教程，作者写的很详细，并且给出了示例代码。


## 开源项目

**iOS**

[10000-Animations](https://github.com/saitjr/10000-Animations)

项目作者正在用 10000 小时时间去完成各种动画，动画实现可以作为参考。

[PDFGenerator](https://github.com/sgr-ksmt/PDFGenerator)

简单易用的 PDF 生成 `UIImage` 框架。

[R.swift](https://github.com/mac-cain13/R.swift)

像 Android R 文件一样管理资源，安全地管理 UIStoryBoard UIImage 等资源。

[Snowflake](https://github.com/onmyway133/Snowflake)

Swift 中的 SVG 解析框架。

**Android**

[SwissArmyKnife](https://github.com/android-notes/SwissArmyKnife)

SwissArmyKnife是一款方便调试Android UI的工具，可以兼容所有Android版本，不需要Root权限。可以直接在Android手机屏幕上显示当前Activity中所有控件（不管是否隐藏）的边界，内外边距大小，每一个控件大小，图片大小，字体颜色，大小，以及自定义信息。

[ScrollablePanel](https://github.com/Kelin-Hong/ScrollablePanel)

这是一个实现了日历滑动效果的开源项目，支持左右、上下滑动。

[android-PageFlip](https://github.com/eschao/android-PageFlip)

这是一款基于OpenGL 2.0实现的3D切换效果。

## 工作

> 有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**移动架构师 by 饿了么**

坐标上海。负责移动产品架构设计，方案制定，技术可行性研究，性能优化和安全加固，以及难题攻关，新技术预研培训，Code Review等。要求本科学历，3年以上移动开发经验，精通iOS & Android开发。薪资面议。简历发送至 biao.hu@ele.me


## 活动

> 宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[中国技术开放日广州站](https://jinshuju.net/f/lV70qu#utm_source=infoq&utm_campaign=techday&utm_medium=wechat&utm_term=1125&utm_content=android)

12月9日广州举行。主题为移动开发前沿。我们邀请了来自腾讯、阿里、百度、唯品会的技术专家前来分享一线开发实践。
