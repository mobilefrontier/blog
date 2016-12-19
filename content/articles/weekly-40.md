+++
date = "2016-12-19T23:07:47+08:00"
title = "移动开发每周阅读清单：第四十期"
description = "美国专利商标局的数据库中近日也出现了一项由 Apple 申请的双卡技术专利。专利展示了如何使用独立天线实现双卡待机并区分双卡之间的优先级，以及同时使两张 SIM 支持 LTE 网络的技术细节。但双卡技术是否会应用在明年的 iPhone 设备上仍然是个未知数。"
+++


## 新闻

[Apple 双卡专利曝光](http://www.phonearena.com/news/Apple-granted-patent-for-dual-SIM-technology_id89004)

美国专利商标局的数据库中近日也出现了一项由 Apple 申请的双卡技术专利。专利展示了如何使用独立天线实现双卡待机并区分双卡之间的优先级，以及同时使两张 SIM 支持 LTE 网络的技术细节。但双卡技术是否会应用在明年的 iPhone 设备上仍然是个未知数。

[Android Wear 2.0的部分第三方独立应用率先曝光](http://www.cnbeta.com/articles/568229.htm)

Google已经确认推迟Android Wear 2.0至明年发布。或许这项决定让部分人感到失望，不过好消息是新版智能手表系统将支持第三方独立应用。本周，根据Google官博客，Foursquare, Glide、Lifesum等软件将会登陆新版Android Wear。


## 教程

**iOS**

[DynamicCocoa：滴滴 iOS 动态化方案的诞生与起航](http://mp.weixin.qq.com/s/qRW_akbU3TSd0SxpF3iQmQ)

动态化一直是 App 开发梦寐以求的能力，而在 iOS 环境下，Apple 禁止了在 Main Bundle 外加载和执行的自己的动态库，所以像 Android 一样下发原生代码的方案被堵死。本文介绍了滴滴自研的 iOS 动态化方案 DynamicCocoa，包含基本的实现原理和功能。

[WKWebView 从入门到趟坑：](http://mp.weixin.qq.com/s/18xXQWboHcjybd_VtcTmUg)

开发 App 的过程中，常常会遇到在 App 内部加载网页，通常用 UIWebView 加载。而这个自 iOS 2.0 开始使用的 Web 容器一直是开发的心病：加载速度慢，占用内存多，优化困难。本文介绍了作者从 UIWebView 迁移到 WKWebView 遇到的坑，并给出了部分解决方案。

[微信读书 iOS 质量保证及性能监控](http://wereadteam.github.io/2016/12/12/Monitor/)

在实现需求的同时，能写出既优雅性能又高效的代码是每个开发者都在追求的目标，但是在实际开发中，随着每个版本需求的迭代，功能变得越来越复杂，加上开发者的意识不够或者一时疏忽，日渐复杂的工程很容易产生或多或少的问题。 app 随机丢失动画、用户反馈 app 卡死、用户投诉看不了书籍等等的问题，这些问题都严重影响使用，也会降低产品口碑。微信读书团队开发了一些监控工具来解决这些问题。

[2016 年 iOS 技术圈回顾](http://mrpeak.cn/blog/ios-2016/)

2016 年同 2015 年一样，一晃神就到了年底。年关将近，不知诸君心情如何，年初的规划实现了多少，来年的计划又是否已有了眉目。年过三十的作者感觉年关是越来越难过了，本文盘点了 2016 年 iOS 技术圈发生的一些大大小小的事。


[Stack View Constraint Conflicts When Hiding Views](http://useyourloaf.com/blog/stack-view-constraint-conflicts-when-hiding-views/)

如果你在使用 UIStackView ，免不了遇到各种约束冲突的提示，本文介绍了冲突的来源和 UISV-hiding 是什么，以及对应的解决方案。


**Android**

[Weex Android SDK源码分析](http://www.jianshu.com/p/3160a0297345)

12月15日，阿里巴巴宣布将移动开源项目Weex捐赠给Apache基金会开始孵化，Weex有望成为中国移动领域的首个Apache顶级项目，这意味着中国移动技术开始反哺世界。据悉，这也是继JStorm、RocketMQ之后，阿里向Apache捐赠的第三个项目。本文作者初学Weex，简单介绍了Weex Android SDK的源码。

[Android Fragment的使用，一些你不可不知的注意事项](http://yifeng.studio/2016/12/15/android-fragment-attentions/)

Fragment俗称碎片，自Android 3.0开始被引进并大量使用。然而就是这样耳熟能详的一个东西，在开发中我们还是会遇见各种各样的问题，层出不穷。作为Activity界面的一部分，Fragment的存在必须依附于Activity，并且与Activity一样，拥有自己的生命周期，同时处理用户的交互动作。本文为我们详细介绍了Fragment的常用方法及一些注意事项。

[Android 开发:由模块化到组件化(一)](http://blog.csdn.net/dd864140130/article/details/53645290)

模块化就是将一个程序按照其功能做拆分，分成相互独立的模块，以便于每个模块只包含与其功能相关的内容。模块我们相对熟悉，比如登录功能可以是一个模块，搜索功能可以是一个模块，汽车的发送机也可是一个模块。组件化就是基于可重用的目的，将一个大的软件系统按照分离关注点的形式，拆分成多个独立的组件，已较少耦合。本文简单介绍了组件化与模块化的区别及整体架构。

[Android NDK vs AOSP Build System](http://woshijpf.github.io/2016/12/17/Android-NDKvsAOSP-Build-System/)

作者最近一直在做有关Android系统源码底层的开发，就经常接触到 Android NDK 和 AOSP(Android Open Source Project) Build System 这两个东西，但是由于他们两者都可以将C/C++代码编译成可执行文件或者动态链接库，导致作者经常将这两者弄混淆了。为了弄明白两者的关系，作者写下了本文。文章详细介绍了Android NDK与AOSP Build System的概念、区别以及两者之间关系。


## 开源项目

**iOS**

[material-components-ios](https://github.com/material-components/material-components-ios)

将 Material Design 应用到 iOS 上组件库。

[Eureka](https://github.com/xmartlabs/Eureka)

易用易扩展的动态表单工具。

[FLEX](https://github.com/Flipboard/FLEX)

App Debug 工具。

[ios-oss](https://github.com/kickstarter/ios-oss)

Kickstarter 完整开源项目。


**Android**

[ZoomHeader](https://github.com/githubwing/ZoomHeader)

模仿饿了么详情页的效果，实现了跟随手指移动viewpager变详情页的效果。

[高仿蘑菇街欢迎页](http://www.jianshu.com/p/9dd4027c2107)

该项目模仿了蘑菇街欢迎页的效果，同时作者还给出了一遍介绍实现过程的文章。

[TextLayoutBuilder](https://github.com/facebookincubator/TextLayoutBuilder)

这是facebook出品的一个开源项目。使用该项目，我们可以非常方便的通过代码去创建一个layout。

## 工作

> 有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

本周暂无工作推荐，可查看之前的推荐。

## 活动

> 宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[QCon北京站2017](http://2017.qconbeijing.com/)

2017年4月16日北京举行。明年第一场最值得期待的综合性技术大会。QCon内容源于实践并面向社区，演讲嘉宾依据热点话题，面向5年以上工作经验的技术团队负责人、架构师、工程总监、高级开发人员分享技术创新和最佳实践。