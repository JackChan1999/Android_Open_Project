## **性能优化**

| 框架名称                                     | 功能描述                  |
| :--------------------------------------- | :-------------------- |
| [LeakCanary](https://github.com/square/leakcanary) | 内存泄漏检测工具              |
| [BlockCanary](http://blog.zhaiyifan.cn/2016/01/16/BlockCanaryTransparentPerformanceMonitor/?utm_source=tuicool&utm_medium=referral) | 轻松找出Android App界面卡顿元凶 |
| [ACRA](https://github.com/ACRA/acra)     | Android应用程序崩溃报告       |
| [battery-historian](https://github.com/google/battery-historian) | 电量分析                  |

## [Google Guava](https://github.com/google/guava)

Guava工程包含了若干被Google的 Java项目广泛依赖 的核心库，例如：集合 [collections] 、缓存 [caching] 、原生类型支持 [primitives support] 、并发库 [concurrency libraries] 、通用注解 [common annotations] 、字符串处理 [string processing] 、I/O 等等。 所有这些工具每天都在被Google的工程师应用在产品服务中。

## google protobuf

由google开发，并且在google内部使用。Protobuf的作用和xml、json是一回事，但他是二进制格式，性能好、效率高。

[ProtoBuf开发者指南](http://www.cppblog.com/woaidongmao/archive/2009/06/23/88391.html)

## BlockCanary
BlockCanary — 轻松找出Android App界面卡顿元凶

http://blog.zhaiyifan.cn/2016/01/16/BlockCanaryTransparentPerformanceMonitor/?utm_source=tuicool&utm_medium=referral

使用的App有：薄荷

## Netty

Netty是一个高性能、异步事件驱动的NIO框架,它提供了对TCP、UDP和文件传输的支持,作为一个异步NIO框架,Netty的所有IO操作都是异步非阻塞的

## GNU Trove
Trove 是一个快速、轻量级 Collection 类的集合。Trove 提供所有标准 java.util Collections 类的更快的版本以及能够直接在原语（primitive）（例如包含 int 键或值的 Map 等）上操作的 Collections 类的版本。使用的App有：网易新闻

## org.eclipse.mat
内存分析。使用的App有薄荷，网易新闻

## [**msgpack**](http://msgpack.org/)

MessagePack是一个基于二进制高效的对象序列化Library用于跨语言通信。
它可以像JSON那样，在许多种语言之间交换结构对象；但是它比JSON更快速也更轻巧。 比Google Protocol Buffers还要快4倍

https://github.com/msgpack/msgpack-java
