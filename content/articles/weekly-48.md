+++
date = "2017-03-07T21:07:47+08:00"
title = "移动开发每周阅读清单：第四十八期"
description = "3月8日，很多iOS开发者发了警告邮件，声称其App违规使用动态方法，责令限时整改。一时间整个iOS圈炸了。"
+++


## 新闻

[苹果“热修复门”事件回顾和分析](https://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651113173&idx=1&sn=8c52d83c505e2be7afe175c01a36de4e)

3月8日，很多iOS开发者发了警告邮件，声称其App违规使用动态方法，责令限时整改。一时间整个iOS圈炸了。

[谷歌公布最新安卓版本分布：7.0/7.1已达2.8%](http://www.ithome.com/html/android/296708.htm)

谷歌目前公布了2017年3月份的安卓系统各版本最新分布情况统计，数据显示目前Android Nougat（7.0+7.1）的份额已经达到2.8%，目前占比最多的仍然是Android Lollipop（32.5%），眼看最新的安卓8.0系统再过几个月就要问世了，目前安卓阵营的碎片化仍然不容乐观。

## 教程

**iOS**

[iOS App 签名的原理](http://blog.cnbang.net/tech/3386/)

iOS 签名机制相对复杂，各种证书，Provisioning Profile，entitlements，CertificateSigningRequest，p12，AppID，概念一堆，也很容易出错，本文尝试从原理出发，一步步推出为什么会有这么多概念，希望能有助于理解 iOS App 签名的原理和流程。

[闲谈 iOS 的动态化](https://zhuanlan.zhihu.com/p/25647026)

本文不聊具体的技术内容，而最近一些应用收到 Apple 警告的问题。提示该应用使用了一些动态技术，让应用在审核之后出现一些不一样的功能，从而越过审核去实现更新，警告开发者对代码进行一些检查，去掉这样的实现。实际上这是一个历史悠久，错综复杂，没有一个统一标准的事情。聊这个事情要从一个很古老的 Wax 项目开始讨论 Native 动态化的事情。

[关于 @synchronized 比你想知道的还多](http://www.jianshu.com/p/7026de47dc75)

如果你曾经使用 Objective-C 做过并发编程，那你肯定见过 @synchronized 。@synchronized 发挥了和锁一样的作用：它避免了多个线程同时执行同一段代码。和使用 NSLock 进行创建锁、加锁、解锁相比，在某些情况下 @synchronized 会更方便、更易读。如果你从来没有使用过 @synchronized ，具体如何使用可以参考下面的实例。本文的将围绕我对 @synchronized 的原理的探究进行讲述。

[RxExample GitHubSearchRepositories](https://blog.dianqk.org/2017/03/09/rxexamples-github-search-repositories/)

在 iOS 中，我们该如何处理网络请求状态、如何管理分页逻辑以及如何处理网络错误，RxSwift 给出了一个官方的例子 GitHubSearchRepositories ，本文对这个例子代码进行了详细的解释。

**Android**

[Android Studio2.3正式版发布，官方全解析](http://mp.weixin.qq.com/s/EGaAyDineE4ZlgMCGec1Vw)

Android Studio 2.3中最令人激动的是质量上的改进，但此版本也加入了一些新功能：设计应用时，增加利用面向应用图像的更新版WebP支持；内容库支持以及布局编辑器中的小部件选项板；在开发过程中，Android Studio新增了一个应用链接助手，它可以帮助您构建一个应用URI合并视图，在构建和部署应用时，使用更新版运行按钮可获得更加直观而又可靠的Instant Run体验等。

[Android自定义Lint实践2——改进原生Detector](http://tech.meituan.com/android_custom_lint2.html)

本文来自美团的技术博客。Android Lint是Google提供给Android开发者的静态代码检查工具。使用Lint对Android工程代码进行扫描和检查，可以发现代码潜在的问题，提醒程序员及早修正。为保证代码质量，美团在开发流程中加入了代码检查，如果代码检测到问题，则无法合并到正式分支中，这些检查中就包括Lint。本文介绍了美团App如何使用自定义Lint进行代码检查。

[React Native for Android异常处理概览](http://mp.weixin.qq.com/s/aWuenpGOKug4fovT5uKXTQ)

研究RN框架异常的动机在于，需要建立起一套针对性的容错机制，毕竟它还是一个不够成熟的框架。期望能够做到的效果就是，对于每一个RN页面的启动，能够在进入页面至退出页面期间侦测所有发生的RN相关的崩溃，然后根据崩溃来考虑该页面是否该有降级策略、判断框架是否真的能够支持稳定迭代。本文从启动期和运行期两方面介绍了RN的异常方案。

[Android Drawable完全解析（一）：Drawable源码分析系列](http://www.jianshu.com/p/c56b762210f2)

Android开发中，Drawable几乎无处不在，Drawable涉及的面很广，尤其是竟然有那么多的继承类。我们常用的有ColorDrawable、StateListDrawable、BitmapDrawable等很有限的几个子类，大多数开发者对于Drawable的应用还是太零散了。因此作者写了关于Drawable的系列文章，从源码的角度详细分析了Drawable的实现。

[Android技巧-Debug判断不再用BuildConfig](http://mp.weixin.qq.com/s?__biz=MzAxNjI3MDkzOQ==&mid=2654472687&idx=1&sn=3a8c101fab3b032d043c6ea0922c76f2)

Android开发中一般会通过BuildConfig.DEBUG判断是否是Debug模式，从而做一些在Debug模式才开启的特殊操作，比如打印日志。这样好处是不用在发布前去主动修改，因为这个值在Debug模式下为true，Release模式下为false。本文介绍如何不设置BuildConfig的Debug技巧。


## 开源项目

**iOS**

[GodEye](https://github.com/zixun/GodEye)

全自动，零代码入侵，一行代码接入来监控应用的日志，卡顿，崩溃，网络，内存泄漏，CPU以及内存使用率，帧率等信息工具。

[Nori](https://github.com/yukiasai/Nori)

将样式代码代码应用到 Storyboard 组件。

[SwipeCellKit](https://github.com/jerkoch/SwipeCellKit)

提供 Cell 丰富左右滑动功能，支持自定义效果。

[panelkit](https://github.com/louisdh/panelkit)

在 iOS 上提供面板功能，即支持多个窗口操作。



**Android**

[atlas](https://github.com/alibaba/atlas)

Atlas是伴随着手机淘宝的不断发展而衍生出来的一个运行于Android系统上的一个容器化框架，也叫动态组件化(Dynamic Bundle)框架。它主要提供了解耦化、组件化、动态性的支持。覆盖了工程师的工程编码期、Apk运行期以及后续运维期的各种问题。

[Robust](https://github.com/Meituan-Dianping/Robust)

美团点评根据Instant Run研发的新一代热更新系统Robust，对Android版本无差别兼容。无需发版就可以做到随时修改线上bug，快速对重大线上问题作出反应，补丁修补成功率高达99.9%。

[Depth](https://github.com/florent37/Depth)

非常炫的页面转换3D效果，可以用于浏览器多页面切换。

## 工作

> 有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

3月初我们发布了[移动开发前线招聘季活动](https://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651113136&idx=1&sn=8227a7c540cf1eadcbefd70036f4c8ce)，目前已有十多个职位发布，欢迎同学们到这里找工作，还有招聘需求的可以回复该贴，我会更新上去。

## 活动


> 宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[GMTC 2017全球移动技术大会](http://gmtc.geekbang.org/?utm_source=infoq&utm_campaign=bornmobile&utm_medium=wechat)

6月9日北京举行。关注移动、前端、跨平台、AI应用等多个技术领域、促进全球技术交流，推动国内技术升级。GMTC为期两天，面向移动开发、前端、AI技术人员，聚焦前沿技术及实践经验，打造技术人员的学习和交流平台。6折倒计时啦！

[QCon北京站2017](http://2017.qconbeijing.com/)

2017年4月16日北京举行。明年第一场最值得期待的综合性技术大会。QCon内容源于实践并面向社区，演讲嘉宾依据热点话题，面向5年以上工作经验的技术团队负责人、架构师、工程总监、高级开发人员分享技术创新和最佳实践。