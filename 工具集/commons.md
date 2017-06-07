## 工具集

| 工具集                                      | 功能描述                                     |
| ---------------------------------------- | ---------------------------------------- |
| [AndroidUtilCode](https://github.com/Blankj/AndroidUtilCode) | Android开发人员不得不收集的代码                      |
| [Apache Commons](http://commons.apache.org/) | 包含了很多开源的工具，用于解决平时编程经常会遇到的问题，减少重复劳动       |
| [Guava](https://github.com/google/guava) | Guava 中文是石榴的意思，该项目是 Google 的一个开源项目，包含许多 Google 核心的 Java 常用库。 |
| [android-common](https://github.com/Trinea/android-common) | **主要包括**：**缓存**(图片缓存、预取缓存、网络缓存)、**公共View**(下拉及底部加载更多ListView、底部加载更多ScrollView、滑动一页Gallery)及**Android常用工具类**(网络、下载、Android资源操作、shell、文件、Json、随机数、Collection等等)。 |
| [LiteCommon](https://github.com/litesuits/android-common) | LiteCommon是一系列通用类、辅助类、工具类的集合             |
| [AndroidCommon](https://github.com/h4de5ing/AndroidCommon) | 常用工具类                                    |
| [easypermissions](https://github.com/googlesamples/easypermissions) | Easypermissions简化了Android M的运行时权限的申请、结果处理、判断等步骤。 |
| [Genius-Android](https://github.com/qiujuer/Genius-Android/blob/master/README-ZH.md) | **Genius-Android** 是 **Android** 中一些常用的的方法集合, **Genius** 提供[6个基本板块](https://www.oschina.net/news/59597/genius-android-2-3-0) |
| [Zip4j](http://www.lingala.net/zip4j/)   | Java处理zip压缩文件的完整解决方案                     |
| [PrettyTime](https://github.com/ocpsoft/prettytime) | Java时间格式化开源类库，它能够将时间格式成易于用户阅读的格式，如"12分钟前"、"2天前"、"至今3个月"等。易于使用。完全可定制，可以创建属于自己TimeUnit和TimeFormat对象。能够与JSF框架集成使用。 |
| [Cal4j](https://github.com/ical4j/ical4j) | Cal4j用于读写iCalendar数据流的一组API。iCalendar标准提供了一种公共的数据格式用于存储关于日历方面的信息比如事件，约定，待办事项等。所有流行日历工具比如：Lotus Notes，Outlook和Apple的iCal都支持iCalendar标准。 |
| [Apache Tika](http://tika.apache.org/)   | Tika是一个内容分析工具，自带全面的parser工具类，能解析基本所有常见格式的文件，得到文件的metadata，content等内容，返回格式化信息。总的来说可以作为一个通用的解析工具。特别对于搜索引擎的数据抓去和处理步骤有重要意义。 |
| [gnu-crypto](http://www.gnu.org/software/gnu-crypto/) | 加密工具                                     |
| java-unrar                               | de.innosystec.unrar解压缩rar文件              |
| [android-priority-jobqueue](https://github.com/path/android-priority-jobqueue) | 一款专门为Android平台编写，实现了[Job Queue](http://en.wikipedia.org/wiki/Job_queue)的后台任务队列类库，能够轻松的在后台执行定时任务，提高用户体验和应用的稳定性。 |
| JOOR                                     | 利用JOOR简单编写java的反射                        |
| [JAudiotagger](http://www.jthink.net/jaudiotagger/) | 提供一个Java类库用于编辑音频文件的tag信息(如ID3)，是jid3lib的扩展，比jlid3lib强大更多，支持更多格式。 |
| [jChardet](http://jchardet.sourceforge.net/) | 自动字符集探测算法，jchardet是firefox使用的字节流编码检测算法 的java开源实现， 检测文本文件(字节流)的编码方式 |
| [mupdf](https://mupdf.com/index.html)    | MuPDF is a lightweight PDF, XPS, and E-book viewer. |

protobuf-javame，net.jarlehansen.protobuf.javame

[nanohttpd](https://github.com/NanoHttpd/nanohttpd) 一个免费、轻量级的(只有一个Java文件) HTTP服务器,可以很好地嵌入到Java程序中

Open Chinese Convert（OpenCC）是一个开源的中文简繁转换项目，致力于制作高质量的基于统计预料的简繁转换词库。还提供函数库(libopencc)、命令行简繁转换工具、人工校对工具、词典生成程序、在线转换服务及图形用户界面。

[jutf7](https://github.com/k9mail/jutf7)：Java UTF-7 Charset support (copy of [http://sourceforge.net/projects/jutf7/](http://sourceforge.net/projects/jutf7/))

## AndroidUtilCode

https://github.com/Blankj/AndroidUtilCode

Android开发人员不得不收集的代码

做这份整理是想把它作为Android开发的小字典，当遇到一些琐碎问题时，不用再面向百度或者谷歌查询API的使用，费时费力，这里有的话，大家尽管撸走；同时也希望它能逐日壮大起来，期待大家的Star和完善，当然我也会一直更新发布版本和日志，为了方便大家导入，现已上传jcenter；其中很多代码也是汇四方之精华，谢谢前辈们的提供，当然最终还是要通过单元测试的，如有错误，请及时告之。

## Guava

https://github.com/google/guava

Guava 中文是石榴的意思，该项目是 Google 的一个开源项目，包含许多 Google 核心的 Java 常用库。

目前主要包含：

- com.google.common.annotations
- com.google.common.base
- com.google.common.collect
- com.google.common.io
- com.google.common.net
- com.google.common.primitives
- com.google.common.util.concurrent

## Apache Commons

Apache Commons包含了很多开源的工具，用于解决平时编程经常会遇到的问题，减少重复劳动

| **组件**        | **功能介绍**                                 |
| :------------ | :--------------------------------------- |
| BeanUtils     | 提供了对于JavaBean进行各种操作，克隆对象,属性等等.           |
| Betwixt       | XML与Java对象之间相互转换.                        |
| Codec         | 处理常用的编码方法的工具类包 例如DES、SHA1、MD5、Base64等.   |
| Collections   | java集合框架操作.                              |
| Compress      | java提供文件打包 压缩类库.                         |
| Configuration | 一个java应用程序的配置管理类库.                       |
| DBCP          | 提供数据库连接池服务.                              |
| DbUtils       | 提供对jdbc 的操作封装来简化数据查询和记录读取操作.             |
| Email         | java发送邮件 对javamail的封装.                   |
| FileUpload    | 提供文件上传功能.                                |
| HttpClien     | 提供HTTP客户端与服务器的各种通讯操作. 现在已改成HttpComponents |
| IO            | io工具的封装.                                 |
| Lang          | Java基本对象方法的工具类包 如：StringUtils,ArrayUtils等等. |
| Logging       | 提供的是一个Java 的日志接口.                        |
| Validator     | 提供了客户端和服务器端的数据验证框架.                      |

##  android-common

https://github.com/Trinea/android-common

**主要包括**：**缓存**(图片缓存、预取缓存、网络缓存)、**公共View**(下拉及底部加载更多ListView、底部加载更多ScrollView、滑动一页Gallery)及**Android常用工具类**(网络、下载、Android资源操作、shell、文件、Json、随机数、Collection等等)。

## LiteCommon

LiteCommon是一系列通用类、辅助类、工具类的集合，有以下特点：

- **1. 通用性强**：只有常用、通用才集入。
- **2. 体积超小**：不到50K！加入增强IO包混淆后70K！
- **3. 纯 纯 纯**：类间独立，单挑大梁，极少耦合，就是单纯！

其中包括bitmap处理，文件操作，加密存储器，shell命令，静默安装，计数器，均值器，吐司，日志，校验，提示，网络监测等基础功能，以及一些Base64、MD5、Hex、Byte、Number、Dialog、Filed、Class、Package、Telephone、Random等工具类。

## JsBridge

[JsBridge](https://github.com/lzyzsd/JsBridge)

[safe-java-js-webview-bridge](https://github.com/pedant/safe-java-js-webview-bridge)

为WebView中的Java与JavaScript提供【安全可靠】的多样互通方案 

[BridgeWebView](https://github.com/open-android/BridgeWebView)

H5和Android通信框架，让H5和Android相互调用更加简单。

## 