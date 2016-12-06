+++
title = "移动开发每周阅读清单：第十九期"
date = "2016-07-12T21:33:45+08:00"
description = "『移动开发每周阅读清单』第十九期与大家见面了，这两周发生了很多大事，让人目不暇接，移动这边则是Pokemon Go爆款，成为现象级应用，大家有玩过吗？"
tags = ""
+++

『移动开发每周阅读清单』第十九期与大家见面了，这两周发生了很多大事，让人目不暇接，移动这边则是Pokemon Go爆款，成为现象级应用，大家有玩过吗？

## 新闻

[苹果公布iOS 10系统中23款可删除预装应用](http://tech.sina.com.cn/mobile/n/n/2016-07-11/doc-ifxtwiht3494966.shtml)

本周五，苹果公司正式放出了新一代操作系统iOS 10和macOS Sierra首个公开测试版，而期待已久的“允许删除iPhone预装应用”功能正式到来。随后，苹果公司正式揭晓了这23款可卸载的iPhone预装应用。不过，根据官方描述，这种删除更像是隐藏，应用代码实际上并不好移除。

[Android Marshmallow/Nougat 进行时：设备升级列表已公布](http://digi.163.com/16/0708/10/BREP49MN00162OUT.html)

近日Google携众厂商发布了Android Marshmallow和Android Nougat的设备升级列表。Nexus系列一直是重点关怀对象，从最新的Nexus 6P/5X、Nexus 6 / Player、Nexus 9 LTE / WiFi，到Nexus 5、以及Nexus 7 2013（双版本），均支持升级到“棉花糖”（Marshmallow）。此外，前半截还很有望吃到“牛轧糖”（Nougat）。

## 教程

**iOS**

[iOS视频直播初窥:高仿<喵播APP>](http://www.jianshu.com/p/b8db6c142aad)

本文介绍了作者在研究iOS视频直播技术之时，高仿了喵播App，并分享了开发过程、相关技术和关键代码。并且作者还将高仿App代码开源了，想研究直播技术的可以下载把玩。

[如何动态调用 C 函数](http://blog.cnbang.net/tech/3219/)

本文作者为JSPatch作者bang，JSPatch支持动态调用C函数，本文是他对其中原理的分享解读。

[让UIWebview拥有超强的图片处理能力](http://www.jianshu.com/p/a46297f2ce70)

其实不仅仅局限于为了让其支持webp，如果能让webview的图片请求都走向自己实现的图片库，那么可以实现很多很多黑科技如加水印等，本文介绍了其中的技术点以及具体实现。

**Android**

[Android内存申请分析](https://mp.weixin.qq.com/s?__biz=MzAwNDY1ODY2OQ==&mid=2649286327&idx=1&sn=b69513e3dfd1de848daefe03ab6719c2&scene=0)

在做优化的过程，除了关注内存的申请量以及GC的情况之外，我们经常需要想方法找出是那些对象占用了大量内存，以及他们是如何导致GC的，这意味着我们需要获取对象申请的信息（大小，类型，堆栈等），本文为我们介绍了几种获取对象申请信息的方法。

[Unity Android Plugin开发指南](https://mp.weixin.qq.com/s?__biz=MzI1NjEwMTM4OA==&mid=2651231917&idx=1&sn=ce2e0f7251e26f7b5a9b2fddadf96bcc&scene=0)

本文为我们介绍了如何在Unity工程中使用Android或者Java的库，包括：如何在Unity项目中使用Android Plugin、Unity-Android相互调用、Unity接口设计的最佳实践、如何构建Unity-Android混合项目、如何调试Unity和Android代码。本文有助于我们上手Unity。

[安卓单元测试(八)：Junit Rule的使用](http://www.jianshu.com/p/2cd745e54a78#rd)

一个JUnit Rule就是一个实现了TestRule的类，这些类的作用类似于@Before、@After，是用来在每个测试方法的执行前后执行一些代码的一个方法。此外，JUnit Rule还能做一些@Before这些Annotation做不到的事情，那就是他们可以动态的获取将要运行的测试类、测试方法的信息。阅读文章，了解Junit Rule的更多细节。

## 开源项目

**iOS**

[LayoutKit](https://github.com/linkedin/LayoutKit)

LinkedIn开源的iOS快速视图布局库。看上去LinkedIn对这个库还是很重视的，不但写了一篇[博客](https://engineering.linkedin.com/blog/2016/06/open-sourcing-layoutkit--a-fast-view-layout-library-for-ios-appl)介绍它，还为它买域名做了[官网](http://layoutkit.org/)。

[CoreStore](https://github.com/JohnEstropia/CoreStore)

对CordData做的封装，让其使用更加安全优雅，使用Swift编写。

[LeetCode_Swift](https://github.com/soapyigu/LeetCode_Swift)

LeetCode题库在程序员中应该是鼎鼎大名了，上面的算法题几乎是面试必备，有人对其中的解答给出了Swift版本，既可以学算法，又可以学习Swift语法中的一些技巧。

[GYDataCenter](https://github.com/Zepo/GYDataCenter)

GYDataCenter 是微信读书团队开源的一个 SQLite 数据库框架，提供了一套简单易用的面向对象的数据操作接口，同时保留了 SQL 查询的灵活性。GYDataCenter 简单易上手，相对于 CoreData，GYDataCenter 的学习成本更低。同时，根据自己的需求，开发者可以更方便地划分数据库，设计数据库表，数据库索引等。

**Android**

[Music-Player](https://github.com/andremion/Music-Player)

这是一款简易的音乐播放器，列表页到播放页的切换动画很赞。这里是一篇介绍项目实现过程的文章。

[FocusResize](https://github.com/borjabravo10/FocusResize)

该项目实现了RecyclerView在滑动时动态伸缩的效果。

[VirtualApp](https://github.com/asLody/VirtualApp)

VirtualApp是一个App虚拟引擎的开源实现，类似LBE平行空间。 VirtualApp在你的App进程内创建一个虚拟空间，你可以在虚拟空间内任意的安装、启动和卸载APK， 这一切都与外部隔离，就如同一个沙盒。VirtualApp亦是一个插件化框架，运行在VirtualApp的插件不需要任何的约束。


## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**iOS/Android工程师 by 快看世界科技有限公司**

坐标北京。负责快看漫画App产品研发，能独立完成模块设计及开发，以及一些优化工作。要求2年实际项目经验。薪资15k-30k。简历发至hr@kuaikanmanhua.com 可标注“从移动开发前线看到”。

**iOS工程师/高级工程师/技术专家 by 新美大平台部门iOS组**

坐标北京。负责维护新美大旗下的主客户端之一美团，以及全公司的iOS相关基础设施。需要合格的iOS开发能力，如果是高级或以上，还需要有技术规划选型，指导他人的能力。薪资面议。简历投至 luozexiang@meituan.com

## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[中国移动互联网测试大会](http://www.bagevent.com/event/56573)

7月16日于北京举行。专注移动互联网测试技术的分享会，关注移动互联网质量的有志之士的集会。本次大会主题涉及移动端的自动化、持续集成、性能、安全等一系列测试领域，以及当下移动端最新最热最实用的测试技术交流分享。

[ArchSummit架构师大会深圳站](http://sz2016.archsummit.com/)

7月15-16日于深圳举行。面向高端技术管理者、架构师的技术大会。秉承“实践第一、案例为主”的原则，展示新技术在行业应用中的最新实践，技术在企业转型中的加速作用，帮助企业技术管理者、CTO、架构师做好技术选型、技术团队组建与管理，并确立技术对于产品和业务的关键作用。

----
上两周移动开发前线公众号精彩文章：

* [安全模式：天猫App启动保护实践](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112417&idx=1&sn=4a6bf640ab72a4c72af1e602a634a2ca#rd)
* [为什么Android开发者应该使用FlatBuffers替代JSON?](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112424&idx=1&sn=51401124fbab3917520cc889dae824fe#rd)
* [不要再给MVP中的Presenter写接口了](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112433&idx=1&sn=f50bd52f056570e3229307fba9d9839a#rd)
* [Storyboard 优雅使用规范](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112441&idx=1&sn=f39a1988a37a78b9b865856c63907f94#rd)
* [iOS交互式动画详解（上）：iOS 10以下的实现](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112450&idx=1&sn=3807acbfac41675cdfd1f9e7c1f50231#rd)
* [iOS交互式动画详解（下）：iOS 10 的新变化](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651112458&idx=1&sn=3c61daa725f74c56a58312f55407d267#rd)

阅读更多移动开发好文，欢迎关注『移动开发前线』公众号。
