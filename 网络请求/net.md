## **网络请求**

| 框架名称                                     | 功能描述                                     |
| :--------------------------------------- | :--------------------------------------- |
| httpclient                               | apache开源的网络请求框架，已过时，android6.0后删除        |
| AsyncHttpClient                          | 基于httpclient封装，已过时                       |
| [OkHttp](https://github.com/square/okhttp) | Square出品，一个Http与Http/2的客户端               |
| [Retrofit](https://github.com/square/retrofit) | Square出品，类型安全的Http客户端                    |
| [Volley](https://android.googlesource.com/platform/frameworks/volley) | Google推出的Android异步网络请求框架和图片加载框架，使用的App有：网易新闻 |
| HttpURLConnection                        | android原生api，省电省流量                       |
| [NoHttp](https://github.com/yanzhenjie/NoHttp) | Android实现Http标准协议框架，支持缓存（提供五种缓存模式）、代理、重定向，底层可动态切换OkHttp、URLConnection，与RxJava完美结合，比Retrofit更简单易用。 |
| [okhttputils](https://github.com/hongyangAndroid/okhttputils) | okhttp的辅助类                               |
| Mina                                     | Apache Mina是一个能够帮助用户开发高性能和高伸缩性网络应用程序的框架。它通过Java nio技术基于TCP/IP和UDP/IP协议提供了抽象的、事件驱动的、异步的API。 |
| mars                                     | Mars 是微信官方的跨平台跨业务的终端基础组件。                |
| Openfire                                 | Openfire 是实时的基于WEB的即时消息传输平台              |
|                                          |                                          |
|                                          |                                          |
|                                          |                                          |

从Android 6.0 开始，Google删除了apache的开源网络请求框架httpclient，所以基于httpclient的AsyncHttpClient也不推荐使用了

Volley适合那些请求频繁但数据量不大的场景，不适用于大数据的请求，比如下载文件

Android 6.0 后，Android开始使用OkHttp，而Retrofit是一个网络代理框架，可以更简单的使用OkHttp

NoHttp使用：http://blog.csdn.net/column/details/nohttp.html

## **网络解析**

| 框架名称                                     | 功能描述                                     |
| :--------------------------------------- | :--------------------------------------- |
| [Gson](https://github.com/google/gson)   | 一个Java序列化/反序列化库，可以将JSON和java对象互相转换       |
| [Jackson](https://github.com/codehaus/jackson) | Jackson可以轻松地将Java对象转换成json对象和xml文档，同样也可以将json、xml转换成Java对象 |
| [Fastjson](https://github.com/alibaba/fastjson) | Java上一个快速的JSON解析器/生成器                    |
| [HtmlPaser](https://sourceforge.net/projects/htmlparser/) | 一种用来解析单个独立html或嵌套html的方式                 |
| [Jsoup](https://github.com/jhy/jsoup)    | 一个以最好的DOM，CSS和jQuery解析html的库             |

## Java-WebSocket

简单的说，websocket就是用来做网页聊天以及手机推送用的。使用的App有薄荷

## 多线程下载

[MultiThreadDownload](https://github.com/Aspsine/MultiThreadDownload) 使用的App有：薄荷

[FileDownloader](https://github.com/lingochamp/FileDownloader)

## nanohttpd

https://github.com/NanoHttpd/nanohttpd

嵌入式HTTP服务器 ，NanoHTTPD是一个免费、轻量级的(只有一个Java文件) HTTP服务器,可以很好地嵌入到Java程序中。支持 GET, POST, PUT, HEAD 和 DELETE 请求，支持文件上传，占用内存很小。可轻松定制临时文件使用和线程模型。

## Mina

Mina是用于开发高性能和高可用性的网络应用程序的基础框架。通过使用MINA框架可以可以省下处理底层I/O和线程并发等复杂工作，开发人员能够把更多的精力投入到业务设计和开发当中

Apache Mina Server 是一个网络通信应用框架，也就是说，它主要是对基于TCP/IP、UDP/IP协议栈的通信框架（当然，也可以提供JAVA 对象的序列化服务、虚拟机管道通信服务等），Mina 可以帮助我们快速开发高性能、高扩展性的网络通信应用，Mina 提供了事件驱动、异步（Mina 的异步IO 默认使用的是JAVA NIO 作为底层支持）操作的编程模型。Mina 主要有1.x 和2.x 两个分支，这里我们讲解最新版本2.0，如果你使用的是Mina 1.x，那么可能会有一些功能并不适用。学习本文档，需要你已掌握JAVA IO、JAVA NIO、JAVASocket、JAVA 线程及并发库(java.util.concurrent.*)的知识。Mina 同时提供了网络通信的Server 端、Client 端的封装，无论是哪端，Mina 在整个网通通信结构中都处于如下的位置：可见Mina 的API 将真正的网络通信与我们的应用程序隔离开来，你只需要关心你要发送、接收的数据以及你的业务逻辑即可

## openfire

是开源的、基于可拓展通讯和表示协议(XMPP)、采用Java编程语言开发的实时协作服务器。 Openfire安装和使用都非常简单，并利用Web进行管理。单台服务器可支持上万并发用户。您可以使用它轻易的构建高效率的[即时通信](http://baike.baidu.com/item/%E5%8D%B3%E6%97%B6%E9%80%9A%E4%BF%A1)服务器.

## Mars 

Mars 是微信官方的终端基础组件，是一个使用 C++ 编写的业务性无关、平台性无关的基础组件。目前已接入微信 Android、iOS、Mac、Windows、WP 等客户端。