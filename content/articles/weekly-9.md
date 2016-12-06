+++
title = "移动开发每周阅读清单：第九期"
date = "2016-04-25T21:33:45+08:00"
description = "『移动开发每周阅读清单』第九期与大家见面了，上周我在QCon上，后面我会将QCon移动相关的内容整理分享给大家~"
tags = ""
+++

『移动开发每周阅读清单』第九期与大家见面了，上周我在QCon上，后面我会将QCon移动相关的内容整理分享给大家~

## 新闻

[WWDC 16 将在 6 月 13 日举行，门票抽选已经结束](https://developer.apple.com/wwdc/)

一年一度的 Apple 全球开发者大会日程已经确定。WWDC 16 将于 6 月 12 日进行报到，并在 6 月 13 日开始的一周于美国旧金山举行。和往年一样，WWDC 16 的门票也采用抽选方式发售，并且抽选已经完成。WWDC 16 上预计会发布 iOS 和 OS X 的全新版本，以及很有可能公布新款的 MacBook Pro 和 Apple Watch 等。如果你足够幸运获得了今年 WWDC 的门票，不妨可以参考一下这篇[《写给初次参加 WWDC 的开发者的简明攻略》](https://onevcat.com/2016/04/first-wwdc/)尽早开始准备行程。

[谷歌I/O 2016大会日程公布：VR才是真正重头戏！](http://www.ithome.com/html/next/220169.htm)

即将于5月18日拉开帷幕的谷歌I/O 2016大会令人期待不已，除了一年一度的固定节目最新安卓系统（Android 7.0）外，谷歌今年似乎将更多重心放在了时下大热的VR领域。

## 教程

**iOS**

[探索 Swift 中的 MVC-N 模式](https://realm.io/cn/news/slug-marcus-zarra-exploring-mvcn-swift/)

MVC-N 模式是一种对 MVC (Model View Controller) 模式进行了扩展的设计模式，它使异步网络调用与用户界面控制器相互隔离，从而对 Controller 部分进行了一些分离和简化。相对于其他一些框架，MVC-N 所作出的变动和更改力度要小得多，因此也更容易应用在开发中，迁移起来也不会特别困难。通过将将网络访问代码抽离出来，形成单独的网络控制器抽象，可以让其他部分的重用和重构变得容易得多。

[Rejected Swift Proposals](http://chris.eidhof.nl/post/rejected-swift-proposals/)

Swift 开源后社区为 Swift 的进化和发展出谋划策，提出了很多的建议。在一些建议被采纳了，并且会出现在今后的 Swift 版本中，但是更多的还是被回绝了。这篇博客分析了几个呼声很高但是最后没有能成为标准的提案，并对它们进行了一些评论。

[巧用 Class Extension 分离接口依赖](http://blog.sunnyxx.com/2016/04/22/objc-class-extension-tips/)

Class Extension 和 Category 是我们经常使用的 Objective-C 语法，使用这些语言特性能够让我们以更优雅的方式组织代码并分离接口依赖。本文举了一个这方面的应用例子来对使用 Class Extension 的好处进行了解释。

**Android**

[如何给安卓APP安装听诊器，检查数据问题](http://www.figotan.org/2016/04/18/using-stetho-to-diagnose-data-on-android/)

从事移动端安卓App的开发，除了代码逻辑之外就是在和数据打交道。数据的输入输出，往返于网络接口之间，流窜于内存之中存储之内，不能像编写的代码那样直接在代码编辑器中看到其具体的内容。Stetho英译为“听诊”，是Facebook研发的安卓APP网络诊断和数据监控的框架，本文介绍了如何使用Stetho来窥探数据。

[【ReactNative For Android】框架启动核心路径剖析](https://mp.weixin.qq.com/s?__biz=MzI1MTA1MzM2Nw==&mid=2649796767&idx=1&sn=9a499453b627a223e0c2863658dd0329)

RN启动过程比较复杂，整个启动过程是先启动终端运行时，随后由终端上下文去启动JS的运行时，进而布局，最后再由终端进行渲染，最后将View添加到RootView上。本文来自QQ空间团队，文章结合源码，分析了ReactNative For Android的启动过程。

[Android单元测试（三）：JUnit单元测试框架的使用](http://www.chriszou.com/2016/04/18/android-unit-testing-junit.html)

我们写单元测试，一般都会用到一个或多个单元测试框架。JUnit4是Java界用的最广泛，也是最基础的一个框架，其他的很多框架，包括Robolectric，都是基于或兼容JUnit4的。本文介绍了JUnit单元测试框架在Android中的使用方法。

## 开源项目

**iOS**

[GPUImage 2](https://github.com/BradLarson/GPUImage2)

如果你在做图像处理相关的工作的话，一定不会回 [GPUImage](https://github.com/BradLarson/GPUImage) 这个强大的图像/视频处理框架陌生。GPUImage 2 是使用 Swift 对原来 Objective-C 版本的 GPU Image 进行的完全重写。得益于 Swift 的跨平台特性，现在 GPUImage 2 不仅可以运行在 iOS 和 Mac 上，你还能在 Linux 上使用它。Swift 的语言特性也在这个框架中得到了完美的诠释，相比于 Objective-C 版本，Swift 的新版代码量只有原来的四分之一，并且更加安全易用。GPUImage 2 的作者同时也发布了[一篇博客](http://sunsetlakesoftware.com/2016/04/16/introducing-gpuimage-2-redesigned-swift)来阐释 GPUImage 2 背后的一些思考。

[JSPatchX](https://github.com/bang590/JSPatchX)

[JSPatch](https://github.com/bang590/JSPatch) 可以让你用 JavaScript 书写原生 iOS app，在实际使用中，只需在项目引入极小的引擎，就可以使用 JavaScript 调用任何 Objective-C 的原生接口，获得脚本语言的优势：为项目动态添加模块，或替换项目原生代码动态修复 bug。这个项目是 JSPatch 的 Xcode 代码自动补全插件，使用这个插件，能让你在 Xcode 中很容易地书写 Javascript 的文件。

[The Swift Summary Book](https://github.com/jakarmy/swift-summary)

对于 Swift 入门和语法学习来说，Apple 的官方文档是很好的材料。但是文档存在内容较多，有时候阅读噪声太大的问题。这个 repo 提供了一系列 Playground 文件，集中地展示了 Swift 的基础语法特性。如果你有一些其他语言的使用基础，想要入门 Swift 的话，这些示例代码应该能够帮助你完成这个任务。

**Android**

[android-about-page](http://androidone.io/info_10169.html)

这是一个能够帮助我们快速创建关于页面的项目。

[AndroidDaemonService](https://github.com/D-clock/AndroidDaemonService)

该项目涉及到了进程保活的相关知识，介绍了如何让App合理并且优雅的保活。

[JKeyboardPanelSwitch](https://github.com/Jacksgong/JKeyboardPanelSwitch)

由于Android上的输入法太多，所以很多Android开发者都遇到过键盘冲突的坑。该项目给出了一种键盘面板冲突的布局闪动处理方案。


## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。


**Android高级开发工程师 by 深圳荷包金融信息咨询有限公司**

工作地点深圳。重视交互体验的p2p理财App，要求三年以上移动开发经验，有做过完整的产品迭代流程，薪资可达30W/Y，具体面谈。有意者发送邮箱至 wuyao@hebaodai.com

**高级iOS开发 by 亚信科技在线业务事业部**

地点北京。要求5年工作经验3年iOS开发经验以上，负责解决产品开发中的技术难题，对初/中级工程师提供技术指导。中级iOS开发职位要求至少2年iOS开发经验。每年至少14薪。有意请发简历至fzxm@foxmail.com可帮助内推。

**iOS高级工程师/iOS开发专家 by 阿里集团国际事业部**

地点杭州+深圳。工程师要求多个完整项目经验，专家要求5年以上开发经验。待遇20-50K。简历发到 blacktea.hw@alibaba-inc.com

## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[GMTC全球移动技术大会](http://gmtc.geekbang.org/?utm_source=zhoubao&utm_medium=xuachuan02&utm_campaign=0425)

6月24-25日北京举办。上周新增三位讲师，支付宝APP性能稳定性架构技术负责人石世群，宝宝树研发经理、《React Native入门与实战》第一作者王利华，澳洲房地产REA高级工程师李剑。本周起开始8折促销期间，5人以上团购更多优惠，欢迎购票参加。

[第二届中国移动互联网测试大会](http://www.bagevent.com/event/56573)

7月16日北京举办。面向移动测试和测试开发工程师。有来自阿里、eBay、360的专家分享。我去年参加了他们的第一届大会，有Appium的创始人前来分享，还是非常不错的。目前早鸟票开售中。

----

上周移动开发前线公众号精彩文章：

* [iOS瘦身之删除无用的mach-O文件](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112096&idx=1&sn=ce8fccce7d5f70e30c078e63e8ea0d15#rd)
* [包建强：为什么我说Android插件化从入门到放弃？](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112099&idx=1&sn=4f6f16f045ea80ce10bad67b85b10a7d#rd)
* [关于Weex你需要知道的一切](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112102&idx=1&sn=ec0575a61f4dabddf02cd40be569a794#rd)
* [实战kotlin@android（三）：扩展变量与其它技巧](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112113&idx=1&sn=e7e3cffe60150e7db20ebd4f648b4c15#rd)

阅读更多移动开发好文，欢迎关注『移动开发前线』公众号。
