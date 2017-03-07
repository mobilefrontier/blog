+++
date = "2017-03-07T21:07:47+08:00"
title = "移动开发每周阅读清单：第四十七期"
description = "据一些业内人士透露，Apple 在以色列有一个超过 1000 人的工程师团队正在进行与 AR 技术相关的研发工作。年内的新一代 iPhone 可能加入 AR 技术，用于创建 3D 影像，可能还会有一个基于 AR 技术的软件开发工具包。"
+++


## 新闻

[Apple 提供上千名工程师在以色列研发 AR 相关项目](http://uk.businessinsider.com/ubs-apple-1000-engineers-ar-2017-2)

Apple CEO Tim Cook 不止一次在公开场合表示过，Apple 一直在 AR 领域投资并看好它的长期发展。据一些业内人士透露，Apple 在以色列有一个超过 1000 人的工程师团队正在进行与 AR 技术相关的研发工作。年内的新一代 iPhone 可能加入 AR 技术，用于创建 3D 影像，可能还会有一个基于 AR 技术的软件开发工具包。

[Android Studio 2.3 正式版发布](http://www.cnbeta.com/articles/soft/589699.htm)

谷歌最近公布了Android Studio 2.3正式版。新版本增加了对WebP的支持；ConstraintLayout库支持更新和布局编辑器的部件面板。提供一个新的App Link助手可以帮助你在应用中构建Uri的统一视图。新的运行按钮提供更直观和可靠的立即运行体验。最后是Android模拟器的测试，支持文本的复制和粘贴。

## 教程

**iOS**

[iOS 触摸事件的流动](http://shellhue.github.io/2017/03/04/FlowOfUITouch/)

本文介绍了从手指触摸屏幕开始，手机都发生了什么事情。

[如何在 iOS 开发中更好的做假数据？](http://shellhue.github.io/2017/02/07/fakedata/)

在繁重的开发时，后端可能没有提供接口，你可以从本文中了解到几种提供假数据的方案。

[使用 Danger 提高 Code Review 体验](http://blog.dianqk.org/2017/02/28/use-danger/)

在 Code Review 时，我们可能经常要去检查各种事情，比如 pr 是否提到了 develop 分支、commit 中是否有毒（存在 merge commit）、禁止某些文件在 pr 中有修改、pr 的描述是否正常等等各种事情。有时我们会忘记检查这些事情，merge 之后才发现，这个就非常尴尬了。使用 Danger 可以很好的帮我们避免上述低级错误的发生，本文对 Danger 进行了使用相关的介绍。

[硅谷和国内的 iOS 开发到底有何不同？](http://www.jianshu.com/p/63aec174bdb7)

本文介绍了作者在游览国内各公司后的体会，你可以从中了解到国内外对 Swift 不同见解、 iOS 开发需求成都、PM 素质差异、面试上流程的差异。

[UIViewController 相关生命周期总结](http://amztion.com/2016/12/03/uiviewcontroller-lifecycle/)

本文介绍了 UIViewController 生命周期相关内容，你可以从中了解到诸如 `loadView` 、`viewDidLoad` 被调用时都发生了什么。

**Android**

[Android 7.0应用启动流程分析](http://blog.csdn.net/dd864140130/article/details/60466394)

所谓冷启动就是启动应用时，后台没有该应用的进程，此时系统会创建一个进程分配给它(AMS通过Socket和Zygote通信，Zygote通过forkAndSpecialize()方法向Linux内核申请新进程)，之后会创建和初始化Application，然后通过反射执行ActivityThread中的main方法。本文结合源码，详细分析了应用冷启动的过程。

[浅谈Android Hook技术](https://sec.xiaomi.com/article/23)

xposed是阿里开源的框架，xposed通过替换`/system/bin/app_process`程序控制zygote进程，使得`app_process`在启动过程中会加载`XposedBridge.jar`这个jar包，从而完成对Zygote进程及其创建的Dalvik虚拟机的劫持。Frida是一款基于python+javascript的hook框架，通杀Android\iOS\linux\win\osx等各平台，由于是基于脚本的交互，因此相比xposed和substrace cydia更加便捷，本文介绍两个框架在Android下面的使用。

[Android LayoutInflater源码解析](http://allenfeng.com/2017/02/24/how-android-layout-inflater-work/)

大家对LayoutInflater一定不陌生，LayoutInflater是一个用于将xml布局文件加载为View或者ViewGroup对象的工具，我们可以称之为布局加载器。在Fragment的onCreateView方法、ListView Adapter的getView方法等许多地方都可以见到它的身影。本文详细介绍了LayoutInflater的用法以及加载布局的工作原理。

[Android恶意软件开发的新技术 | 360恶意软件专题报告](http://www.leiphone.com/news/201703/gCh1K5FTWRh5LQi6.html?winzoom=1)

2016年全年，从手机用户感染恶意程序情况看，360互联网安全中心累计监测到Android用户感染恶意程序2.53亿，平均每天恶意程序感染量约为70万人次。从恶意软件开发技术角度看，2016年恶意软件利用社会工程学、界面劫持、破解接口、开源项目、简易开发工具、碎片化代码、注入系统根进程、篡改系统引导区以及代理反弹技术，成为主要使用的新技术。


## 开源项目

**iOS**

[Swashbuckler](https://github.com/pkluz/Swashbuckler)

你可以写像 CSS 一样的方式书写 iOS 上的样式代码。

[Format](https://github.com/marmelroy/Format)

支持格式化数字、手机号、金额的组件。

[TVButton](https://github.com/marmelroy/TVButton)

在 iOS 上使用 Apple TV Button 的效果。

[ObjectiveKit](https://github.com/marmelroy/ObjectiveKit)

对 Swift 友好的 Objective-C Runtime API 。



**Android**

[Android-Debug-Database](https://github.com/amitshekhariitbhu/Android-Debug-Database)

Android Debug Database 是一个功能强大的数据调试工具。使用改工具，我们可以通过浏览器查看、编辑数据库、shared preferences，强烈推荐使用。

[vlayout](https://github.com/alibaba/vlayout)

vlayout是手机天猫Android版内广泛使用的一个基础UI框架项目。提供了一个用于RecyclerView的自定义的LayoutManger，可以实现不同布局格式的混排，目标是支撑客户端native页面的快速开发。它也是Tangram框架的基础模块。

[WeiXinRecordedDemo](https://github.com/Zhaoss/WeiXinRecordedDemo)

高仿微信视频录制，涂鸦水印添加，基于ffmpeg实现了视频拍摄及合成，图片与视频合成等。

## 工作

> 有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

上周我们发布了[移动开发前线招聘季活动](https://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651113136&idx=1&sn=8227a7c540cf1eadcbefd70036f4c8ce)，目前已有十多个职位发布，欢迎同学们到这里找工作，还有招聘需求的可以回复该贴，我会更新上去。

## 活动


> 宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[GMTC 2017全球移动技术大会](http://gmtc.geekbang.org/?utm_source=infoq&utm_campaign=bornmobile&utm_medium=wechat)

6月9日北京举行。关注移动、前端、跨平台、AI应用等多个技术领域、促进全球技术交流，推动国内技术升级。GMTC为期两天，面向移动开发、前端、AI技术人员，聚焦前沿技术及实践经验，打造技术人员的学习和交流平台。

[QCon北京站2017](http://2017.qconbeijing.com/)

2017年4月16日北京举行。明年第一场最值得期待的综合性技术大会。QCon内容源于实践并面向社区，演讲嘉宾依据热点话题，面向5年以上工作经验的技术团队负责人、架构师、工程总监、高级开发人员分享技术创新和最佳实践。