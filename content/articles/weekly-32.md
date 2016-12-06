+++
title = "移动开发每周阅读清单：第三十二期"
date = "2016-10-24T21:33:45+08:00"
description = "Apple 正式公布新 Mac 发布会的邀请函，发布会将于 10 月 28 日凌晨 1 点召开。本次邀请函的口号与 1998 年乔布斯回归苹果后发布的第一代 iMac 宣传语 hello (again) 非常相似。本次苹果将会对多款 Mac 产品进行更新，新款 MacBook Pro 将加入 OLED 触控条、USB-C 等诸多新特性。"
tags = ""
+++


## 新闻

[Apple 发出新 Mac 发布会邀请函，本月 28 日召开](http://thenextweb.com/apple/2016/10/19/apple-plans-to-unveil-the-long-awaited-2016-macbook-at-october-27-event/)

Apple 正式公布新 Mac 发布会的邀请函，发布会将于 10 月 28 日凌晨 1 点召开。本次邀请函的口号与 1998 年乔布斯回归苹果后发布的第一代 iMac 宣传语 hello (again) 非常相似。本次苹果将会对多款 Mac 产品进行更新，新款 MacBook Pro 将加入 OLED 触控条、USB-C 等诸多新特性。发布会直达链接 [hello again](http://www.apple.com/apple-events/october-2016/)。

[Android7.1开放下载](http://digi.163.com/16/1020/11/C3QML2NQ001687H3.html)

想要获得和Pixel/Pixel XL中相同的系统版本吗？Google宣布Android 7.1开发者预览版于近日正式开放下载，尽管并非是完全版本更新但依然带来了一些新功能，包括对Daydream VR平台和GIF键盘的支持，开放制作圆形图标的相关资源和应用快捷方式（通过长按获得类似于3D Touch的使用体验）。

## 教程

**iOS**

[移动 App 兼容性测试工具 Spider](http://tech.meituan.com/spider.html)

本文总结了美团点评技术沙龙 11 期的部分内容，主要涉及 Spider 功能介绍、相关背景、功能实现。相关分享 [Slide 链接](http://www.slideshare.net/meituan/011-appspider) 。

[Realm数据库从入门到“放弃”](http://www.jianshu.com/p/50e0efb66bdf)

本文作者从入门实践到 Realm 内部原理分析，以及 Realm 当前的优势与限制，很详细。

[Swift 反射 API 及用法](http://swift.gg/2015/11/23/swift-reflection-api-what-you-can-do/)

本文作者分享了关于 Swift 中反射 API 的相关知识及其用法，并分享了一个 Struct 转换成 Core Data 的例子。


**Android**

[Android ListView与RecyclerView对比浅析--缓存机制](http://mp.weixin.qq.com/s?__biz=MzAwNDY1ODY2OQ==&mid=2649286405&idx=1&sn=414e2d2eb577884ccee5c9076e8b8357&chksm=8334c387b4434a9124f5acd93f331968a44256b8374eeafb4b1857671072b3b6364e5ec38485&scene=0#rd)

RecyclerView是谷歌官方出的一个用于大量数据展示的新控件，可以用来代替传统的ListView，更加强大和灵活。作者最近遇到了是否要将ListView替换为RecyclerView的问题。秉承着实事求是的作风，弄清楚RecyclerView是否有足够的吸引力替换掉ListView，作者从性能这一角度出发，研究RecyclerView和ListView二者的缓存机制，并得到了一些较有益的结论。

[tinker源码研读（一）：补丁生成之DexDiff原理简析](https://halfstackdeveloper.github.io/2016/10/19/tinker%E6%BA%90%E7%A0%81%E7%A0%94%E8%AF%BB%EF%BC%88%E4%B8%80%EF%BC%89%EF%BC%9A%E8%A1%A5%E4%B8%81%E7%94%9F%E6%88%90%E4%B9%8BDexDiff%E5%8E%9F%E7%90%86%E7%AE%80%E6%9E%90/)

Tinker和以往的HotFix库思路不太一样，它更像是APP的增量更新，在服务器端通过差异性算法，计算出新旧dex之间的差异包，推送到客户端，进行合成。传统的差异性算法有BsDiff，而Tinker的优秀之处就在于它自己基于Dex的文件格式，研发出了DexDiff算法。

[Android进程绝杀技--forceStop]()

话说Android开源系统拥有着App不计其数，百家争鸣，都想在这“大争之世”寻得系统存活的一席之地。然则系统资源有限，如若都割据为王，再强劲的CPU也会忙不过来，再庞大的内存终会消耗殆尽，再大容量的电池续航终会昙花一现。面对芸芸众生，无尽变数，系统以不变应万变，一招绝杀神技forceStop腾空出世，需要具有FORCE\_STOP_PACKAGES权限，当然这个并非第3方app可以直接调用的， 否则App间可以相互停止对方。


## 开源项目

**iOS**

[RxSwift](https://github.com/ReactiveX/RxSwift/releases/tag/3.0.0)

RxSwift 更新到 3.0 版本，支持 Linux 。

[WBWebViewConsole](https://github.com/Naituw/WBWebViewConsole)

将 `UIWebView` 和 `WKWebView` log 打印到 App 中，同时直接在 Console 执行 JavaScript 代码与 Web 交互。

[retriver](https://github.com/cyanzhong/retriver)

非越狱查看所有 App info.plist 。

[PAPermissions](https://github.com/pascalbros/PAPermissions)

统一系统 API 请求权限 Swift 框架。



**Android**

[GitClub](https://github.com/TellH/GitClub)

这是一个Github客户端，也是一个发现优秀Github开源项目的app。

[AndroidHttpCapture](https://github.com/JZ-Darkal/AndroidHttpCapture)

这是一款针对于移动流量劫持而开发的手机抓包软件。主要功能包括：手机端抓包、PING/DNS/TraceRoute诊断、抓包HAR数据上传分享，使用前请确保手机HTTP代理的关闭。

[BigBang](https://github.com/baoyongzhang/BigBang)

该项目模仿了Smartisan OS的 BigBang功能。




## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

本期暂无工作推荐。



## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

----

[ArchSummit全球架构师峰会](http://bj2016.archsummit.com/)

地点北京。ArchSummit秉承“实践第一、案例为主”的原则，展示新技术在行业应用中的最新实践，技术在企业转型中的加速作用，帮助企业技术管理者、CTO、架构师做好技术选型、技术团队组建与管理，并确立技术对于产品和业务的关键作用。
