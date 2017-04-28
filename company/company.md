## **Square& JakeWharton**

| 框架名称                                     | 功能描述                                     |
| :--------------------------------------- | :--------------------------------------- |
| [Picasso](https://github.com/square/picasso) | 一个强大的图片下载与缓存的库                           |
| [OkHttp](https://github.com/square/okhttp) | Square出品，一个Http与Http/2的客户端               |
| [Retrofit](https://github.com/square/retrofit) | Square出品，类型安全的Http客户端                    |
| [ButterKnife](https://github.com/JakeWharton/butterknife) | 将Android视图和回调方法绑定到字段和方法上                 |
| [sqlbrite](https://github.com/square/sqlbrite) | 一个响应式的数据查询框架                             |
| keywhiz                                  | 一个隐私管理分配系统，能很好地与SOA配合                    |
| [LeakCanary](https://github.com/square/leakcanary) | 内存泄漏检测工具                                 |
| javapoet                                 | 动态生成Java源码                               |
| [phrase](https://github.com/square/phrase) | 字符串格式化                                   |
| [dagger](https://github.com/square/dagger) | 依赖注入框架                                   |
| Flow                                     | Flow 将一个应用分成一个逻辑上的 Screen组合，Screen不是任何形式的特殊的库对象，而是一个被创造来代表我们应用视图的普通java对象（POJO） |
| Mortar                                   | Mortar是一个专注拖拽和依赖注入的库，Mortar 用以下几个不同的部分将一个应用分为可组合的模块：Blueprints, Presenters and a boatload of custom Views |
| RxBinding                                | 可以实现数据层与View层的绑定，当数据发生变化，View会自动更新UI     |
| RxAndroid                                | RxJava的扩展, 优雅地处理异步请求                     |
| timber                                   | 对Android的Log类进行封装后的一个Log工具               |
| [ViewPagerIndicator](https://github.com/JakeWharton/ViewPagerIndicator) | Paging indicator widgets compatible with the ViewPager |
| [DiskLruCache](https://github.com/JakeWharton/DiskLruCache) | Java实现基于LRU的磁盘缓存                         |

## [JakeWharton scalpel](https://github.com/JakeWharton/scalpel)

Jake Wharton，Android开发领域传奇一般的存在，熟悉Android开发的同学应该都听说过，即便没有，也应该会经常用到他主导或参与贡献的开源 项目，他在GitHub上开源了多个Android兼容性、依赖注入相关的知名项目，目前就职Square, 也参与贡献了Square公司开源的诸如Retrofit, okhttp等热门项目。

Jake大神喜欢以刀命名自己的项目，可能他觉得这能很好的表达它们作为开发利器的犀利程度，不过没准他也很喜欢中国武侠小说呢。

他最有名的两把刀，一把是Dagger, 匕首，一个依赖注入框架，用来解耦开发中各模块依赖的，最早由他开发与维护，后来转给Google维护；另一把是同样大名鼎鼎的ButterKnife， 黄油刀，有了它，你再也不用写findViewById了，以后有机会给大家详细介绍它们。

今天的主角是它们不那么知名的小兄弟，Scalpel，这把非常酷炫实用的解剖刀。

他其实就是实现了一个三维效果的界面布局层次展示，不需要手机连接开发设备，只需要简单几行代码将其集成到你的应用中，即可开启酷炫之旅，它提供的功能包括：

- 通过setLayerInteractionEnabled(boolean)可开启与关闭此功能。

- 通过setDrawViews(boolean)可控制是否绘制View, 也就是说它可以仅仅是个简单的布局线框图，也可以是色彩丰富的真实效果图。

- 通过setDrawIds(boolean)可控制是否显示各控件的Id, 你就能知道你自己正在调试的那个控件到底在哪了？

- 通过setChromeColor，setChromeShadowColor可自定义线框图的颜色，随你喜欢。

## 阿里巴巴

| 项目名称                                     | 功能描述                                     |
| :--------------------------------------- | :--------------------------------------- |
| [freeline](https://github.com/alibaba/freeline) | Freeline 是 Android 平台上的秒级编译方案，Instant Run 的替代品，也可以从 Freeline 官方主页来获取更多的信息。Freeline 由蚂蚁聚宝 Android 团队开发，它可以充分利用缓存文件，在几秒钟内迅速地对代码的改动进行编译并部署到设备上，有效地减少了日常开发中的大量重新编译与安装的耗时。Freeline能够为Android开发者节省很多喝杯咖啡的时间 |
| [weex](https://github.com/alibaba/weex)  | A framework for building Mobile cross-platform UI |
| [fastjson](https://github.com/alibaba/fastjson) | A fast JSON parser/generator for Java    |
| [Dubbo](https://github.com/alibaba/dubbo) | Dubbo is a distributed, high performance RPC framework enpowering applications with service import/export capabilities |
| [AndFix](https://github.com/alibaba/AndFix) | AndFix is a library that offer hot-fix for Android App |
| [dexposed](https://github.com/alibaba/dexposed) | dexposed enable 'god' mode for single android application |
| [vlayout](https://github.com/alibaba/vlayout) | VirtualLayout是一个针对RecyclerView的LayoutManager扩展, 主要提供一整套布局方案和布局间的组件复用的问题 |

## 小米开源项目

| 项目名称                                     | 功能描述           |
| :--------------------------------------- | :------------- |
| [Notes](https://github.com/MiCode/Notes) | 小米便签社区开源版      |
| [FileExplorer](https://github.com/MiCode/FileExplorer) | MIUI文件管理器社区开源版 |
| [SoundRecorder](https://github.com/MiCode/SoundRecorder) | MIUI录音机社区开源版   |

## Google开源项目

| 项目名称                                     | 功能描述                                     |
| :--------------------------------------- | :--------------------------------------- |
| [GCM](https://github.com/google/gcm)     | Google Cloud Messaging 消息推送              |
| [ iosched](https://github.com/google/iosched) | Google I/O Android App                   |
| [android-topeka](https://github.com/googlesamples/android-topeka) | Google官方给出的material design应用指南           |
| [android-UniversalMusicPlayer](https://github.com/googlesamples/android-UniversalMusicPlayer) | Google官方给出的m音乐播放器，支持Android phones, tablets, Auto, Wear and Cast devices |
| [ExoPlayer](https://github.com/google/ExoPlayer) | An extensible media player for Android   |
| [guava](https://github.com/google/guava) | Google Core Libraries for Java 6+        |
| [flexbox-layout](https://github.com/google/flexbox-layout) | FlexboxLayout is a library project which brings the similar capabilities of CSS Flexible Box Layout Module to Android. |
| [guice](https://github.com/google/guice) | 轻量级的依赖注入框架                               |
| [gson](https://github.com/google/gson)   | A Java serialization/deserialization library that can convert Java Objects into JSON and back. |
| [protobuf](https://github.com/google/protobuf) | Protocol Buffers - Google's data interchange format |
| [material-design-icons](https://github.com/google/material-design-icons) | Material Design icons by Google          |
| [auto](https://github.com/google/auto)   | Auto 是 Java 生成器源代码集合，包括：AutoFactory - 兼容 JSR-330 的工厂；AutoService - ServiceLoader 的 Provider-configuration 文件；AutoValue - Java 1.6+ 的不可变 value-type 代码生成；Common - Helper 实用工具，用来编写注释处理器 |
| [android-architecture](https://github.com/googlesamples/android-architecture) | A collection of samples to discuss and showcase different architectural tools and patterns for Android apps |

## Facebook

| 项目名称         | 功能描述                                     |
| :----------- | :--------------------------------------- |
| react-native | A framework for building native apps with React |
| fresco       | 最好的图片处理框架，没有之一                           |
| rebound      | 动画库                                      |