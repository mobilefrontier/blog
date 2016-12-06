+++
title = "移动开发每周阅读清单：第八期"
date = "2016-04-18T21:33:45+08:00"
description = "『移动开发每周阅读清单』第八期与大家见面了，本周工作模块我们推出了几个重量级的开发岗位，薪资丰厚，欢迎关注~"
tags = ""
+++

『移动开发每周阅读清单』第八期与大家见面了，本周工作模块我们推出了几个重量级的开发岗位，薪资丰厚，欢迎关注~

## 新闻

[Swift 项目合并 Android 分支](https://github.com/apple/swift/pull/1442)

在今年二月，Facebook 的工程师 [Brian Gesiak](https://github.com/modocache) 向 Apple 提交了一个 pull request，将 Swift 的标准库移植到了 Android 上。这样开发者可以使用 NDK 的方式在 Android 上调用 Swift 编译的内容。本周 Apple 将这些代码合并到了 Swift 仓库中，这意味着我们可以在不久的将来在 Android 上运行 Swift。但是值得指出的是，这并不代表我们现阶段可以很好地使用 Swift 来开发 Android 应用，在 SDK 调用和开发模式的匹配上，仍然会有很多工作要做。

[Apple 可能正在策划推出 App Store 付费排名](http://daringfireball.net/linked/2016/04/14/bloomberg-app-store-search)

国外有[消息](http://www.bloomberg.com/news/articles/2016-04-14/apple-said-to-pursue-new-search-features-for-crowded-app-store)指出，Apple 可能在考虑将竞价排名或者付费关键词搜索加入到 App Store 的搜索体系中。根据现有消息，App Store 的付费排名可能采取和 Google 搜索的关键字购买类似，开发商对某个关键字进行购买，并让自己的 app 出现在搜索前列。如果消息属实，那么这对整个 App Store 生态将产生相当大的影响。

[Android N将引入3D Touch功能](http://www.leiphone.com/news/201604/9ymkFDkLGU2mM5ZV.html)

在最新的Android N开发者预览版中，代码显示Android即将引入类似苹果3D Touch的功能。有开发者已经模拟出了这项功能。这让外界得以了解谷歌对于压力感应技术的想法。由于目前尚无支持3D Touch功能的Android硬件设备面市，因此这名开发者在模拟中利用了对图标的长按和下滑操作。谷歌的文档显示，3D Touch只对应用图标本身，或谷歌所说的“启动器快捷方式”有效。

## 教程

**iOS**

[iOS 关于navigationBar的一些：毛玻璃、透明、动态缩放、动态隐藏](http://www.jianshu.com/p/b2585c37e14b)

关于 iOS 中的导航栏自定义相关技术，在 iOS 7 改变整体风格以前就是一个热门话题。而在 iOS 7 加入半透明效果和重新定义了视觉元素之后，导航栏的显示和动态特效自定义需求则更加复杂。这篇文章对导航栏的常见自定义效果进行了一些整理和示例说明。

[Custom UIViewController transitions in VIPER](https://swifting.io/blog/2016/04/11/12-custom-uiviewcontroller-transitions-in-viper/)

ViewController 转场的 API 在 iOS 7 被引入到 iOS SDK 中，从此开发者可以方便地控制和自定义转场的效果。如果你对 VIPER 或者其他一些非 MVC 的架构方式有一定了解的话，会知道其实采取这些非 MVC 的方式时，和 CocoaTouch API 进行交互会有一些额外需要注意的事项和技巧。这篇文章就为我们说明了如何在一个 VIPER 架构的项目中使用 ViewController 转场相关的 API。如果你有意尝试新的架构方式的话，这可能会对你有所启发。

[Powerful private methods for debugging in Cycript & LLDB](http://iosre.com/t/powerful-private-methods-for-debugging-in-cycript-lldb/3414)

使用 LLDB 进行 app 调试可以说是广大 iOS 开发者的日常必备技能了，而相比起来，知道或者熟悉 Cycript 的开发者就会少很多。[Cycript](http://www.cycript.org) 是一款能在越狱设备上对运行时进行注入的调试工具，你可以用它来对 app 进行探索。这篇文章为我们介绍了一些调试时很有用，但却鲜为人知的命令。

**Android**

[Android插件化原理解析——广播的管理](http://weishu.me/2016/04/12/understand-plugin-framework-receiver/)

本文介绍了BroadcastReceiver组件的插件化方式。作者通过大量的篇幅讲述了BroadcastReceiver的原理，通过对广播原理的解读，引出了BroadcastReceiver插件化方案的实现方法。插件方案对于BroadcastReceiver的处理相对简单，同时静态广播非静态的特性以及BroadcastReceiver先天的一些特点导致插件方案没有办法做到尽善尽美。不过在绝大多数情况下，文章中提到的的处理方式是可以满足需求的。阅读文章，看看作者是如何实现BroadcastReceiver的插件化。

[Android项目使用Dagger2进行依赖注入](http://joggerplus.github.io/2016/04/14/using-dagger.html)

从事Android开发的同学几乎都听说过大名鼎鼎的Dagger2。本文讲解了Dagger2的一些使用方法。依赖注入是一个模式，如果你还没有使用它，那么在你的应用中迟早会用到该模式。

[如何提升Android代码的质量和语法](https://mp.weixin.qq.com/s?__biz=MzA4MjU5NTY0NA==&mid=405869129&idx=1&sn=7e741439b66095f9b72152d02d226a75)

本文介绍了通过自动化工具提高Android代码质量的几种不同方式，包括 Checkstyle， Findbugs， PMD，当然，还有我们最熟悉的Android Lint。为了让代码保持缜密的语法，同时避免一些糟糕的实现和错误，使用自动化的方式测试代码十分有用，尤其是协作开发的时候。文章中也介绍了如何直接通过你的Gradle构建脚本使用这些工具。

## 开源项目

**iOS**

[EasyPeasy](https://github.com/nakiostudio/EasyPeasy)

另一个用来简化创建布局约束的框架，EasyPeasy 使用了更简洁和智能的约束描述语法来创建约束，并提供了很多便利的方法和属性辅助我们以更加直观的方式用纯代码使用 AutoLayout。如果你不使用 Interface Builder，而是选择在源代码中创建视图和约束的话，这个框架可以帮助你节省很多时间。

[TextAttributes](https://github.com/delba/TextAttributes)

Cocoa 框架中有一些使用起来会令人抓狂的 API，`NSAttributedString` 就是其中之一。想想看要创建一个带有格式的字符串是多困难吧：寻找 `Range`，指定属性，创建配置字典等等。Cocoa 这样设计 API 可以最大限度保证松耦合，确实有其优势。但是作为 API 的使用者，这样的接口使用起来并不是特别方便，而且并不太适合 Swift 的强类型约束。TextAttributes 框架将这些松耦合的接口进行了重新封装，使其类型更加安全，也使得原有的 API 更易用一些。

[Peek](https://github.com/shaps80/Peek)

一个可以在开发时截取当前界面，并且对界面里的视图进行检测和查看的框架，你可以把它理解为可以运行在 iOS 上的 [Reveal](http://revealapp.com)。通过集成 Peek，你可以快速确认界面布局是否满足设计师的需求，也可以在运行时确认某个 view 的状态是否和预想一样。

[FBMemoryProfiler](https://github.com/facebook/FBMemoryProfiler)

Facebook 出品的一个实时监测内存使用的库。相比于 Xcode 自带的 Instruments，这个框架提供了更友好的信息，包括当前没有释放的对象以及 retain cycle 的详细信息等。这个工具是高度模块化的，你可以选择自己感兴趣的部分使用，比如要是你只想要检测 retain cycle 的话，可以只需要使用 Facebook 同时公布的这个项目：[FBRetainCycleDetector](https://github.com/facebook/FBRetainCycleDetector)。

**Android**

[folding-cell-android](https://github.com/Ramotion/folding-cell-android)

这个项目实现了折叠效果的Cell，动画效果很赞。

[FlexLayout](https://github.com/mmin18/FlexLayout)

FlexLayout是最近比较火的一个开源项目，有了FlexLayout，开发者可以用类似于Java的语法来写布局文件。FlexLayout也可以实现一些LinearLayout、RelativeLayout无法实现的功能。这里是一篇关于RelativeLayout， FlexLayout及其它Layout性能对比的文章。

[redex](https://github.com/facebook/redex)

ReDex是Facebook开源的工具，通过对字节码进行优化，以减小Android Apk大小，同时提高App启动速度。这里是一篇介绍Redex的文章。

## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**高级Android/iOS开发 by 菜鸟网络**

杭州北京两地。菜鸟与大淘宝、蚂蚁金服共同组成阿里电商的铁三角，旨在建设一个数据驱动、社会化协同的物流及供应链平台。20k-40k，16-19薪，外加期权。简历投递邮箱 trinea.cn@gmail.com

**高级IOS/Android开发工程师各1名 By 猎头渠道**

地点上海张江。主要是做online learning的平台, 有一定的英文要求, 薪资最高到450K/Y, 详细请发送简历到 bendypan@silverlightjob.com 秒回复,谢谢!

**资深iOS/Android专家 By 阿里聚划算**

阿里社招岗位，地点杭州。5年工作经验3年移动经验以上，负责技术攻坚，SDK开发、核心业务开发。职级P7、P8，薪资面议。简历请投至 mazhao.mz@taobao.com

## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[GMTC全球移动技术大会](http://gmtc.geekbang.org/)

6月24-25日北京举办。上周新增两位讲师，阿里B2B国际技术部高级iOS工程师杨显涛，给大家分享的是《360°全景视频播放器的实现原理》，ThoughtWorks高级咨询师、移动架构师傅若愚，分享《函数式编程中的Swift与Swift中的函数式编程》。本周最后6折促销期间，5人以上团购更多优惠，欢迎购票参加。

[2016 Women Techmakers 谷歌女性开发者节](http://mp.weixin.qq.com/s?__biz=MzA5MDg3MjczMg==&mid=2652003382&idx=1&sn=1cf86dffae3b0b0ed1fed5694411c986&scene=0#wechat_redirect)

4月24日北京举办。WTM 是谷歌在全球发起的女性开发者项目，希望为更多的科技行业女性从业者提供更多的资源和更开阔的视野，帮助她们在工作上获得更大提升，项目面向所有的女性工程师、设计师、创业者。男性请在任一位女性友人陪同下入场。

+++

上周移动开发前线公众号精彩文章：

* [Android官方MVP架构示例项目解析](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=403539764&idx=1&sn=d30d89e6848a8e13d4da0f5639100e5f#rd)
* [实战Kotlin@Andorid（二）：界面构建与扩展方法](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=403568637&idx=1&sn=e6edfa6ef2029e0f6c1892ed7d2611d2#rd)
* [使用React Native开发F8 App实战教程（一）](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=403628431&idx=1&sn=8384dc0956e12dbbbce3982bb2a85cee#rd)
* [React Native 蛮荒开发生存指南](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112082&idx=1&sn=11c40b90e8efe8c209674dd23402376e#rd)
* [群分享：iOS遗留系统重构实践](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112090&idx=1&sn=7e00d0da704f99ef93ffd815731f1fd9#rd)

阅读更多移动开发好文，欢迎关注『移动开发前线』公众号。
