+++
title = "移动开发每周阅读清单：第二十三期"
date = "2016-08-08T21:33:45+08:00"
description = "微博网友曝光疑似 iPhone 7 工程测试机的照片，工程机的造型和坊间传闻的 iPhone 7 基本一致，后置摄像头仍然凸起，照片上开机后运行的系统可能是 Apple 测试系统。"
tags = ""
+++



## 新闻

[疑似 iPhone 7 工程样机曝光：运行苹果测试系统](http://appleinsider.com/articles/16/08/04/new-alleged-iphone-7-pictures-surface-show-installed-apple-test-software)

微博网友曝光疑似 iPhone 7 工程测试机的照片，工程机的造型和坊间传闻的 iPhone 7 基本一致，后置摄像头仍然凸起，照片上开机后运行的系统可能是 Apple 测试系统。

[Android 7.0采用独特的Home按键设计](http://app.techweb.com.cn/android/2016-08-06/2370858.shtml)

Home按键能够有怎样独特的功能？无论是苹果iOS还是Android都有自己的Home按键，功能实际上都差不多，只不过分为物理实体按键和虚拟按键。当然也有很多有实力的厂商自己开发独特功能的Home按键，比如国内的魅族和ZUK。最近谷歌Android 7.0版本的新Home按键被泄露。从泄露的动态图看，这这次谷歌打算给Home按键带来点不一样的内容。

## 教程

**iOS**

[Swift 3 新变化](http://swift.gg/2016/07/27/swift3-changes/)

Swift 3 正式版即将发布，如果你的项目正在考虑从 Swift 2 迁移到 Swift 3，本文正合口味。文章介绍了为了让 Swift 3 变得更加安全、易读、简洁做的那些“破坏性的改动”。

[为什么必须用汇编实现 objc_msgSend](http://arigrant.com/blog/2014/2/12/why-objcmsgsend-must-be-written-in-assembly)

用汇编实现 objc\_msgSend 的真正原因并未只是追求速度、性能，本文解释了为什么实现 objc\_msgSend 只能采用汇编的方案。中文翻译见[翻译-为什么 objc_msgSend 必须用汇编实现](http://tutuge.me/2016/06/19/translation-why-objcmsgsend-must-be-written-in-assembly/)。

[活久见的重构 - iOS 10 UserNotifications 框架解析](https://onevcat.com/2016/08/notification/)

iOS 10 把很多通知相关的“老朋友”干掉了，本文回顾了 iOS 通知的历史，然后通过例子来展示新系统中通知的特性和使用方式。全面适配为时尚早，但是未雨绸缪总没有错。


**Android**

[Android N混合编译与对热补丁影响解析](https://mp.weixin.qq.com/s?__biz=MzAwNDY1ODY2OQ==&mid=2649286341&idx=1&sn=054d595af6e824cbe4edd79427fc2706&scene=0)

大约在六月底，Tinker在微信全量上线了一个补丁版本，随即华为反馈在Android N上微信无法启动。冷汗冒一地，Android N又搞了什么东东？为什么与instant run保持一致的补丁方式也会出现问题？本文详细介绍了Android N混合编译对热补丁的影响。

[Android端外推送到底有多烦？](http://mp.weixin.qq.com/s?__biz=MzA4NTg1MjM0Mg==&mid=2657261350&idx=1&sn=6cea730ef5a144ac243f07019fb43076#rd)

说Android端外推送比较烦，实际有两层意思：首先是实现麻烦，其次是市场混乱。无论是你花费了多少功夫，做了多少优化，仍然可能存在推送不到或推送延迟的情况。本文的目的，就是站在一个App开发团队的角度，集中讨论两方面的问题：如何对各家的推送平台进行技术选型；在集成各家推送平台的SDK的时候，应该重点关注哪些问题。

[Android开发架构规范](http://www.jianshu.com/p/99239b9c1630)

在开发中，一个良好的开发习惯以及一个开发规范可能会让你少走很多弯路，也会一定程度上的提高代码的可读性，可维护性和可拓展性。当随着需求的不断变更，需要维护项目的时候。当随着项目的代码量的提升，需要重构的时候，便会明白一个好的开发规范多么多么的重要。本文作者整理了自己在Android开发中的一些规范，希望对大家有参考意义。



## 开源项目

**iOS**

[Sample Code - Apple Developer](https://developer.apple.com/sample-code/wwdc/2016/)

WWDC 已经过去了一个多月，Apple 更新了 WWDC 2016 示例代码。

[Typeset](https://github.com/Draveness/Typeset)

简单、优雅的处理富文本 Objectice-C 框架，支持链式调用、灵活的匹配字符串方案。

[CCRequest](https://github.com/xincc/CCRequest)

支持多种 Cache 的网络框架，基于 AFNetworking 3.0 。

[ColorMatchTabs](https://github.com/Yalantis/ColorMatchTabs)

漂亮、简洁的顶部 TabBar Swift 框架。


**Android**

[Luban](https://github.com/Curzibn/Luban)

目前做App开发总绕不开图片这个元素。但是随着手机拍照分辨率的提升，图片的压缩成为一个很重要的问题。单纯对图片进行裁切，压缩已经有很多文章介绍。但是裁切成多少，压缩成多少却很难控制好，裁切过头图片太小，质量压缩过头则显示效果太差。于是自然想到App巨头“微信”会是怎么处理，Luban（鲁班）就是通过在微信朋友圈发送近100张不同分辨率图片，对比原图与微信压缩后的图片逆向推算出来的压缩算法。

[TastyToast](https://github.com/yadav-rahul/TastyToast)

TastyToast是一款自定义的Android Toast，比系统自带的Toast效果美观了很多。

[AndroidSweetSheet](https://github.com/zzz40500/AndroidSweetSheet)

这是一个带有动画的Sheet，动画效果很赞。




## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**Android工程师 by 美甲帮**

地点北京。负责公司App开发。要求熟悉Java和Android，有良好的工程素养。薪资面议。简历发送至 lexchen@mooyoo.com.cn

**Android高级工程师 by 微鲸科技**

地点上海。负责Android多媒体开发。要求本科3年(硕士1年)以上工作经验。薪资面议。简历发送至 logan62334@gmail.com

**iOS/Android 高级工程师 by 阿里国际事业部**

地点杭州。招P6、P7级别工程师和技术专家。要求有多个完整项目经验。待遇20-50K。简历发送至 blacktea.hw@alibaba-inc.com

## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[APMCon中国应用性能管理大会](http://www.bagevent.com/event/109881)

8月18日~19日在北京召开。聚焦于应用性能管理垂直领域的盛会。来自LinkedIn、AppDynamics、阿里巴巴、腾讯、京东、新浪、美团、360等国内外一线互联网公司的技术专家将给大家带来精彩的演讲分享！

----
