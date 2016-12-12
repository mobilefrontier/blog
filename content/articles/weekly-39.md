+++
date = "2016-12-12T23:07:47+08:00"
title = "移动开发每周阅读清单：第三十九期"
description = "上周苹果公布了 2016 年度 App & 游戏，Prisma 和 Clash Royale 成为最大赢家。音乐制作应用 Medly 和色彩跑酷 Chameleon Run 获得年度优秀 App & 游戏。Pin、VUE 等 16 款应用入选国区年度十佳。"
+++


## 新闻

[苹果公布 2016 年度 App & 游戏榜单](http://www.ithome.com/html/iphone/278578.htm)

上周苹果公布了 2016 年度 App & 游戏，Prisma 和 Clash Royale 成为最大赢家。音乐制作应用 Medly 和色彩跑酷 Chameleon Run 获得年度优秀 App & 游戏。Pin、VUE 等 16 款应用入选国区年度十佳。

[Google Developers中国网站发布](https://mp.weixin.qq.com/s?__biz=MzAwODY4OTk2Mg==&mid=2652040364&idx=1&sn=57f9d3a7fe5db730f448c0eaa2f8ddc0)

Google Developers 中国网站是特别为中国开发者而建立的，它汇集了 Google 为全球开发者所提供的开发技术资源，包括 API 文档、开发案例、技术培训的视频。[谷歌开发者中文博客](http://developers.googleblog.cn/)是另一个谷歌新发布的中文博客站点，这个博客以中文的形式向中国的开发者提供了来自全球的谷歌开发者博客的翻译文章。


## 教程

**iOS**

[到年底了，为什么不在 iOS 上尝试 ReX 呢？](https://medium.com/@DianQK/%E5%88%B0%E5%B9%B4%E5%BA%95%E4%BA%86-%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%8D%E5%9C%A8-ios-%E4%B8%8A%E5%B0%9D%E8%AF%95-rex-%E5%91%A2-f8e27d19f488#.r3o0jv4cf)

本文介绍了作者对 RxSwift 实践较长一段时间的思考结果，整体框架参考了 Vuex 的方式。相信 ReX 是值得在 iOS 上实践的新框架。

[如何知道某个网络请求是哪个 SDK 发起的](http://mp.weixin.qq.com/s/65XQx6HszNO_n0RhQu4Qhg)

大多数的 APP 都在适配 HTTPS ，在引入了很多 SDK 的我们，需要知道如何查找某个网络请求是哪个 SDK 发起的，本文结合一个具体的例子介绍了如何查找的方案。

[是时候学习 RxSwift 了](http://limboy.me/tech/2016/12/11/time-to-learn-rxswift.html)

相信在过去的一段时间里，对 RxSwift 多少有过接触或耳闻，或者已经积累了不少实战经验。本文主要针对那些在门口徘徊，想进又拍踩坑的同学。

[Consistent, Thin, & Dumb: Redesigning the Spotify iOS App](https://realm.io/news/mbltdev-hector-zarate-consistent-thin-dumb-spotify/)

团队人多了后，写 UI 的代码很容易出现不一致的情况，比如同一类型的按钮在不同屏幕大小颜色有出入， UI 代码容易变得臃肿。本文介绍了 Spotify 的 iOS 团队是如何解决这个问题的。


**Android**

[Android增量编译3～5秒的背后](http://www.jianshu.com/p/37e31d924be9)

Freeline是由蚂蚁聚宝Android团队开发的一款针对Android平台的增量编译工具。它可以充分利用缓存文件，在几秒钟内迅速地对代码的改动进行编译并部署到设备上，有效地减少了日常开发中的大量重新编译与安装的耗时。本文主要介绍了freeline是如何实现快速增量编译的。

[MultiDex工作原理分析和优化方案](https://zhuanlan.zhihu.com/p/24305296)

MultiDex是Google为了解决“65535方法数超标”以及“INSTALL_FAILED_DEXOPT”问题而开发的一个Support库。当一个Dex文件太大的时候（方法数目太多、文件太大），在打包Apk文件的时候就会出问题，就算打包的时候不出问题，在Android 5.0以下设备上安装或运行Apk也会出问题。既然一个Dex文件不行的话，那就把这个硕大的Dex文件拆分成若干个小的Dex文件，刚好一个ClassLoader可以有多个DexFile，这就是MultiDex的基本设计思路。

[Qzone视频下载如何做到多快好省？](http://mp.weixin.qq.com/s/BQxu7vXfdbd5U4izW5VTZQ)

Qzone的日均视频播放量已经突破了10亿，其中Android端的播放量在总播放量中的占比超过70%，相比年初，播放量的增长了超过10倍。视频下载是整个视频播放的基础，如果下载侧出问题，则会造成整个视频播放的失败，这就对视频下载提出了非常高的要求。本文详细介绍了Qzone团队对于下载的优化技术方案。

[微信终端跨平台组件mars系列(二) - 信令传输超时设计](http://mp.weixin.qq.com/s/PnICVDyVuMSyvpvTrdEpSQ)

mars是微信官方使用C++编写的业务性无关、平台性无关的终端基础组件，目前在微信Android、iOS、Windows、Mac、Windows Phone等多个平台中使用，并正在筹备开源。本文是微信团队介绍mars的第二篇文章。


## 开源项目

**iOS**

[SwifterSwift](https://github.com/omaralbeik/SwifterSwift)

提供了非常多的便利方法的工具。

[TTGPuzzleVerify](https://github.com/zekunyan/TTGPuzzleVerify)

拼图验证控件。

[Whisper](https://github.com/hyperoslo/Whisper)

简洁的通知和消息控件。


**Android**

[ZoomHeader](https://github.com/githubwing/ZoomHeader)

模仿饿了么详情页的效果，实现了跟随手指移动viewpager变详情页的效果。

[MyOkHttp](https://github.com/tsy12321/MyOkHttp)

MyOkHttp是对Okhttp3进行二次封装,对外提供了POST请求、GET请求、PATCH请求、PUT请求、DELETE请求、上传文件、下载文件、取消请求、Raw/Json/Gson返回、后台下载管理等功能，[这里](http://www.jianshu.com/p/219ee2afb4f3)是作者对该项目的详细介绍。

[WaveLoading](https://github.com/race604/WaveLoading)

这是一款水波纹效果的加载动画，支持自定义速度、长度等。

## 工作

> 有招聘移动开发工程师需求可以给我发邮件：amos@infoq.com，附上公司名称介绍、招聘需求、待遇、联系方式等等。我会选择一些放在这里。

**Android高级工程师 by 融360**

坐标北京。负责公司移动产品研发。要求两年以上移动开发经验，能独立承担开发任务。薪资25-30K，好的可以更高。简历发送至 39206514@qq.com

**iOS/Android高级工程师/专家 by 支付宝**

坐标上海。负责支付宝钱包、线下支付、社交等Android/iOS客户端应用架构和开发工作。要求5年客户端开发经验。职级P6-P7。简历发送至 zhengfang.zf@alibaba-inc.com

## 活动

> 宣传社区办的一些移动相关的线下活动，有想放在这里的欢迎和我打招呼，友情帮宣传。

[华为技术开放日](form.mikecrm.com/OAvnqm)

12月13日成都举行。华为发布了基于安卓7.0的EMUI5.0，通过智能学习系统优化安卓资源调度管理。华为将在成都、北京、广州举办三场EMUI5.0技术开放日，与资深极客、技术专家和花粉针对EMUI从设计到交互再到性能进行全面性的探讨交流，使广大用户对EMUI能够有更深一步的认知，并聆听用户的意见和建议，助力EMUI变得更好。