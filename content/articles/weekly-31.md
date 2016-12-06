+++
title = "移动开发每周阅读清单：第三十一期"
date = "2016-10-10T21:33:45+08:00"
description = "和我们之前的推测一样，Google放弃了Nexus品牌，转而推出了两款Pixel打头的手机——Pixel和Pixel XL。和之前和Nexus手机相比，Pixel有两点明显的不同：第一是手机硬件上由Google旗下的Pixel团队研发，不再受制于OEM厂商（Pixel和Pixel XL的背部甚至没有出现其制造商HTC的名字）；第二点是很Pixel的定价，很贵，恩。"
tags = ""
+++


## 新闻

[第一部Google牌手机来了](http://www.geekpark.net/topics/216887)

和我们之前的推测一样，Google放弃了Nexus品牌，转而推出了两款Pixel打头的手机——Pixel和Pixel XL。和之前和Nexus手机相比，Pixel有两点明显的不同：第一是手机硬件上由Google旗下的Pixel团队研发，不再受制于OEM厂商（Pixel和Pixel XL的背部甚至没有出现其制造商HTC的名字）；第二点是很Pixel的定价，很贵，恩。

[Apple 中国研发中心在中关村成立](http://it.sohu.com/20160929/n469386940.shtml)

北京中关村园区管理委员会披露，Apple 研发（北京）有限公司在中关村朝阳园成立。该公司是苹果公司在中国第一家直接投资的研发中心。未来，该研发中心将致力于计算机软硬件、通讯、音频和视频设备、消费电子产品技术及信息技术等技术。

## 教程

**iOS**

[让支持 VoiceOver 成为一种习惯](https://zhuanlan.zhihu.com/p/22776897)

作者因为收到视瞕用户反馈，决定让自己的 App 支持 VoiceOver 。在本文中作者分享了支持 VoiceOver 的基本开发指导。It’s the right thing to do。

[I create iOS apps - is RxSwift for me?](https://realm.io/news/tryswift-Marin-Todorov-I-create-iOS-apps-is-RxSwift-for-me/)

Marin Todorov 分享了将 RxSwift 应用到实际开发的一些经验，特别是在多个 ViewController 之间复杂交互的思考。

[CocoaPods 都做了什么？](http://draveness.me/cocoapods/)

作者分享了为什么 CocoaPods 和 Fastlane 都使用 Ruby 编写，并分析介绍了 CocoaPods 的工作原理。

[黑科技：把第三方 iOS 应用转成动态库](http://mp.weixin.qq.com/s?__biz=MjM5NTIyNTUyMQ==&mid=2709545228&idx=1&sn=7a47a0de32e06f9c465319e8db8ca13f&chksm=828f0bd2b5f882c46416ab20cd9ea482b3c57b202d876b75d5625a1bb036d40fe01d31c2679a&scene=0#wechat_redirect)

本文作者介绍了自己写的一个工具，能够把第三方 iOS 应用转成动态库，并加载到自己的 App 中，文章最后以支付宝为例，展示如何调用其中的 C 函数和 Objective-C 方法。


**Android**

[Activity到底是什么时候显示到屏幕上的呢](http://mp.weixin.qq.com/s?__biz=MzIwOTQ1MjAwMg==&mid=2247483771&idx=1&sn=fc2a36bddd29a0bb9d6512ba7e9b71ad&chksm=9772eff6a00566e0424e3bccfcf61df5bff709739ece80c6641ca6cf742e9949c27f29bc48f0&mpshare=1&scene=1&srcid=1008ksnBumwlSEhlQl3Qe45O#rd)

统计App冷启动时间，这个任务看上去不难，但是要求统计出来的时间要准，要特别准。意思就是必须要按Activity绘制到屏幕上这个时间节点作为标杆，来进行统计工作。毕竟如果是因为视图处理不当而导致的measure/layout/draw耗时太久，这是不能忍的，需要及时统计到。由于这件事情还算有意义，所有作者就深挖了一下，本文是作者的深挖过程。

[搭建 Android 7.0的源码环境](http://android.jobbole.com/84924/)

Google已发布Android 7.0源码，想要快人一步，先下载源码一睹为快。本文详细解决了搭建Android 7.0的源码环步骤。

[App优化之电池省着用](http://www.jianshu.com/p/c55ef05c0047)

电量使用优化，基本上是我们最不怎么关注的一项优化。可能很多公司连QA/Tester也不会关注测试App电量的使用。一般来说开发和测试的测试设备也一直是连着USB处于充电状态的，感官上也体会不到电量的损耗。然而，对于用户来说，实际上App的电量损耗也是用户体验的一个方面。特别是当今人们对移动设备的依赖度越来越高，电量也是用户特别关注的。本文详细介绍了电量的优化方法。

[WatchDog工作原理](http://android.jobbole.com/84881/)

Android系统中，有硬件WatchDog用于定时检测关键硬件是否正常工作，类似地，在framework层有一个软件WatchDog用于定期检测关键系统服务是否发生死锁事件。WatchDog功能主要是分析系统核心服务和重要线程是否处于Blocked状态。

## 开源项目

**iOS**

[rx-sample-code](https://github.com/DianQK/rx-sample-code)

多个有趣的使用 RxSwift 完成的 Demo 。

[Import](https://github.com/markohlebar/Import)

支持在任意行键入 import 引入 framework 的 Xcode Extensions 。

[pbxprojHelper](https://github.com/yulingtianxia/pbxprojHelper)

pbxprojHelper 可以让你通过原生 UI 应用来创建和修改 Xcode 工程，同时支持在终端使用。

[punic](https://github.com/schwa/punic)

比 Carthage 更好用的依赖管理工具，可定制性更高，速度更快。



**Android**

[okhttp-OkGo](https://github.com/jeasonlzy/okhttp-OkGo)

该库是封装了okhttp的网络框架，支持大文件上传下载，上传进度回调，下载进度回调，表单上传，链式调用，可以自定义返回对象，支持Https和自签名证书，支持cookie的持久化和自动管理，支持四种缓存模式缓存网络数据，支持301和302重定向，扩展了统一的上传管理和下载管理功能。

[yyquan](https://github.com/jiangzehui/yyquan)

一款基于Xmpp协议的即时通讯社交软件(客户端+服务端)。

[FreshDownloadView](https://github.com/dudu90/FreshDownloadView)

这是一组跟踪下载过程的动画，包括下载进度、下载状态、重置。




## 工作

> 新开栏目，有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

本期暂无工作推荐。



## 活动

> 新栏目之二，宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

----

[QCon上海高并发与实时处理架构设计专场](http://form.mikecrm.com/OIFtbP)

将分享大规模实时流处理平台架构以及实时消息推送架构，并从稳定性和实时性两个方面探讨即时通讯云实践，还将揭示海量数据推送服务背后的挑战，希望能帮助开发者了解解决现实问题的新思路。
