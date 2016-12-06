+++
title = "移动开发每周阅读清单：第二期"
date = "2016-03-14T21:34:45+08:00"
description = "上周速报更名为『移动开发每周阅读清单』，今天是第二期，内容来自InfoQ iOS和Android周报、移动前线群成员的分享。目前初创期，欢迎大家多提建议~"
tags = ""
+++

大家好，上周速报更名为『移动开发每周阅读清单』，今天是第二期，内容来自InfoQ iOS和Android周报、移动前线群成员的分享。目前初创期，欢迎大家多提建议~

## 新闻

[Google I/0 2016将于3.8日开放注册](https://events.google.com/io2016/)

一年一度的谷歌I/O开发者大会官方网站已正式上线。除去熟悉的倒计时器外，该网站提供的信息还显示，本届谷歌I/O开发者大会将于3月8日开放注册，并将于5月18日至5月20日举办。与往年的收费标准相同，本届谷歌I/O开发者大会的门票价格为900美元。开发者有两天时间提交参会申请。在3月10日之后，谷歌将随机挑选参会开发者，邀请函则 将通过电子邮件发送给申请人。

[Apple开设支持服务推特账号](http://www.macrumors.com/2016/03/03/apple-launches-twitter-support-account/)

本周 Apple 在推特开通了官方的支持账号，用来解答用户使用上的问题。在账号开通 24 小时后，这个账号就拥有了超过 12 万粉丝，并且发出了超过 2750 条信息。使用社交网络的方式来进行客户服务并不鲜见，但是对于 Apple 这样体量的企业也转向更多地用这种迅速的方式提供客服，是企业客服方式正在转变的信号。

## 教程

[Swift 烧脑体操](http://www.infoq.com/cn/articles/swift-brain-gym-optional)

一系列 Swift 比较有意思的语法和概念的解析，包括了 Optional，函数参数，高阶函数，map 和 flatMap 的解读。按照文章的内容进行思考，对于理解 Swift 的这些基本概念很有帮助。系列一共五篇，本周会全部发完。

[iOS 高效添加圆角效果实战讲解](http://www.jianshu.com/p/f970872fdc22)

圆角是一种很常见的视图效果，相比于直角，它更加柔和优美，易于接受。但很多开发者并不清楚如何设置圆角的正确方式和原理。设置圆角会带来一定的性能损耗，如何提高性能是另一个需要重点讨论的话题。这篇文章就这个话题进行了一些分析和讨论。

[使用Swift的stack trace调试异步任务](http://www.cocoawithlove.com/blog/2016/02/28/stack-traces-in-swift.html)

Debug 向来是开发中很重要的一个环节，但是对于异步代码来说，调试工作会困难得多。这篇文章介绍了一种针对多个线程的任务进行追踪的方式，通过这种方法，我们可以获取到异步任务的调用栈，这对于调试异步代码会非常有用。

[Swift Asserts](https://www.mikeash.com/pyblog/friday-qa-2016-03-04-swift-asserts.html)

Assert 经常被用在检查代码运行条件时，善用 assert 可以在开发阶段就捕获由于开发者失误所带来的错误。这篇文章介绍了 Swift 中 assert 相关 API 使用上的一些实践和方式。

[移动网络下的性能优化之省电篇](https://blog.wilddog.com/?p=948)

想开发出用户体验更好的应用，就需要对移动网络有更深入的了解。本系列文章将分为上下两篇，分别介绍如何开发出更省电和网络延迟更低的移动应用程序。本篇文章主要介绍了移动网络的一些基本工作原理以及降低手机耗电的优化方案。

[微信红包照片客户端开发那些事](https://mp.weixin.qq.com/s?__biz=MzAwNDY1ODY2OQ==&mid=401327503&idx=1&sn=1d9fac7b648c3494d312da962f53bfbd)

2016 除夕夜，微信除了摇一摇抢红包，同时还带来了另外一个新玩法——红包照片，而据说很多人也都卖命晒出了珍藏多年的照片！回头来看红包照片这一套系统，对于客户端而言，区别于普通的朋友圈图片设计差异是否大？它是否复杂？客户端都关注些什么？本文从一个Android客户端开发者的角度出发分析了以上这些问题。

[更优雅的 Android 发布自动版本号方案](http://www.race604.com/android-auto-version/)

每一次发布新版本，我们都需要针对不同的渠道打多个Apk包，如果手动进行该工作，效率将会很低，并且容易出错。如果您的项目是用Git管理的，并且恰巧又是使用Gradle编译，那么本文将教会你一种更加优雅的自动版本管理方法。

[一款Android VoIP网络电话App架构分析](http://ticktick.blog.51cto.com/823160/1746136)

VoIP 简而言之就是将模拟信号数字化，以数据封包的形式在IP网络上做实时传递。飞鸽电话是一款Android平台的VoIP网络电话应用，支持给任意局域网内使用该App的其他用户拨打网络电话。该应用涉及到大量P2P语音传输技术。本文出自飞鸽电话作者之手，是对整个开发过程的一个总结，从宏观上分析了整个应用的架构和所涉及到的技术，对于我们学习VoIP很有帮助。

[Android推送技术研究](http://www.jianshu.com/p/584707554ed7)

推送已经成为了App的必备功能。由于自建推送服务性价比低，并且第三方的服务也比较稳定，所以目前大部分的App都会采用接入第三方的推送服务。但了解推送的实现方式还是很有必要的，本文介绍了推送的不同实现方式以及一些关于推送的基本知识点。

[面过阿里、点我吧、美柚、挖财、有赞 会有怎样的总结？](https://www.zhihu.com/question/40909636/answer/88775539)

本文作者面试了多家知名公司，总结了一些面试题与大家分享。题目涉及面比较广，包括Android技术发展的探讨、性能、 Activity（service）启动流程、动态化的几种方案、热修复、网络优化、数据库性能、线程等。本文对于我们巩固知识点有一定的帮助。

## 项目

[Advance](https://github.com/storehouse/Advance)


一个 Swift 动画框架，可以让我们用很简单的 API 来制作高性能和更真实的交互式动画。如果你对交互式动画并不熟悉的话，可以阅读一下 objc 中国的[这篇文章](ttp://objccn.io/issue-12-6/)。交互式动画中有很多隐藏的细节，并需要不少动画制作的经验。Advance 将这些繁琐的细节进行了封装，让开发者可以在更高抽象层上制作出完美的交互式动画。

[Markoff](https://github.com/thoughtbot/Markoff)


由 thoughtbot 带来的一个完整的 Swift 的 markdown 文件预览 OS X 应用。这个应用使用了 SwiftMark 来解析，使用 ReactiveCocoa 来响应式地进行代码组织。可以作为学习 app 开发的很好的示例应用。

[TranslateApp](http://androidone.io/info_10111.html)

该项目是一个划词翻译的开源App，App实现了复制单词即可显示的功能。

[android-support-23.2-sample](https://github.com/liaohuqiu/android-support-23.2-sample)


该项目是针对android-support-23.3新特性编写的一个Demo项目。项目中有包括Vector Drawable、Animated Vector Drawable、AppCompat DayNight theme、Bottom Sheets、RecyclerView等。

[NineGridImageView](http://androidone.io/info_10112.html)

NineGridImageView是一个能够显示九宫格图片的组件，利用该项目我们可以快速实现类似微信朋友圈显示多图片的功能。
