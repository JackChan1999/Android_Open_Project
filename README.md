##**Square& JakeWharton**

| 框架名称|功能描述 |
| :------------- |:-------------|
| [Picasso](https://github.com/square/picasso) | 一个强大的图片下载与缓存的库|
| [OkHttp](https://github.com/square/okhttp) | Square出品，一个Http与Http/2的客户端|
| [Retrofit](https://github.com/square/retrofit) | Square出品，类型安全的Http客户端 |
| [ButterKnife](https://github.com/JakeWharton/butterknife) | 将Android视图和回调方法绑定到字段和方法上|
|[sqlbrite](https://github.com/square/sqlbrite)|一个响应式的数据查询框架|
|keywhiz|一个隐私管理分配系统，能很好地与SOA配合|
| [LeakCanary](https://github.com/square/leakcanary) | 内存泄漏检测工具 |
|javapoet|动态生成Java源码|
|[phrase](https://github.com/square/phrase)|字符串格式化|
|[dagger](https://github.com/square/dagger)|依赖注入框架|
|Flow |Flow 将一个应用分成一个逻辑上的 Screen组合，Screen不是任何形式的特殊的库对象，而是一个被创造来代表我们应用视图的普通java对象（POJO）|
|Mortar|Mortar是一个专注拖拽和依赖注入的库，Mortar 用以下几个不同的部分将一个应用分为可组合的模块：Blueprints, Presenters and a boatload of custom Views|
|RxBinding|可以实现数据层与View层的绑定，当数据发生变化，View会自动更新UI|
|RxAndroid|RxJava的扩展, 优雅地处理异步请求|
|timber|对Android的Log类进行封装后的一个Log工具|
|[ViewPagerIndicator](https://github.com/JakeWharton/ViewPagerIndicator)|Paging indicator widgets compatible with the ViewPager|
| [DiskLruCache](https://github.com/JakeWharton/DiskLruCache) | Java实现基于LRU的磁盘缓存|

##**缓存**
| 框架名称                                     | 功能描述                                     |
|:---------------------------------------- |:---------------------------------------- |
| LruCache                                 | Android原生API，内存缓存                        |
| [DiskLruCache](https://github.com/JakeWharton/DiskLruCache) | Java实现基于LRU的磁盘缓存                         |
| [ASimpleCache](https://github.com/yangfuhai/ASimpleCache) | 一个为android制定的轻量级的开源缓存框架                  |
| [base-diskcache](https://github.com/hongyangAndroid/base-diskcache) | Android 缓存库，融合了DiskLruCache和ASimpleCache |

##**图片加载**
| 框架名称                                     | 功能描述                     |
|:---------------------------------------- |:------------------------ |
| [Android Universal Image Loader](https://github.com/nostra13/Android-Universal-Image-Loader) | 一个强大的加载，缓存，展示图片的库        |
| [Picasso](https://github.com/square/picasso) | 一个强大的图片下载与缓存的库           |
| [Fresco](https://github.com/facebook/fresco) | 一个用于管理图像和他们使用的内存的库       |
| [Glide](https://github.com/bumptech/glide) | 一个图片加载和缓存的库，使用的App有：网易新闻 |
<br>
Picasso是著名的开源组织Square出品的图片处理框架，使用的比较多

Glide是Google的员工基于Picasso开发，优化的，Android官网推荐使用的图片处理框架

Fresco是Facebook开源的图片处理框架，真正做到了三级缓存，功能强大，强烈推荐使用

Android Universal Image Loader是一个老牌的图片处理框架，但是在2015年的9月份已经停止更新维护，所以不推荐使用

##**图片处理**
| 框架名称                                     | 功能描述                                     |
|:---------------------------------------- |:---------------------------------------- |
| [Picasso-transformations](https://github.com/wasabeef/picasso-transformations) | 一个为Picasso提供多种图片变换的库                     |
| [Glide-transformations](https://github.com/wasabeef/glide-transformations) | 一个为Glide提供多种图片变换的库                       |
| [Android-gpuimage](https://github.com/CyberAgent/android-gpuimage) | 基于OpenGL的Android过滤器                      |
| [MultiImageSelector](https://github.com/lovetuzitong/MultiImageSelector) | 图片选择，使用的App有：薄荷                          |
| [photoview](https://github.com/chrisbanes/PhotoView) | 使用的App有：薄荷,网易新闻                          |
| [circleimageview](https://github.com/hdodenhof/CircleImageView) | 圆形图片，使用的App有：薄荷                          |
| [RoundedImageView](https://github.com/vinc3m1/RoundedImageView) | 圆形图片，使用的App有：薄荷                          |
| [SelectableRoundedImageView](https://github.com/pungrue26/SelectableRoundedImageView) | Android ImageView that supports different radii on each corner |
| [android-crop](https://github.com/jdamcd/android-crop) | 图片裁剪，使用的App有：网易新闻，芒果TV                   |
| [android-gif-drawable](https://github.com/koral--/android-gif-drawable) | gif图片，使用的App有：网易新闻，快手                    |
| [uCrop](https://github.com/Yalantis/uCrop) | [Image Cropping Library for Android](https://yalantis.com/blog/introducing-ucrop-our-own-image-cropping-library-for-android/)，使用的App有：薄荷，哔哩哔哩 |
| [BGAPhotoPicker-Android](https://github.com/bingoogolapple/BGAPhotoPicker-Android) | Android 图片选择、预览、九宫格图片控件、拖拽排序九宫格图片控件      |
| [TakePhoto](https://github.com/crazycodeboy/TakePhoto) | 轻量级Android照片处理框架                         |
| [cropper](https://github.com/edmodo/cropper) | 图片裁剪开源框架                                 |
##**网络请求**
| 框架名称                                     | 功能描述                                     |
|:---------------------------------------- |:---------------------------------------- |
| httpclient                               | apache开源的网络请求框架，已过时                      |
| AsyncHttpClient                          | 基于httpclient封装，已过时                       |
| [OkHttp](https://github.com/square/okhttp) | Square出品，一个Http与Http/2的客户端               |
| [Retrofit](https://github.com/square/retrofit) | Square出品，类型安全的Http客户端                    |
| [Volley](https://android.googlesource.com/platform/frameworks/volley) | Google推出的Android异步网络请求框架和图片加载框架，使用的App有：网易新闻 |
<br>
从Android 6.0 开始，Google删除了apache的开源网络请求框架httpclient，所以基于httpclient的AsyncHttpClient也不推荐使用了

Volley适合那些请求频繁但数据量不大的场景，不适用于大数据的请求，比如下载文件

Android 6.0 后，Android开始使用OkHttp，而Retrofit是一个网络代理框架，可以更简单的使用OkHttp

##**网络解析**
| 框架名称                                     | 功能描述                                     |
|:---------------------------------------- |:---------------------------------------- |
| [Gson](https://github.com/google/gson)   | 一个Java序列化/反序列化库，可以将JSON和java对象互相转换       |
| [Jackson](https://github.com/codehaus/jackson) | Jackson可以轻松地将Java对象转换成json对象和xml文档，同样也可以将json、xml转换成Java对象 |
| [Fastjson](https://github.com/alibaba/fastjson) | Java上一个快速的JSON解析器/生成器                    |
| [HtmlPaser](https://sourceforge.net/projects/htmlparser/) | 一种用来解析单个独立html或嵌套html的方式                 |
| [Jsoup](https://github.com/jhy/jsoup)    | 一个以最好的DOM，CSS和jQuery解析html的库             |

##**数据库**

| 框架名称                                     | 功能描述                                     |
|:---------------------------------------- |:---------------------------------------- |
| [OrmLite](https://sourceforge.net/projects/ormlite/files/releases/com/j256/ormlite/) | JDBC和Android的轻量级ORM java包                |
| [Sugar](https://github.com/satyan/sugar) | 用超级简单的方法处理Android数据库                     |
| [GreenDAO](https://github.com/greenrobot/greenDAO) | 一种轻快地将对象映射到SQLite数据库的ORM解决方案，使用的App有：薄荷，京东 |
| [ActiveAndroid](https://github.com/pardom/ActiveAndroid) | 以活动记录方式为Android SQLite提供持久化              |
| [SQLBrite](https://github.com/square/sqlbrite) | SQLiteOpenHelper 和ContentResolver的轻量级包装  |
| [Realm](https://github.com/jhy/jsoup)    | 移动数据库：一个SQLite和ORM的替换品                   |
| [android-database-sqlcipher](https://github.com/sqlcipher/android-database-sqlcipher) | 数据库加密                                    |
| [storio](https://github.com/pushtorefresh/storio) | Beautiful API for SQLiteDatabase and ContentResolver |
| [realm-java](https://github.com/realm/realm-java) | 高性能数据库，Realm is a mobile database: a replacement for SQLite & ORMs |

##**依赖注入**

| 框架名称                                     | 功能描述                                   |
|:---------------------------------------- |:-------------------------------------- |
| [ButterKnife](https://github.com/JakeWharton/butterknife) | 将Android视图和回调方法绑定到字段和方法上|
| [Dagger2](https://github.com/google/dagger) | 一个Android和java快速依赖注射器                  |
| [AndroidAnotations](https://github.com/androidannotations/androidannotations) | 快速安卓开发。易于维护                            |
| [RoboGuice](https://github.com/roboguice/roboguice) | Android平台的Google Guice                 |
##**图表Chart**

| 框架名称                                     | 功能描述                              |
|:---------------------------------------- |:--------------------------------- |
| [WilliamChart](https://github.com/diogobernardino/WilliamChart) | 创建图表的Android库                     |
| [HelloCharts](https://github.com/lecho/hellocharts-android) | 兼容到API8的Android图表库，使用的App有：薄荷     |
| [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) | 一个强大的Android图表视图/图形库，使用的App有：春雨医生 |
##**9、后台处理**

| 框架名称                                     | 功能描述                    |
|:---------------------------------------- |:----------------------- |
| [Tape](https://github.com/square/tape)   | 一个轻快的，事务性的，基于文件的FIFO的库  |
| [Android Priority Job Queue](https://github.com/yigit/android-priority-jobqueue) | 一个专门为Android轻松调度任务的工作队列 |
##**10、事件总线**

| 框架名称                                     | 功能描述                                     |
|:---------------------------------------- |:---------------------------------------- |
| [EventBus](https://github.com/greenrobot/EventBus) | 安卓优化的事件总线，简化了活动、片段、线程、服务等的通信，使用的App有：薄荷  |
| [Otto](https://github.com/square/otto)   | 一个基于Guava的增强的事件总线                        |
| [HermesEventBus](https://github.com/eleme/HermesEventBus) | 一个基于EventBus的、能在进程间发送和接收event的库，在IPC或者插件开发中非常有用 |
##**11、响应式编程**

| 框架名称                                     | 功能描述                                    |
|:---------------------------------------- |:--------------------------------------- |
| [RxJava](https://github.com/ReactiveX/RxJava) | JVM上的响应式扩展                              |
| [RxJavaJoins](https://github.com/ReactiveX/RxJavaJoins) | 为RxJava提供Joins操作                        |
| [RxAndroid](https://github.com/ReactiveX/RxAndroid) | Android上的响应式扩展，在RxJava基础上添加了Android线程调度 |
| [RxBinding](https://github.com/JakeWharton/RxBinding) | 提供用RxJava绑定Android UI的API               |
| [Agera](https://github.com/google/agera) | Android上的响应式编程                     |
|[RxLifecycle](https://github.com/trello/RxLifecycle)|Lifecycle handling APIs for Android apps using RxJava|


##**Log框架**

| 框架名称                                     | 功能描述                 |
|:---------------------------------------- |:-------------------- |
| [Logger](https://github.com/orhanobut/logger) | 简单，漂亮，强大的Android日志工具 |
| [Hugo](https://github.com/JakeWharton/hugo) | 在调试版本上注解的触发方法进行日志记录  |
| [Timber](https://github.com/JakeWharton/timber) | 一个小的，可扩展的日志工具        |
##**测试框架**

| 框架名称                                     | 功能描述                 |
|:---------------------------------------- |:-------------------- |
| [Mockito](https://github.com/mockito/mockito) | Java编写的Mocking单元测试框架 |
| [Robotium](https://github.com/RobotiumTech/robotium) | Android UI 测试        |
| [Robolectric](https://github.com/robolectric/robolectric) | Android单元测试框架        |
<br>
Android自带很多测试工具：JUnit，Monkeyrunner，UiAutomator，Espresso等

##**调试框架**

| 框架名称                                     | 功能描述                                 |
|:---------------------------------------- |:------------------------------------ |
| [Stetho](https://github.com/facebook/stetho) | 调试Android应用的桥梁，使得可以利用Chrome开发者工具进行调试 |
##**性能优化**

| 框架名称                                     | 功能描述            |
|:---------------------------------------- |:--------------- |
| [LeakCanary](https://github.com/square/leakcanary) | 内存泄漏检测工具        |
|[BlockCanary](http://blog.zhaiyifan.cn/2016/01/16/BlockCanaryTransparentPerformanceMonitor/?utm_source=tuicool&utm_medium=referral)|轻松找出Android App界面卡顿元凶|
| [ACRA](https://github.com/ACRA/acra)     | Android应用程序崩溃报告 |

##**热修复**
| 框架名称                                     | 功能描述         |
|:---------------------------------------- |:------------ |
| [tinker](https://github.com/Tencent/tinker) | 腾讯开源的一个热修复框架 |
| [AndFix](https://github.com/alibaba/AndFix) | alibaba热修复框架 |
| [dexposed](https://github.com/alibaba/dexposed) | alibaba热修复框架 |

##**二维码**
| 框架名称                                     | 功能描述                                     |
|:---------------------------------------- |:---------------------------------------- |
| [Zxing](https://github.com/zxing/zxing)  | 一个二维码开源框架                                |
| [barcodescanner](https://github.com/dm77/barcodescanner) | 使用的App有：薄荷                               |
| [BGAQRCode-Android](https://github.com/bingoogolapple/BGAQRCode-Android) | 扫描二维码、扫描条形码、相册获取图片后识别、生成带 Logo 二维码、支持微博微信 QQ 二维码扫描样式 |
| [zxing-android-embedded](https://github.com/journeyapps/zxing-android-embedded/tree/master/zxing-android-embedded/src/com/journeyapps/barcodescanner) | 使用的App有：春雨医生，芒果TV                        |


##**多媒体**
| 框架名称                                     | 功能描述                             |
|:---------------------------------------- |:-------------------------------- |
| [ijkplayer](https://github.com/Bilibili/ijkplayer) | Bilibili开源的视频播放器                 |
| [DanmakuFlameMaster ](https://github.com/Bilibili/DanmakuFlameMaster) | Android开源弹幕引擎·烈焰弹幕使，使用的App有：网易新闻 |
| [Vitamio](https://github.com/yixia/VitamioBundle) | 一款全能多媒体开发框架，全面支持硬件解码与 GPU 渲染     |
| [FFmpeg](https://github.com/FFmpeg/FFmpeg) | 一个基于C语言的多媒体开源框架                  |
| 百度媒体云                                    | 基于百度视频处理、人脸识别、语音等技术媒体相关的整体解决方案   |
| [ExoPlayer](https://github.com/google/ExoPlayer) | Google开源的视频播放器                   |

# Android开源项目

# 阿里巴巴
|项目名称|功能描述|
|:---|:---|
|[freeline](https://github.com/alibaba/freeline)|Freeline 是 Android 平台上的秒级编译方案，Instant Run 的替代品，也可以从 Freeline 官方主页来获取更多的信息。Freeline 由蚂蚁聚宝 Android 团队开发，它可以充分利用缓存文件，在几秒钟内迅速地对代码的改动进行编译并部署到设备上，有效地减少了日常开发中的大量重新编译与安装的耗时。Freeline能够为Android开发者节省很多喝杯咖啡的时间|
|[weex](https://github.com/alibaba/weex)|A framework for building Mobile cross-platform UI|
|[fastjson](https://github.com/alibaba/fastjson)|A fast JSON parser/generator for Java|
|[Dubbo](https://github.com/alibaba/dubbo)|Dubbo is a distributed, high performance RPC framework enpowering applications with service import/export capabilities|
|[AndFix](https://github.com/alibaba/AndFix)|AndFix is a library that offer hot-fix for Android App.|
|[dexposed](https://github.com/alibaba/dexposed)|dexposed enable 'god' mode for single android application.|

#小米开源项目
|项目名称|功能描述|
|:---|:---|
| [Notes](https://github.com/MiCode/Notes)|小米便签社区开源版|
|[FileExplorer](https://github.com/MiCode/FileExplorer)|MIUI文件管理器社区开源版|
|[SoundRecorder](https://github.com/MiCode/SoundRecorder)|MIUI录音机社区开源版|

#Google开源项目
|项目名称|功能描述|
|:---|:---|
|[GCM](https://github.com/google/gcm)|Google Cloud Messaging 消息推送|
|[ iosched：](https://github.com/google/iosched)|Google I/O Android App|
|[android-topeka](https://github.com/googlesamples/android-topeka)|Google官方给出的material design应用指南|
|[android-UniversalMusicPlayer](https://github.com/googlesamples/android-UniversalMusicPlayer)|Google官方给出的m音乐播放器，支持Android phones, tablets, Auto, Wear and Cast devices|
|[ExoPlayer](https://github.com/google/ExoPlayer)|An extensible media player for Android|
|[guava](https://github.com/google/guava)|Google Core Libraries for Java 6+|
|[flexbox-layout](https://github.com/google/flexbox-layout)|FlexboxLayout is a library project which brings the similar capabilities of CSS Flexible Box Layout Module to Android.|
|[guice](https://github.com/google/guice)|轻量级的依赖注入框架|
|[gson](https://github.com/google/gson)|A Java serialization/deserialization library that can convert Java Objects into JSON and back.|
|[protobuf](https://github.com/google/protobuf)|Protocol Buffers - Google's data interchange format|
|[material-design-icons](https://github.com/google/material-design-icons)|Material Design icons by Google|
|[auto](https://github.com/google/auto)|Auto 是 Java 生成器源代码集合，包括：AutoFactory - 兼容 JSR-330 的工厂；AutoService - ServiceLoader 的 Provider-configuration 文件；AutoValue - Java 1.6+ 的不可变 value-type 代码生成；Common - Helper 实用工具，用来编写注释处理器|
|[android-architecture](https://github.com/googlesamples/android-architecture)|A collection of samples to discuss and showcase different architectural tools and patterns for Android apps|


##[android-topeka](https://github.com/googlesamples/android-topeka)

<img src="https://github.com/googlesamples/android-topeka/raw/master/screenshots/categories.png" width="200"> <img src="https://github.com/googlesamples/android-topeka/raw/master/screenshots/category_history.png" width="200"> <img src="https://github.com/googlesamples/android-topeka/raw/master/screenshots/quiz_shakespeare.png" width="200">

##[android-UniversalMusicPlayer](https://github.com/googlesamples/android-UniversalMusicPlayer)

<img src="https://github.com/googlesamples/android-UniversalMusicPlayer/raw/master/screenshots/phone.png" width="200"> <img src="https://github.com/googlesamples/android-UniversalMusicPlayer/raw/master/screenshots/phone_lockscreen.png" width="200"> <img src="https://github.com/googlesamples/android-UniversalMusicPlayer/raw/master/screenshots/phone_fullscreen_player.png" width="200"> 

##[ExoPlayer](https://github.com/google/ExoPlayer)

An extensible media player for Android

[Streaming media with ExoPlayer - Google I/O 2016](http://v.youku.com/v_show/id_XMTU4MzA5NjA0NA==.html?f=27314446)

##[guava](https://github.com/google/guava)

##[flexbox-layout](https://github.com/google/flexbox-layout)

<img src="https://github.com/google/flexbox-layout/raw/master/assets/flex-direction.gif" width="300">

--- 
## u2020
JakeWharton写的一个App,针对多个库的综合应用：Dagger、ButterKnife、Retrofit、Moshi、Picasso、OkHttp、RxJava、Timber、Madge、ProcessPhoenix、Scalpel、LeakCanary

![](https://github.com/JakeWharton/u2020/raw/master/u2020.gif)

AntennaPod Rss订阅 乐音订阅 - https://github.com/danieloeh/AntennaPod
Muzei Live Wallpaper 定时更换桌面精美壁纸 - https://github.com/romannurik/muzei
Financius 简单易用的记账程序 - https://github.com/mvarnagiris/Financius
ChaseWhisplyProject 打鬼游戏 - https://github.com/tvbarthel/ChaseWhisplyProject
ZXing 二维码扫描工具 - https://github.com/zxing/zxing
Anime Taste 全球动画精选- https://github.com/daimajia/AnimeTaste

Notes 小米便签 - https://github.com/MiCode/Notes
四次元 - https://github.com/qii/weiciyuan
oschina oschina客户端 - https://github.com/oschina/android-app
eoecn eoe客户端 - https://github.com/eoecn/android-app
github 客户端 - https://github.com/github/android
饭否开源客户端 - https://github.com/mcxiaoke/fanfouapp-opensource
9GAG stormzhang Android REST Client - https://github.com/stormzhang/9GAG
Dribbo 碎星大神 - https://github.com/Issacw0ng/Dribbo
StartupNews - https://github.com/halzhang/StartupNews

##[GitHub 上都有哪些值得关注学习的 Android项目？](https://www.zhihu.com/question/23804819)

##[android-best-practices](https://github.com/futurice/android-best-practices)

##[Andriod-collect-blogs](https://github.com/ZQiang94/Andriod-collect-blogs)

##[GitHub秘籍](https://github.com/tiimgreen/github-cheat-sheet/blob/master/README.zh-cn.md)

##[《编程之法：面试和算法心得》](https://github.com/julycoding/The-Art-Of-Programming-By-July)

##[AndroidSlidingUpPanel](https://github.com/umano/AndroidSlidingUpPanel)

AndroidSlidingUpPanel 是一个上拉面板, 就是向上滑动的时候往上飞出一个显示面板控件, 该库效果在 Google Music, Google Maps and Rdio等 App 中用到。

![](https://camo.githubusercontent.com/834cfd81ce764457db69dc023e1bd0adf0a8d00d/68747470733a2f2f7261772e6769746875622e636f6d2f756d616e6f2f416e64726f6964536c6964696e67557050616e656c44656d6f2f6d61737465722f736c6964696e67757070616e656c2e706e67)

##[EffectiveAndroidUI](https://github.com/pedrovgs/EffectiveAndroidUI)

## [四季电台](https://github.com/linroid/Sky31Radio)

<img src="https://github.com/linroid/Sky31Radio/raw/master/screenshots/device-2015-01-22-224854.png" width="300"/> <img src="https://github.com/linroid/Sky31Radio/raw/master/screenshots/device-2015-01-22-224820.png" width="300"/> <img src="https://github.com/linroid/Sky31Radio/raw/master/screenshots/device-2015-02-07-141957.png" width="300"/>


