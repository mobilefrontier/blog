+++
date = "2017-03-22T21:07:47+08:00"
title = "移动开发每周阅读清单：第四十八期"
description = "此前有消息称 Apple 会在 3 月份举办新品发布会，但现在看来， Apple 不准备“大动干戈”，而是采取直接线上发布的方式推出。可以基本确定会有中国红色调的新款 iPhone 7。"
+++


## 新闻

[Apple 新品线上发布：中国红 iPhone7、新款 iPad Pro](http://www.techweb.com.cn/tele/2017-03-21/2503004.shtml)

此前有消息称 Apple 会在 3 月份举办新品发布会，但现在看来， Apple 不准备“大动干戈”，而是采取直接线上发布的方式推出。可以基本确定会有中国红色调的新款 iPhone 7。

[安卓8.0多项新特性曝光：看片利器](http://www.ithome.com/html/android/298418.htm)

离Google I/O 2017开发者大会还有两个月左右的时间，该大会最大的看点就是下一代安卓系统Android 8.0，按照以往的传统其代号应该是Android O，“O”有可能是Oreo（奥利奥），但目前还无法确定。现在关于安卓8.0的传闻开始崭露头角了，最新的传闻来自外媒9to5Google。

## 教程

**iOS**

[Weex 是如何在 iOS 客户端上跑起来的](http://www.jianshu.com/p/41cde2c62b81)

近一年来，ReactNative 和 Weex 这些跨平台技术对 Native 开发者来说，冲击是巨大的。Native 在开发 App 的时候存在一些弊端，比如客户端需要频繁更新，iOS 更新时间还要受到审核的牵制等等。ReactNative 和 Weex 尝试解决这些痛点。本文将介绍 Weex 是什么、它的工作原理，已经 Weex 是如何在 iOS 上跑起来。

[IPAPatch: 免越狱调试、修改第三方App](http://media.weibo.cn/article?id=2309404086977153611942)

和 "HackingFacebook" 类似，"IPAPatch" 主要可以在第三方的 IPA 文件上 "添加" 自己的代码，并且无需越狱。本文介绍了 IPAPatch 的诞生及其作用，你可以了解其工作原理和使用方法。

[深入浅出 JavaScriptCore](http://www.jianshu.com/p/ac534f508fb0)

本文介绍了 JavaScriptCore 相关内容，包括与 Objective-C 交互、内存管理、多线程等内容。

[iOS 开发技术栈与进阶](http://blog.cnbang.net/tech/3354/)

当学习到一定阶段，可能会遇到如何进一步提高等问题，你可以从本文中了解到哪些可能需要锻炼、进一步地学习。

**Android**

[Android热更新方案Robust开源，新增自动化补丁工具](http://tech.meituan.com/android_autopatch.html)

Robust热更新系统借鉴Instant Run原理，实现了一个兼容性更强而且实时生效的热更新方案。其基本思路是，Robust热更新系统在一个方法的入口处插入一段跳转代码，当发现某个方法出现bug就跳转执行补丁中的代码，略过原有代码的执行，否则执行原有方法体逻辑。

[Android APP启动优化](http://wuxiaolong.me/2017/03/13/appStart/)

我们在点击桌面图标的时候，偶尔会出现一个白屏，然后才进入主界面，这是因为从桌面点击APP图标启动应用开始，程序会显示一个启动窗口等待Activity的创建加载完毕再进行显示。冷启动白屏持续时间可能会很长，这可是个槽糕的体验，本文给出了解决该问题的方案。

[加快apk的构建速度，如何把编译时间从130秒降到17秒](http://www.jianshu.com/p/53923d8f241c)

公司的项目代码比较多，每次调试改动Java文件后要将近2分钟才能跑起来，实在受不了。作者在网上找了一大堆配置参数也没有很明显的效果，尝试使用instant run效果也不怎么样，然后又尝试使用freeline编译速度还可以但是不稳定，每次失败后全量编译很耗费时间，既然没有好的方案就于是作者开始自己尝试做。本文的源码在[这里](https://github.com/typ0520/fastdex)。

[FlexboxLayout帮助您完成聪明的UI布局](http://mp.weixin.qq.com/s/w76l1fpbsEyWoowytDj0iw)

去年Google的I/O上发布了ConstraintLayout，使得开发者在构建复杂布局的同时能够让视图层级得到精简。它在 Android Studio的Visual Layout Editor中也同样可以使用。同时，Google开源了FlexboxLayout，使得 Android里的CSS Flexible Layout模块也能拥有同样强大的功能。本文详细介绍了FlexboxLayout的使用方法。

[美团点评移动网络优化实践](http://tech.meituan.com/SharkSDK.html)

网络优化对于App产品的用户体验至关重要，与公司的运营和营收息息相关。有两个公开的数据：页面加载超过3秒，57%的用户会离开。Amazon页面加载延长1秒，一年就会减少16亿美金营收。在美团点评，监控团队开发了基于端到端的客户端监控平台。端对端就是请求从客户端发出到服务端响应返回的整个过程。它区别于后台服务监控，是一种从用户角度观察到的真实体验监控。本文是美团网络优化的实践，对于我们进行相应优化很有参考价值。


## 开源项目

**iOS**

[TKeyboard](https://github.com/music4kid/TKeyboard)

将你的 mac 作为 iPhone 键盘开源项目。

[mingsmck](https://github.com/ming1016/smck)

Objective-C 工程分析工具。

[sde](https://github.com/jinmingjian/sde)

在 VSCode 上愉快地写 Swift 的插件，支持自动补全、编译、调试。

[spruce-ios](https://github.com/willowtreeapps/spruce-ios)

简洁轻量的动画库。



**Android**

[fastdex](https://github.com/typ0520/fastdex)

如果你忍受不了apk龟速的编译(尤其是项目中有多个dex)，fastdex可以帮助你加快apk生成过程。

[ancyShowCaseView](https://github.com/faruktoptas/FancyShowCaseView)

这是一个使用简单、可定制的高亮引导动画，可以使用在新功能的引导页位置。

[ExpectAnim](https://github.com/florent37/ExpectAnim)

效果很赞的一个滚动动画效果。

## 工作

> 有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

3月初我们发布了[移动开发前线招聘季活动](https://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651113136&idx=1&sn=8227a7c540cf1eadcbefd70036f4c8ce)，目前已有十多个职位发布，欢迎同学们到这里找工作，还有招聘需求的可以回复该贴，我会更新上去。

## 活动


> 宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[GMTC 2017全球移动技术大会](http://gmtc.geekbang.org/?utm_source=infoq&utm_campaign=bornmobile&utm_medium=wechat)

6月9日北京举行。关注移动、前端、跨平台、AI应用等多个技术领域、促进全球技术交流，推动国内技术升级。GMTC为期两天，面向移动开发、前端、AI技术人员，聚焦前沿技术及实践经验，打造技术人员的学习和交流平台。6折倒计时啦！

[QCon北京站2017](http://2017.qconbeijing.com/)

4月16日北京举行。明年第一场最值得期待的综合性技术大会。QCon内容源于实践并面向社区，演讲嘉宾依据热点话题，面向5年以上工作经验的技术团队负责人、架构师、工程总监、高级开发人员分享技术创新和最佳实践。

[第二届 @Swift 开发者大会](http://www.bagevent.com/event/378252)

5.13-14 在深圳举办。邀请到了 Uber 的 iOS 负责人，RayWenderlich CTO，CocoaPods 核心团队成员，Realm 核心成员，RxSwift 作者，Perfect 作者，唐巧，虾神，以及来自腾讯、Google、ThoughtWorks、美团、滴滴的技术大牛。输入邀请码「infoq」，每张票优惠 79 元，只能使用 50 次，先到先得。

[MTSC 2017第三届中国移动互联网测试开发大会](http://test-china.org/)

7月15日北京举行。MTSC是一个为期一天的围绕移动测试开发技术的非营利国际性技术大会，主要关注移动互联网和移动应用方面的测试开发技术。期间我们将邀请众多国内外顶尖的测试人员来分享他们的知识及对测试的独到见解。