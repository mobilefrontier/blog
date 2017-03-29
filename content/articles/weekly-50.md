+++
date = "2017-03-29T21:07:47+08:00"
title = "移动开发每周阅读清单：第五十期"
description = "Apple 发布了 iOS 10.3 ，带来了新的 Apple ID 页面，增加了允许 App 内评分及留言、APFS、Find My AirPods 等功能。（当然也发布了 Xcode 8.3）。"
+++


## 新闻

[Apple 发布 iOS 10.3](https://www.macrumors.com/2017/03/27/apple-releases-ios-10-3/)

Apple 发布了 iOS 10.3 ，带来了新的 Apple ID 页面，增加了允许 App 内评分及留言、APFS、Find My AirPods 等功能。（当然也发布了 Xcode 8.3）。

[Android O Developer Preview 终于推出啦！](http://developers.googleblog.cn/2017/03/android-o-developer-preview.html)

谷歌在系统上的更新一直很积极，安卓系统可以说在市场的占占有率是很高的，谷歌在系统迭代上一直非常积极，Android N市场占有率还没到两位数时，Google发布了首个Android O开发者预览版。 在接下来的几个月中，Google 将发布开发者预览版的更新，更多详情将在今年5月的Google I/O大会上揭晓。

## 教程

**iOS**

[[Profiling your Swift compilation times](http://irace.me/swift-profiling)

Swift 的编译速度非常慢（Swift 3.1 略有改进），本文介绍了如何在项目中检查每个方法的编译时间，以及如何使用 `xcodebuild` 更好地筛选出编译时间较长的方法。

[RxSwift 处理错误例子 - 上传图片](https://blog.dianqk.org/2017/03/27/handle-error-example-upload-image/)

上传图片通常我们会选择一些对象存储服务减少对服务器的压力，为此我们就需要先上传图片到对象存储服务器中，再将上传完成的图片链接配合其他参数返回给我们的服务器，本文介绍了一种如何处理上述相对复杂逻辑的方案。

[iOS 自动构建命令——xcodebuild](http://www.jianshu.com/p/3f43370437d2)

通常我们使用 Xcode 提供的 GUI 方式编译项目，`xcodebuild` 是一个命令行工具，你可以用它来完成一些自动化的操作，本文介绍了 `xcodebuild` 的基本使用。

[Variable Height Table View Header](https://useyourloaf.com/blog/variable-height-table-view-header/)

为了适配不同屏幕的大小，我们可能需要动态修改 TableView 的 HeaderView 的高度，本文介绍了一种比较好的动态修改高度方案。

[如何优雅地使用 KVO](http://draveness.me/kvocontroller/)

KVO 作为 iOS 中一种强大并且有效的机制，为 iOS 开发者们提供了很多的便利；我们可以使用 KVO 来检测对象属性的变化、快速做出响应，这能够为我们在开发强交互、响应式应用以及实现视图和模型的双向绑定时提供大量的帮助。但是在大多数情况下，除非遇到不用 KVO 无法解决的问题，笔者都会尽量避免它的使用，这并不是因为 KVO 有性能问题或者使用场景不多，总重要的原因是 KVO 的使用是在是太麻烦了。本文介绍了优雅的解决方案 [KVOController](https://github.com/facebook/KVOController) 。

**Android**

[小微团队怎么玩转App自动化测试](https://mp.weixin.qq.com/s/LHJF5knghtlimQB3qOp1WA)

App自动化测试一直是小微团队很少会去涉足的领域，在互联网快速迭代这个大场景下，随着业务发展，回归压力逐渐增大。相信每次因为回归覆盖不足而导致线上事故，懊恼郁闷到要砸桌子的绝对不止我一个。一般情况小微团队的测试包括回归测试都是人工进行的，一些偏离主流程却又比较关键的业务往往是人工回归测试容易遗漏的。本文给出了小团队进行自动化测试的方案，推荐小团队的开发者阅读。

[Android 优化APP 构建速度的17条建议](http://www.jianshu.com/p/a1cc8f2e0877)

较长的构建时间将会减缓项目的开发进度，特别是对于大型的项目，app的构建时间长则十几分钟，短则几分钟，长的构建时间已经成了开发瓶颈，本篇文章根据Google官方文档，外加作者的一些理解，目的是提供一些提升app构建速度的优化建议。

[是时候和 Implict Broadcast 说再见了](https://zhuanlan.zhihu.com/p/26029881)

Android O对于系统广播（Broadcast）的改变归根结底都是为了进一步的节省功耗。Google在Android Marshmallo(6.0, API level 23)中引入了Doze and App Standby来改进Android系统的电池表现。本文主要介绍了Android O中对Broadcast的改变。

[一个完整的示例：Android Things和TensorFlow能擦出怎样的火花？](https://mp.weixin.qq.com/s/9eLTmtzY-yGuMitXm0iEnA)

现在深度学习很火，那我们就在Android Things中，利用摄像头抓拍图片，让TensorFlow去识别图像，最后用扬声器告诉我们结果。是不是很酷？阅读文章，了解具体实现。

[Android渲染优化](http://wuxiaolong.me/2017/03/26/Rendering/)

Android系统每隔16ms发出VSYNC信号，触发对UI进行渲染，要每次渲染都成功，这样就必须达到流畅的画面所需要的60fps，否则会发生丢帧的现象，丢帧越多，用户明确感到卡顿。卡顿现象，由于复杂的布局或界面过度绘制未能在每帧16ms内完成导致的。本文讲解了渲染优化的技巧。


## 开源项目

**iOS**

[BuildTimeAnalyzer-for-Xcode](https://github.com/RobertGummesson/BuildTimeAnalyzer-for-Xcode)

Swift 编译时间分析的工具，Swift开发必备。

[Few.swift](https://github.com/joshaber/Few.swift)

类似于 React 写法的组件库，基于Swift。

[FengNiao](https://github.com/onevcat/FengNiao)

检查项目中无用资源的工具，喵神出品。

[AutoToggleHeaderFooterView](https://github.com/recruit-lifestyle/AutoToggleHeaderFooterView)

为你的滚动视图添加随手势变化的动态Header Footer UI 组件。



**Android**

[AppMethodOrder](https://github.com/zjw-swun/AppMethodOrder)

一个能让你了解所有函数调用顺序的Android库（无需侵入式代码）。原理就是基于android sdk中提供的工具——traceview，和dmtracedump。traceview会生成.trace文件，该文件记录了函数调用顺序，函数耗时，函数调用次数等等有用的信息。

[android-tips-tricks](https://github.com/nisrulz/android-tips-tricks)

该项目收集了Android开发需要的一些小技巧。

[FlipsideCamera](https://github.com/andyb129/FlipsideCamera)

很有意思的一个项目，支持前后摄像头拍摄照片显示在同一屏幕，并且提供了滤镜功能。

## 工作

> 有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

3月初我们发布了[移动开发前线招聘季活动](https://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651113136&idx=1&sn=8227a7c540cf1eadcbefd70036f4c8ce)，目前已有十多个职位发布，欢迎同学们到这里找工作，还有招聘需求的可以回复该贴，我会更新上去。

**iOS高级工程师1名 by 银如意App**

坐标上海。上市公司移动团队，负责开发维护银如意App，要求移动开发经验4年，职位工程师，薪资面议，简历发送至邮箱：wangsu2004@163.com

**Android高级开发工程师N名 by APUS公司客户端研发团队**

坐标北京。负责开发维护客户端App，要求移动开发经验5年，职位高级Android开发，薪资40K左右～简历发送至邮箱：zhanghongjiao@apusapps.com

## 活动


> 宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[GMTC 2017全球移动技术大会](http://gmtc.geekbang.org/?utm_source=infoq&utm_campaign=bornmobile&utm_medium=wechat)

6月9日北京举行。关注移动、前端、跨平台、AI应用等多个技术领域、促进全球技术交流，推动国内技术升级。GMTC为期两天，面向移动开发、前端、AI技术人员，聚焦前沿技术及实践经验，打造技术人员的学习和交流平台。8折倒计时啦！

[QCon北京站2017](http://2017.qconbeijing.com/)

4月16日北京举行。明年第一场最值得期待的综合性技术大会。QCon内容源于实践并面向社区，演讲嘉宾依据热点话题，面向5年以上工作经验的技术团队负责人、架构师、工程总监、高级开发人员分享技术创新和最佳实践。

[第二届 @Swift 开发者大会](http://www.bagevent.com/event/378252)

5.13-14 在深圳举办。邀请到了 Uber 的 iOS 负责人，RayWenderlich CTO，CocoaPods 核心团队成员，Realm 核心成员，RxSwift 作者，Perfect 作者，唐巧，虾神，以及来自腾讯、Google、ThoughtWorks、美团、滴滴的技术大牛。输入邀请码「infoq」，每张票优惠 79 元，只能使用 50 次，先到先得。

[MTSC 2017第三届中国移动互联网测试开发大会](http://test-china.org/)

7月15日北京举行。MTSC是一个为期一天的围绕移动测试开发技术的非营利国际性技术大会，主要关注移动互联网和移动应用方面的测试开发技术。期间我们将邀请众多国内外顶尖的测试人员来分享他们的知识及对测试的独到见解。