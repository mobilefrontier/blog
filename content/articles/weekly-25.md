+++
title = "移动开发每周阅读清单：第二十五期"
date = "2016-08-24T21:33:45+08:00"
description = "Apple CEO Tim Cook 和国务院副总理张高丽会面时表示，Apple 将在中国建立亚洲首个独立研发中心，计划于今年年底前建成。Apple 在中国建立独立研发中心将可以加强苹果在中国市场的影响力，并和政府建立更为良好的合作关系。"
tags = ""
+++


## 新闻

[Tim Cook 表示将在中国建立亚洲首家独立研发中心](https://9to5mac.com/2016/08/16/apple-china-rd-center/)

Apple CEO Tim Cook 和国务院副总理张高丽会面时表示，Apple 将在中国建立亚洲首个独立研发中心，计划于今年年底前建成。Apple 在中国建立独立研发中心将可以加强苹果在中国市场的影响力，并和政府建立更为良好的合作关系。

[Android 7.0牛轧糖发布时间泄露：Nexus 6P/5X将首尝“甜头”](http://www.ithome.com/html/android/250693.htm)

谷歌将在本月放出Android 7.0牛轧糖（安卓N）正式版的传闻已经由来已久，现在更具体的日期也被曝光。来自加拿大电信运营商Telus的最新消息显示，Nexus 6P和5X将在8月22日，也就是下周一迎来安卓7.0固件更新。

## 教程

**iOS**

[ReactiveCocoa 中潜在的内存泄漏及解决方案](http://tech.meituan.com/potential-memory-leak-in-reactivecocoa.html)

ReactiveCocoa 是 GitHub 开源的一个函数响应式编程框架，目前在美团 App 中大量使用。用过它的人都知道很好用，也确实为我们的生活带来了很多便利，特别是跟 MVVM 模式结合使用，更是如鱼得水。不过刚开始使用的时候，可能容易疏忽掉一些隐藏的细节，从而导致内存泄漏等问题。本文就带大家深入了解下 ReactiveCocoa 中隐藏的一些细节，帮助大家以更加正确的姿势使用 ReactiveCocoa。

[如何使用 Runtime 给现有的类添加 weak 属性](http://www.jianshu.com/p/ed65d71554d8)

本文给出了一份如何使用 Runtime 实现 weak 属性的解答，思路与 @iOS程序犭袁的给出的[参考答案](https://github.com/ChenYilong/iOSInterviewQuestions/blob/master/01%E3%80%8A%E6%8B%9B%E8%81%98%E4%B8%80%E4%B8%AA%E9%9D%A0%E8%B0%B1%E7%9A%84iOS%E3%80%8B%E9%9D%A2%E8%AF%95%E9%A2%98%E5%8F%82%E8%80%83%E7%AD%94%E6%A1%88/%E3%80%8A%E6%8B%9B%E8%81%98%E4%B8%80%E4%B8%AA%E9%9D%A0%E8%B0%B1%E7%9A%84iOS%E3%80%8B%E9%9D%A2%E8%AF%95%E9%A2%98%E5%8F%82%E8%80%83%E7%AD%94%E6%A1%88%EF%BC%88%E4%B8%8A%EF%BC%89.md)略有不同。

[如何进行 HTTP Mock（iOS）](http://draveness.me/http-mock/)

本文是对 [OHHTTPStubs](https://github.com/AliSoftware/OHHTTPStubs) 源代码的分析，其实现原理建立在 NSURLProtocol 的基础上，分析了 OHHTTPStubs 是拦截 HTTP 请求及如何伪造 HTTP 原理。

**Android**

[Android最新Support V4包大拆分有用吗？](http://mp.weixin.qq.com/s?__biz=MzAxNjI3MDkzOQ==&mid=2654472617&idx=1&sn=f8a61e2232c40329d83b05e94d5a7159&scene=4#wechat_redirect)

近日Google更新的Support Library版本，其中最为显眼的功能莫过于support-v4的大拆分，然而这个拆分现在看来并没有那么美好。v4包从2011年开始引入，包含ViewPager、FragmentActivity等我们常用的功能，目前已经达到1.3M，Google此次升级将这个库拆分为5个子的Module，每个Module可以被单独引用。阅读文章，了解更多最新Support V4的细节知识。

[猎豹"快切App"中用到的Android开发技巧探索（附源码）](http://blog.csdn.net/u013045971/article/details/52119117)

快切是从猎豹的Clear Master中分离出来的一个悬浮窗小工具。因为对这个比较感兴趣，博主断断续续花了2个月时间完成了一个类似块切的版本，起了个名字叫“Well Swipe”，中文名叫“Well 划划”。本文详细介绍了该项目开发中遇到的一些坑和技巧，同时给大家揭密了块切开发过程中用到的自定义控件技术细节。

[Android进程保活招式大全](http://dev.qq.com/topic/57ac4a0ea374c75371c08ce8)

目前市面上的应用，貌似除了微信和手Q都会比较担心被用户或者系统（厂商）杀死问题。Android进程拉活包括两个层面：一个是提供进程优先级，降低进程被杀死的概率，另一个是在进程被杀死后，进行拉活。本文从这两方面为我们详细讲解了如何进行保活操作。

## 开源项目

**iOS**

[StyleKit](https://github.com/146BC/StyleKit)

使用 JSON 文件定制 UI Style 的 Swift 框架，支持自定义解析文本 Style 。

[ChineseIDCardOCR](https://github.com/KevinGong2013/ChineseIDCardOCR)

中国二代身份证识别 Swift 框架。

[ReactiveAutomaton](https://github.com/inamiy/ReactiveAutomaton)

基于 ReactiveCocoa 实现的状态机框架，灵感来自于 Redux 和 Elm ，同时还有基于 RxSwift 版本的状态机 RxAutomaton。


**Android**

[GuideView](https://github.com/binIoter/GuideView)

轻量级的新手引导库，能够快速为任何一个View创建一个遮罩层，支持单个页面，多个引导提示，支持为高亮区域设置不同的图形，支持引导动画，方便扩展

[Jgraph](https://github.com/mychoices/Jgraph)

这是一个实现了线形、柱状、点状风格的图表效果，并且提供了动画功能。

[SlackLoadingView](https://github.com/JeasonWong/SlackLoadingView)

一款效果很赞的加载动画，作者还写了一篇[教程](http://www.wangyuwei.me/2016/08/15/%E6%89%8B%E6%91%B8%E6%89%8B%E6%95%99%E4%BD%A0%E5%86%99Slack%E7%9A%84Loading%E5%8A%A8%E7%94%BB/)专门介绍该动画的实现过程。

## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**Android/iOS工程师 by 谁叫随到**

地点北京。O2O创业公司招募技术中坚，有机会成为技术合伙人。要求2年以上移动开发经验，能承担独立开发工作。薪资面议。建立发送至 hrytn2016@dingtalk.com

## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。


----
