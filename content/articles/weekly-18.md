+++
title = "移动开发每周阅读清单：第十八期"
date = "2016-06-28T21:33:45+08:00"
description = "『移动开发每周阅读清单』第十八期与大家见面了，上周由我们举办的GMTC全球移动技术大会顺利结束，没有到现场的朋友也不用着急，我们已经放出PPT，后续还会将演讲整理为视频和文字分享给大家。"
tags = ""
+++

『移动开发每周阅读清单』第十八期与大家见面了，上周由我们举办的GMTC全球移动技术大会顺利结束，没有到现场的朋友也不用着急，我们已经放出PPT，后续还会将演讲整理为视频和文字分享给大家。

## 新闻

[Apple 确认 iOS 10 Beta Kernel 未加密并非疏漏](http://www.macrumors.com/2016/06/22/apple-unencrypted-kernel-ios-10-intentional/)

本周，有开发者[发现](https://www.technologyreview.com/s/601748/apple-opens-up-iphone-code-in-what-could-be-savvy-strategy-or-security-screwup/) Apple 提供的 iOS 10 Beta 版本的 Kernel 部分没有进行加密，这和以往 iOS 系统的情况并不相同。未加密的 Kernel 将会使开发者和研究人员更容易明白 iPhone 的软件和硬件到底是如何进行交互的，也将导致漏洞更容易被发现。本周 Apple 确认 iOS 10 Beta 中未加密的 Kernel 是有意为之，这样 Apple 将可以借助研究者的力量提供更安全的系统。

[Android N或启用全新虚拟导航栏](http://www.cnbeta.com/articles/513873.htm)

Google预计在未来几个月发布Android操作系统的最新版本，而相关信息也逐渐开始在网络上传播开来。近日外媒Android Police曝光了Android N的虚拟导航栏，报道称截取自Google的下一代Nexus智能手机Marlin和Sailfish上。目前尚不清楚运行原生Android系统设备可以看到这个重新设计的导航栏还是仅限于两款Nexus设备 。

[GMTC全球移动技术大会2016PPT下载](http://ppt.geekbang.org/gmtc)

由InfoQ举办的全球移动技术大会（GMTC）已圆满结束，大会上数十位讲师进行了分享。大会涉及到了多个主题，干货满满，没有到现场参会的开发者可以通过本文的链接下载PPT来进行学习。

## 教程

**iOS**

[为什么objc_msgSend必须用汇编实现](http://tutuge.me/2016/06/19/translation-why-objcmsgsend-must-be-written-in-assembly/)

我们知道，在 Objective-C 中对于方法的调用最终会被转换为 `objc_msgSend` 的函数调用，而 `objc_msgSend` 是使用汇编实现的。不过，使用汇编的目的不仅仅是为了更好的性能，这篇文章为我们介绍了 `objc_msgSend` 实现的一些细节和它背后的考虑。

[UICollectionView: Unjustly Maligned](https://ashfurrow.com/blog/uicollectionview-unjustly-maligned/)

`UICollectionView` 是从 iOS 6 开始引入的用 Grid 来显示数据的一种 view。除了 Apple 提供的默认的 `UICollectionViewFlowLayout` 以外，开发者也可是实现自己的 layout 来进行各种各样的视图布局。`UICollectionView` 可能一直以来都被开发者和设计师忽视，很多时候我们会简单地使用 Table View 来展示数据。然而，为了灵活性和可扩展的考虑，无论何时你都应该优先考虑 `UICollectionView`。本文为我们展示了 `UICollectionView` 的强大之处，以及可以通过自定义 layout 所实现的一些漂亮的效果。

[What’s New in Swift 3?](https://www.raywenderlich.com/135655/whats-new-swift-3)

因为 Swift 3 是开源开发的，所以新版本中的变化大家都已经基本知道了。不过这篇文章还是对 Swift 3 的变化进行了很好的总结，如果你有项目需要从 Swift 2 迁移到 Swift 3 的话，读一读本文将会很有帮助。

**Android**

[微信Android热补丁实践演进之路](https://mp.weixin.qq.com/s?__biz=MzAwNDY1ODY2OQ==&mid=2649286306&idx=1&sn=d6b2865e033a99de60b2d4314c6e0a25&scene=0)

继插件化后，热补丁技术在2015年开始爆发，目前已经是非常热门的Android开发技术。其中比较著名的有淘宝的Dexposed、支付宝的AndFix以及Qzone的超级热补丁方案。微信对热补丁技术的研究并不算早，大约开始于2015年6月。经过研究与尝试现有的各个方案，微信团队发现它们都有着自身的一些局限性。微信最终采用不同于它们的技术方案，走出了自己的实践演进之路。

[理解Android Crash处理流程](http://gityuan.com/2016/06/24/app-crash/)

App crash， 对于Crash可分为native crash和framework crash（包含app crash在内），对于crash相信很多app开发者都会遇到，那么上层什么时候会出现crash呢，系统又是如何处理crash的呢。例如，在app大家经常使用try...catch语句，那么如果没有有效catch exception，就是导致应用crash，发生没有catch exception，系统便会来进行捕获，并进入crash流程。本文详细讲解了Android系统对于Crash的处理流程。

[Instant Run工作原理及用法](http://www.jianshu.com/p/2e23ba9ff14b)

Instant Run是Android Studio2.0新增的一个运行机制，在你编码开发、测试或debug的时候，它都能显著减少你对当前应用的构建和部署的时间。当第一次点击run、debug按钮的时候，程序启动时间和以前的一样。但以后每次修改代码点击run、debug按钮时，对应的改变将迅速的部署到你正在运行的程序上，传输速度快到你都来不及把注意力集中到手机屏幕上，它就已经做好相应的更改。本文分析了Instant Run的工作原理，该技术对于我们研究插件化有一定的帮助。

## 开源项目

**iOS**

[Save the Dot](https://github.com/JakeLin/SaveTheDot)

在 iOS 10 中 Apple 引入了 `UIViewPropertyAnimator`，它可以用来控制交互式的 `UIView` 属性动画。这个项目通过 `UIViewPropertyAnimator` 实现了一个通过 UIView 动画构成的小游戏。

[Potatso-iOS](https://github.com/icodesign/Potatso-iOS)

通过 iOS 9 Network Extension 构建的网络代理应用，可以监视和调试通过设备的网络请求。作为一个完整的 app，项目里对于各类第三方框架的使用，Model 的组织方式，以及网络部分的处理都十分值得学习。

[Cartography](https://github.com/robb/Cartography)

一个 Swift 的使用代码书写 AutoLayout 的框架。因为需要考虑到满足所有可能的需求，所以 Apple 自己的 AutoLayout 相关 API 相对起来使用比较麻烦，于是出现了不少对于原来 AutoLayout API 的封装，Cartography 就是其中之一。

[Preheat](https://github.com/kean/Preheat)

iOS 10 中 Apple 为 `UITableView` 和 `UICollectionView` 添加了预先获取 cell 的特性，这样在展示 cell 时我们可以在实际展示之前就提前对 cell 进行加载和布局。Preheat 和这个作用类似，它将在合适的时候询问 delegate 并让你提供机会进行提前处理。你可以将这个框架和一些图片加载的框架一起使用，在实际展示前就完成图片下载。

**Android**

[Android主要网络请求工具汇总](http://blog.androidone.io/?p=125)

本文汇总了常用的网络请求工具及其优缺点，大家可以根据自己的需求进行选择。

[MagicaSakura](https://github.com/Bilibili/MagicaSakura)

MagicaSakura是一款Android多主题框架，切换主题时无卡顿现象。

[BezierMaker](https://github.com/venshine/BezierMaker)

该项目实现了通过de Casteljau算法绘制贝塞尔曲线，并计算它的切线，实现1-7阶贝塞尔曲线的形成动画。

[StepView](https://github.com/baoyachi/StepView)

这是一款步骤跟踪指示器，可以进行自定义。




## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

本周工作推荐暂停，感兴趣的同学可以看看之前的推荐。

## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[中国移动互联网测试大会](http://www.bagevent.com/event/56573)

7月16日于北京举行。专注移动互联网测试技术的分享会，关注移动互联网质量的有志之士的集会。本次大会主题涉及移动端的自动化、持续集成、性能、安全等一系列测试领域，以及当下移动端最新最热最实用的测试技术交流分享。

[W3C中国十周年庆典](http://www.w3ctech.com/event/58)

7月9日于北京举行。由W3C成员向观众分享核心Web技术以及Web的未来。设计的领域包括区块链、VR、数据可视化、支付、物联网等等。

----
