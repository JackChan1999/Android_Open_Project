## **网络请求**

| 框架名称                                     | 功能描述                                     |
| :--------------------------------------- | :--------------------------------------- |
| httpclient                               | apache开源的网络请求框架，已过时                      |
| AsyncHttpClient                          | 基于httpclient封装，已过时                       |
| [OkHttp](https://github.com/square/okhttp) | Square出品，一个Http与Http/2的客户端               |
| [Retrofit](https://github.com/square/retrofit) | Square出品，类型安全的Http客户端                    |
| [Volley](https://android.googlesource.com/platform/frameworks/volley) | Google推出的Android异步网络请求框架和图片加载框架，使用的App有：网易新闻 |

从Android 6.0 开始，Google删除了apache的开源网络请求框架httpclient，所以基于httpclient的AsyncHttpClient也不推荐使用了

Volley适合那些请求频繁但数据量不大的场景，不适用于大数据的请求，比如下载文件

Android 6.0 后，Android开始使用OkHttp，而Retrofit是一个网络代理框架，可以更简单的使用OkHttp

## **网络解析**

| 框架名称                                     | 功能描述                                     |
| :--------------------------------------- | :--------------------------------------- |
| [Gson](https://github.com/google/gson)   | 一个Java序列化/反序列化库，可以将JSON和java对象互相转换       |
| [Jackson](https://github.com/codehaus/jackson) | Jackson可以轻松地将Java对象转换成json对象和xml文档，同样也可以将json、xml转换成Java对象 |
| [Fastjson](https://github.com/alibaba/fastjson) | Java上一个快速的JSON解析器/生成器                    |
| [HtmlPaser](https://sourceforge.net/projects/htmlparser/) | 一种用来解析单个独立html或嵌套html的方式                 |
| [Jsoup](https://github.com/jhy/jsoup)    | 一个以最好的DOM，CSS和jQuery解析html的库             |