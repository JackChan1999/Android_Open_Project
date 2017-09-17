## 响应式编程

| 框架名称                                     | 功能描述                                     |
| :--------------------------------------- | :--------------------------------------- |
| [RxJava](https://github.com/ReactiveX/RxJava) | JVM上的响应式扩展                               |
| [RxKotlin](https://github.com/ReactiveX/RxKotlin) | RxJava bindings for Kotlin               |
| [RxjavaUtils](https://github.com/open-android/RxjavaUtils) | Rxjava工具类，Rxjava快速封装实现的示例工程，包括变换的使用以及与Retrofit联用 |
| [RxJavaJoins](https://github.com/ReactiveX/RxJavaJoins) | 为RxJava提供Joins操作                         |
| [RxAndroid](https://github.com/ReactiveX/RxAndroid) | Android上的响应式扩展，在RxJava基础上添加了Android线程调度  |
| [RxBinding](https://github.com/JakeWharton/RxBinding) | 提供用RxJava绑定Android UI的API                |
| [Agera](https://github.com/google/agera) | Android上的响应式编程                           |
| [RxLifecycle](https://github.com/trello/RxLifecycle) | Lifecycle handling APIs for Android apps using RxJava |
| [Bolts-Android](https://github.com/BoltsFramework/Bolts-Android) | bolts类似RxJava，其中的Task相当于Observable\Subscriber，但是比RxJava轻便好用 |

## RxLifecycle
https://github.com/trello/RxLifecycle

## [Bolts-Android](https://github.com/BoltsFramework/Bolts-Android)

对Android客户端编程来说，有个明确的规则是不能在ui线程里面做耗时的操作。这样就要求网络请求、文件读写等等操作都要异步操作。而异步操作完成后，往往需要再更新ui界面。最直接的想法是回调，只要保证在ui线程里面，更新ui组件不会困难。但有些情况下，往往需要多层异步操作，这时候代码就很丑了，不管是维护，还是编写都是挑战。

Javascript 有Promise处理异步操作，程序逻辑扁平化，非常有利于扩展和组合。对于Android也有类似的解决方案，就是Bolts-Android。iOS也有相应的版本：Bolts-iOS。

Bolts 是Parse 开源的框架，Parse 前端时间被Facebook收购，是个云平台服务提供商。

Bolts 提供了一种对任务的封装，将所有的操作抽象为Task, 只包含两种结果，出错 & 成功。并提供了一系列接口，方便开发者使用。

RxJava, 也是一种扁平化的编程方式，对异步处理也很有方便，但包很大，整个编程思想也与原有模式有很大的不同。Bolts 很轻量，有作用的类也就Task一个，代码也不多

bolts是Parse被FaceBook收购后开源的一个工具库组合，

Parse声称，与[Android AsyncTask](https://github.com/BoltsFramework/Bolts-Android)和[iOS NSOperation](https://github.com/BoltsFramework/Bolts-iOS)相比，Tasks有若干优势，其中包括：

- 连续执行数个任务不会像只使用回调函数时那样创建嵌套的“金字塔（pyramid）”代码。
- Tasks是完全可组合的，允许开发人员执行分支、并行和复杂的错误处理。
- 开发人员可以按照执行顺序安排基于任务的代码，而不必将逻辑分解到分散的回调函数中。

简单的来说，bolts类似RxJava，其中的Task相当于Observable\Subscriber，但是比RxJava轻便好用，如果不考虑Retrofit网络库支持的话，我更倾向于使用Task。

Task可以无限链接，感觉就像是你在使用链式编程。