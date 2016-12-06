+++
title = "移动开发每周阅读清单：第二十九期"
date = "2016-09-20T21:33:45+08:00"
description = "Apple 发布了 iOS 10 正式版更新，不少在第一时间升级的用户在通过 OTA 方式升级时都遇到了假死的情况，设备会进入恢复模式，需要连接 iTunes 进行恢复以及 Apple Music 音乐库无法同步的问题。"
tags = ""
+++

## 新闻

[iOS 10 正式版发布 用户升级遇多种问题](http://thenextweb.com/apple/2016/09/13/what-a-day-for-apple/)

Apple 发布了 iOS 10 正式版更新，不少在第一时间升级的用户在通过 OTA 方式升级时都遇到了假死的情况，设备会进入恢复模式，需要连接 iTunes 进行恢复以及 Apple Music 音乐库无法同步的问题。

[可怕的事实：美国49%用户每月下载App数量为零](http://www.ithome.com/html/iphone/258057.htm)

根据comScore最新的移动应用报告，美国一半智能手机用户每月下载的应用数量为零。在给定的一个月时间里，有49%美国智能手机用户没有下载应用。在51%下载过应用的智能手机用户中，“平均的应用下载数量为3.5个”。“然而，一小部分用户下载了大部分应用。13%的智能手机用户下载的应用数量超过总数的一半。”

## 教程

**iOS**

[Chris Lattner 对 Swift 3 的总结与对 Swift 4 的展望]()

Swift 语言创始人 Chris 发表了对 Swift 3 开发的回顾以及公布了对 Swift 4 阶段性的开发计划。同时本文还有一篇[中文翻译](http://swift.gg/2016/09/14/chris-lattner-on-wrapping-up-swift-3-starting-swift-4/)。

[Working with JSON in Swift](https://developer.apple.com/swift/blog/?id=37)

Apple 官方关于 JSON 转 Model 的 Swift 3 例子，它比 JSONExport 等通常的做法要优雅一点的地方在于：它不是在 struct 里面定义optional var, 而是在 model extension 里增加一个 failable initializer。

[BadURLScheme in iOS](http://paper.seebug.org/42/)

本文作者分享了 iOS 中的 XSS 漏洞，主要是在 iOS 对于 URL Scheme 及其在 UIWebView 等控件的自动诊断识别等处理机制下导致跨应用 XSS 漏洞。

**Android**

[Android 热补丁技术——资源的热修复](http://blog.csdn.net/sbsujjbcy/article/details/52541803)

今年真是热补丁框架的洪荒之力爆发的一年，短短几个月内，已经出现了好几个热修复的框架了，基本上都是大同小异。但只有自己真正的去经历过，你才会发现其中的大写的坑。

[Android ButterKnife 的实现思路](http://blog.csdn.net/bboyfeiyu/article/details/52572963)

在Android开发中，我们为了方便初始化Activity中的各种View，我们可能会使用到Jake Wharton的ButterKnife库，这个库是针对View、资源id等进行注解的开源库，它能够去除掉一些丑陋不堪的样板式代码，使得我们的代码更加简洁、易于维护，同时基于APT也使得它的效率得到保证。那么ButterKnife的原理是什么呢？@InjectView又是什么？ButterKnife的inject函数又有什么作用？本文给出了答案。

[Android LowMemoryKiller原理分析](http://gityuan.com/2016/09/17/android-lowmemorykiller/)

Android的设计理念之一，便是应用程序退出,但进程还会继续存在系统以便再次启动时提高响应时间. 这样的设计会带来一个问题, 每个进程都有自己独立的内存地址空间，随着应用打开数量的增多,系统已使用的内存越来越大，就很有可能导致系统内存不足, 那么需要一个能管理所有进程，根据一定策略来释放进程的策略，这便有了lmk，全称为LowMemoryKiller(低内存杀手)，lmkd来决定什么时间杀掉什么进程.

## 开源项目

**iOS**

[URLNavigator](https://github.com/devxoul/URLNavigator)

优雅的 URL Router Swift 框架，支持 UIViewController 的转场，以及可定制的匹配结果处理，如弹窗、从 Stroyboard 初始化 ViewController 转场等。

[Down](https://github.com/iwasrobbed/Down)

基于 cmark 高性能 Markdown 渲染 Swift 框架。

[MetaModel](https://github.com/MModel/MetaModel)

底层基于 SQL 的持久化方案。不需要直接使用 SQL 语言处理数据，有更简洁的 API ，基于 Ruby 栈创建 Model 。

**Android**

[StylishMusicPlayer](https://github.com/ryanhoo/StylishMusicPlayer)

这是一款完整的音乐播放器项目，支持音乐播放、文件浏览等功能，可以在版本号为16+的设备上运行。

[Qart](https://github.com/scola/Qart)

Qart是一个二维码生成项目，支持图片合成，使用该项目可以生成非常漂亮的二维码。

[AndroidAudioConverter](https://github.com/adrielcafe/AndroidAudioConverter)

这是一个格式转换项目，支持的格式有AAC, MP3, M4A, WMA, WAV、FLAC，集成简单。



## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

本期暂无工作推推荐。


## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

----
