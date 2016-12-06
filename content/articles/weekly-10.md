+++
title = "移动开发每周阅读清单：第十期"
date = "2016-05-03T21:33:45+08:00"
description = "『移动开发每周阅读清单』第十期与大家见面了，上周五一劳动节，不知道大家有没有好好放松自己呢~"
tags = ""
+++

『移动开发每周阅读清单』第十期与大家见面了，上周五一劳动节，不知道大家有没有好好放松自己呢~

## 新闻

[Xamarin 宣布开源](http://open.xamarin.com)

Microsoft 收购了使用 Mono 进行跨平台开发的工具提供商 Xamarin 后，与本周将 Xamarin 各部件进行了开源，其中也包含 [iOS 和 Mac 的相关组件](https://github.com/xamarin/xamarin-macios)。Xamarin 在之前完全变为免费，而本次的开源也预示了微软继续对这个项目进行开发和支持的愿景。对于同时开发 iOS 和 Android 应用的开发者来说，使用 C# 在同一个项目中对逻辑和 Model 部分进行开发维护是一件很吸引人的方式，而以 Xaramin 为代表的统一逻辑层以及各自原生的 UI 层在现在看来是一种相对稳定的跨平台开发方式。

[Apple 向开发者宣传 Apple Music API](https://affiliate.itunes.apple.com/resources/documentation/apple-music-best-practices-for-app-developers/)

Apple 在 [iOS 9.3](https://developer.apple.com/library/ios/releasenotes/General/WhatsNewIniOS/Articles/iOS9_3.html) 中新加了 `SKCloudServiceController` 在内的一系列访问和更新 Apple Music 的功能，但是因为是在小版本中进行的更新，对于开发者来说缺少学习和了解的机会。为了让更多开发者及时了解相关 API 的信息，Apple 本周制作了一个介绍 Apple Music 相关 API 使用方法的网页，并通过邮件的方式通知开发者。如果你需要在项目中涉及访问或者操作 Apple Music 的话，可以关注一下。

[谷歌低调推进Android Auto 已有百款车型支持](http://digi.tech.qq.com/a/20160502/004625.htm)

Android Auto是一款谷歌为汽车开发的操作系统，用户需要用5.0版本以上的Android系统智能手机连接到Android Auto平台，激活内置的车载娱乐系统。在过去的一年里，Android Auto已经有了很大程度的发展，许多汽车厂商都计划为自己的产品增加这一系统，并且支持的车型也在逐渐增加。

## 教程

**iOS**

[ReactiveCocoa vs RxSwift](https://www.raywenderlich.com/126522/reactivecocoa-vs-rxswift)

自从 ReactiveCocoa 以来，响应式函数式编程一直被不少开发者使用和喜爱。相对于命令式的编程方式，响应式编程在处理用户响应和事件流上天生的优势在不少时候能够简化代码，提高可读性。而在 Swift 中，后起之秀 RxSwift 更是抢尽风头。这篇文章为我们对比了 ReactiveCocoa 和 RxSwift 各自的优势和适用场景，如果你正打算在项目中尝试响应式编程的方法，这篇文章可能可以为你的基础框架选择提供一定建议。

[去model化和数据对象](http://casatwy.com/OOP_nomodel.html)

在我们构建项目时，一般都会有一个 Model 层来存储和表示数据。在应用的各组件或者各层中，我们是否应该直接传递这个 model 对象，是一个很重要的选择。因为对于 model 对象的传递，往往意味着向我们的代码中引入新的依赖，这在有些时候可能不是我们想要的结果。本文分析了在数据传递时的“去 Model 化”的一些想法以及对应的替代方式，如果又需要，可以在进行架构设计时进行参考。

[聊聊 Swift 3.0 - 新版本对我们的影响](http://swiftcafe.io/2016/05/01/swift3/)

随着 WWDC 16 的临近，Swift 3.0 也将很快与我们见面。得益于 Swift 的开源和详细的发展进程表，我们可以提前预知 Swift 3 中稳定的 ABI (Application Binary Interface)、更加简洁的新 API 规范、更完善的跨平台支持等特性。新版本中的这些变化到底意味着什么，会对我们的开发产生什么影响，这篇文章从这些方面着手为我们进行了一些分析。

[Xcode Search: the Hidden Gems](http://holko.pl/2016/04/26/xcode-search/)

Xcode 应该是大多数 iOS/Mac 开发者日常工作中最常用的 IDE 工具了。Xcode 其实为我们提供了十分强大的搜索功能，包括像是使用 Pattern 搜索、只搜索定义、自定义搜索范围等等特性。这篇文章为我们列举了那些不太常用但是绝对有效的提高我们搜索效率的方法，如果你经常困扰于使用 Xcode 的搜索却找不到想要的代码的话，这篇文章绝对值得一读。

**Android**

[Android性能优化典范 - 第5季](http://hukai.me/android-performance-patterns-season-5/)

这是Android性能优化典范第5季，文章共10个段落，涉及的内容有：多线程并发的性能问题，介绍了AsyncTask，HandlerThread，IntentService与ThreadPool分别适合的使用场景以及各自的使用注意事项，这是一篇了解Android多线程编程不可多得的基础文章，清楚的了解这些Android系统提供的多线程基础组件之间的差异以及优缺点，才能够在项目实战中做出最恰当的选择。

[关于 Android N 那些你不知道的事儿](http://bugly.qq.com/bbs/forum.php?mod=viewthread&tid=894)

今年3月，Google破天荒提前半年发布了Android N开发者预览版。本文分析了Android N的新特性，内容详细并且分析的全面到位。

[Android drawable微技巧，你所不知道的drawable的那些细节](http://blog.csdn.net/guolin_blog/article/details/50727753)

drawable这个东西相信大家天天都在使用，每个人都再熟悉不过了，但再熟悉不过的技术，可能也有一些你所不知道的细节，本文就带我们一起探究了这些微小的细节。

[SearchView源码解析](https://github.com/nukc/SearchViewAnalysis)

SearchView是一个搜索框控件。搜索是一个使用频率非常高的功能，很多同学都是用EditText来自定义搜索功能，其实Android的v7包中的SearchView就是用来实现搜索框功能的，很多同学对这个组件并不了解。本文对android.support.v7.widget包下的SearchView进行了解析，有助于我们了解SearchView的特性。

## 开源项目

**iOS**

[SwiftOCR](https://github.com/garnele007/SwiftOCR)

SwiftOCR 是一个用 Swift 写的 OCR 框架，相比于 C++ 写的有三十年历史的 [Tesseract](https://github.com/tesseract-ocr/tesseract)，作者宣称在识别数字和字母的准确性和效率上，SwiftOCR 都具有压倒性的优势。如果你恰好有识别像是验证码或者礼品卡上的数字和字母这样的需求的话，不妨尝试下这个框架。同时如果你在学习图像识别或者是人工智能之类的课题的话，这个项目也会  是不错的学习资料。

[CoreStore](https://github.com/JohnEstropia/CoreStore)

很多时候我们往往会选择一些替代方案或者对 Core Data 的再次包装和简化。CoreStore 就是一个基于 Core Data 的 API 封装，它能让我们利用 Swift 的特性以一种更好的方式使用 Core Data。

[Palau](https://github.com/symentis/Palau)

Swift 提供的类型安全对现有的 Cocoa API 的改进是很有潜力的，而 `NSUserDefaults` 就是一个很好的改进案例。Palau 用类型安全的方式对 `NSUserDefaults` 进行了封装，同时也扩展了 `NSUserDefaults` 所能支持的类型，让我们可以用更好的方式使用 `NSUserDefaults`。

[LeeGo](https://github.com/wangshengjia/LeeGo)

LeeGo 是一个尝试使用声明式的，可配置的和易复用的 UI 组件进行用户界面开发的方式。相对于直接创建和书写 `UIView` 的子类，LeeGo 通过创建 `Brick` 来将用户界面分解成一个一个的小块，然后再将它们进行组合并展示为完整的用户界面。相比于传统的 `UIView`，LeeGo 的 UI 创建方式是声明式的，并且能够通过 JSON 进行远程的更新，是一种十分具有吸引力的 UI 构建方式。

**Android**

[Depth-LIB-Android-](https://github.com/danielzeller/Depth-LIB-Android-)

这是一个非常酷炫的Fragment切换动画效果。[这里](http://www.jianshu.com/p/a4dabb3554c1)是一篇介绍该动画实现过程的文章。

[StickyHeaderListView](https://github.com/sfsheng0322/StickyHeaderListView)

这是国内开发者的一个开源项目，可基于实际需求做出的灵活可定制的ListView，比如支持无限循环的广告位，高度可动态配置的Header2和Header3（使用GridView实现），分类、排序和筛选布局滑动到顶部后吸附、悬停等等。

[PLDroidPlayer](https://github.com/pili-engineering/PLDroidPlayer)

PLDroidPlayer 是一个适用于Android平台的音视频播放器SDK，可高度定制化和二次开发，为Android开发者提供了简单、快捷的接口，帮助开发者在Android平台上快速开发播放器应用。

## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**资深Android/iOS开发工程师 by 阿里云**

地点北京或杭州。负责阿里云MBaaS相关产品的移动端研发工作。要求两年以上客户端开发经验，薪资面议。有意者发送简历至：lingming.yb@alibaba-inc.com


## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[GMTC全球移动技术大会](http://gmtc.geekbang.org/?utm_source=zhoubao&utm_medium=xuachuan02&utm_campaign=0425)

6月24-25日北京举办。上周新增讲师腾讯社交平台部Android开发工程师王少鸣，向大家分享QQ空间的React Native实践。本周起开始8折促销期间，5人以上团购更多优惠，欢迎购票参加。

[Celebrate Ubuntu黑客松——北京站](https://developer.ubuntu.com/zh-cn/beijing-hackathon/?utm_source=BeijingHack201605&utm_medium=infoq&utm_campaign=Hackathons)

5月7-8日在北京举行。使用Ubuntu手机SDK开发应用，包括Native和类似H5的一种都可以。奖品有装有Ubuntu手机系统的魅族PRO5、BQ M10平板等。喜欢Hackathon和Ubuntu的同学不可错过。

----

上周移动开发前线公众号精彩文章：

* [群分享：蘑菇街支付金融Android单元测试实践](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112121&idx=1&sn=c5cc27a8cefd0dc8e1ed956e82a76cd9#rd)
* [React Native如何做跨平台设计](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112134&idx=1&sn=c26ceb682e361ae33bc1eb5348e5e7bb#rd)
* [使用Swift进行Android开发](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112140&idx=1&sn=8989b9a6ea5cf22fbea8d666e66a9767#rd)
* [群分享：从Android到Swift iOS开发：语言与框架对比](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112156&idx=1&sn=8dfaa630e8bc6ef66b4263bffd2d29dc#rd)

阅读更多移动开发好文，欢迎关注『移动开发前线』公众号。
