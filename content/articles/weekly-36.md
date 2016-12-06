+++
title = "移动开发每周阅读清单：第三十六期"
date = "2016-11-21T21:33:45+08:00"
description = "Apple 已经确认有极少数的 iPhone 6s 设备可能会意外关机。这并不是一个安全问题，且仅会影响序列号在一定范围内的，生产日期为 2015 年 9 月到 10 月之间的设备。Apple 提供了更换电池的相应策略。"
tags = ""
+++



## 新闻

[iPhone 6s 意外关机问题计划](https://www.apple.com/cn/support/iphone6s-unexpectedshutdown/)

Apple 已经确认有极少数的 iPhone 6s 设备可能会意外关机。这并不是一个安全问题，且仅会影响序列号在一定范围内的，生产日期为 2015 年 9 月到 10 月之间的设备。Apple 提供了更换电池的相应策略。

[谷歌加速Android与Chrome融合!再见安卓?](http://mobile.pconline.com.cn/857/8577704.html)

前些时候，外媒传出了谷歌正在加速Android和Chrome OS相整合的消息，而这个新系统最终将抛弃“Android”这个十年相随的名字，更名为“Andromeda”（仙女座）。根据外媒给出的最新消息，目前已经有两家硬件厂商获得了Andromeda的开发工具包，搭载Andromeda的首批设备最早将于明年第三、四季度登场。


## 教程

**iOS**

[一种 App 内路由系统的设计](https://xcoder.tips/a-route-system-design/)

App 发展到一定程度时，页面越来越多，工程越来越大，合作开发的人也越来越多，这时就可能需要引入路由系统（当然，从项目一开始启动就接入路由是最好不过了）。本文探讨了怎样才是路由系统该有的设计。

[从 Swift 的面向协议编程说开去](https://bestswifter.com/pop/)

文章标题谈到了面向协议编程(下文简称 POP)，是因为前几天阅读了一篇讲 Swift 中 POP 的文章。本文会以此为出发点，聊聊相关的概念，比如接口、mixin、组合模式、多继承等，同时也会借助各种语言中的例子来阐述我的思想。

[把玩高阶函数](http://williamzang.com/blog/2016/11/08/ba-wan-gao-jie-han-shu/)

如果你开始接触函数式编程，你一定听说过高阶函数。高阶函数需要接受一个或多个函数作为输入或者输出一个函数。那它们在实际的开发过程中究竟起着什么样的作用呢？本文将从入参、返回值和综合使用三部分来看这个问题。

[FLOW.CI 初体验! 记一次暖心的 iOS 持续集成](http://fanhang.me/ios/ji-ci-ioschi-xu-ji-cheng-chu-ti-yan)

在 iOS 开发中集成 CI 是件极其麻烦的事情，因为一般我们没有使用 macOS 做服务器的环境，Fir 出品了一款 flow.ci ，本文介绍了作者在使用 flow.ci 的一整套服务的体验。

[Falsiness In Swift](http://khanlou.com/2016/06/falsiness-in-swift/)

在 Python 中，零和 None，以及空列表、字典和字符串，都有 falsy 值。 如果有 falsy 值，意味着可以它在 if 语句中使用，且可以使用 else。本文解释了为什么 Python 的规则比 Swift 的（以及几乎所有其他语言的）更实用呢，并给出了 Swift 更优雅的处理 falsy 和 truthy 的方案。


**Android**

[Android内存泄漏分析心得](http://mp.weixin.qq.com/s?__biz=MzI1MTA1MzM2Nw==&mid=2649796884&idx=1&sn=92b4e344060362128e4a86d6132c3736)

对于C++来说，内存泄漏就是new出来的对象没有delete，俗称野指针；对于Java来说，就是new出来的Object放在Heap上无法被GC回收；本文通过QQ和Qzone中内存泄漏实例讲解了Android中内存泄漏分析解法和编写代码应注意的事项。

[Android SDK 开发（第一部分）](https://zhuanlan.zhihu.com/p/22527586)

一般来说，SDK是Framework、API以及Library的集合。本文作者有多年的SDK开发经验，文章非常详细的介绍了如何开发一款高质量的SDK，推荐广大Android开发者阅读。

[Android ImageView 正确使用姿势](http://mp.weixin.qq.com/s?__biz=MzA3NTYzODYzMg==&mid=2653578233&idx=1&sn=aea773c1e815fdef910fba28d765940b)

ImageView是Android开发者最常用的控件之一，相信大家对ImageView的常用属性也非常熟悉，比如如何设置颜色、图片等。本文主要介绍了ImageView的相关重要方法，从源码角度剖析了一些容易令人混淆或百思不得其解的问题。

[安卓自定义View进阶-特殊控件的事件处理方案](http://www.gcssloop.com/customview/touch-matrix-region)

本文会带大家了解Android特殊形状控件的事件处理方式，主要是利用了Region和Matrix的一些方法，超级实用的事件处理方案，相信看完本篇之后，任何奇葩控件的事件处理都会变得十分简单。

[Clipboard还能玩出花](https://zhuanlan.zhihu.com/p/23700634)

Clipboard是Android提供的一个系统服务，它提供了一个全局的剪贴板，让文字、图片、数据，在多App间共享成为可能，今天，我们来了解下它的真面目，以及被玩坏的新姿势。例如手机迅雷，如果你复制了一个链接，那么打开迅雷后，会自动检测并提示下载。阅读文章，了解更多关于Clipboard的玩法。


## 开源项目

**iOS**

[Dash-iOS](https://github.com/Kapeli/Dash-iOS)

著名 Dash 应用开源了其 iOS 版本的 App ，代码可能写的如何大跌眼镜。但这是一款好的产品，也确实的表明了，用户不关心你用什么语言写、代码写的多漂亮。

[ALSLayouts](https://github.com/mariotaku/ALSLayouts)

将 Android 三大经典布局移植到 iOS 的框架。

[katana-swift](https://github.com/BendingSpoons/katana-swift)

一款参考 Redux 实现的 iOS 开发框架。



**Android**

[devfest2016](https://github.com/gdgbeijing/devfest2016)

这个是项目存放的是 『北京 GDG Devfest 2016』 资料，目前 Android 的讲义已经全部都上传了，Web 马上也全了。

[GSYVideoPlayer](https://github.com/CarGuo/GSYVideoPlayer)

这是一款视频播放器，支持基本的拖动，声音、亮度调节，支持边播边缓存，支持视频本身自带rotation的旋转，重力旋转与手动旋转的同步支持，支持列表播放 ，直接添加控件为封面，列表全屏动画，列表小窗口支持拖动，5.0的过场效果等等。

[ENViews](https://github.com/codeestX/ENViews)

ENViews是一个华丽的动效控件库，所有控件原型取自[Nick Buturishvili](https://dribbble.com/nick_buturishvili)的设计作品。

[AlgorithmVisualizer-Android](https://github.com/naman14/AlgorithmVisualizer-Android)

一款Android平台的算法可视化工具，目前支持二分查找、二叉搜索树(搜索和插入)、冒泡排序、插入排序、链表和堆栈、BFS和DFS遍历等。




## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

----

[ArchSummit全球架构师峰会](http://bj2016.archsummit.com/)

地点北京。ArchSummit秉承“实践第一、案例为主”的原则，展示新技术在行业应用中的最新实践，技术在企业转型中的加速作用，帮助企业技术管理者、CTO、架构师做好技术选型、技术团队组建与管理，并确立技术对于产品和业务的关键作用。

[百度技术沙龙68期：移动端输入法性能优化实战](http://form.mikecrm.com/RIrDrw)

本期百度技术沙龙，我们将邀请到百度输入法团队的工程师们，从三个方面解析百度输入法当前的进展，包括对iOS输入法启动速度和内存的优化措施；人工智能在手写引擎中的应用，输入体验的提升；以及智能语音输入的技术核心，实现方式，优化细节等等。
