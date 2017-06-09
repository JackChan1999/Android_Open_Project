## 关于RecyclerView的那些开源LayoutManager

> 原文链接：http://www.jianshu.com/p/cf3a4a9b3698

Google默认为RecyclerView提供了LinearLayoutManager、StaggeredGridLayoutManager、GridLayoutManager，已经可以满足很多开发需求了，但是实际开发过程中，免不了出现一些更加新颖的交互设计。于是，便从Github上整理了一波关于RecyclerView可以使用的LayoutManager，在实际开发中需要用到时，遇到相似的效果时即可随手拈来，提高效率。

## FanLayoutManager

> [https://github.com/Cleveroad/FanLayoutManager](https://github.com/Cleveroad/FanLayoutManager)

来自国外一家名为Cleveroad的科技公司的开源作品，因其效果就像风扇扇叶旋转一样，所以名中带Fan。效果不错，API上也有很多的配置参数，用起来还是挺灵活的。

![img](https://diycode.b0.upaiyun.com/photo/2017/b900c72687b8410b9181cac5ec33354c.gif)

## CarouselLayoutManager

> [https://github.com/Azoft/CarouselLayoutManager](https://github.com/Azoft/CarouselLayoutManager)

让你的RecyclerView秀出传送带效果，支持横向和纵向两种选择。

![img](https://diycode.b0.upaiyun.com/photo/2017/d936b099402d557a35ddbbdc3eee44f2.gif)

## ChipsLayoutManager

> [https://github.com/BelooS/ChipsLayoutManager](https://github.com/BelooS/ChipsLayoutManager)

一种流式布局的效果，很像我们平时看到的标签云。该库同样提供了很多可配置效果的API，并且支持多种多花效果。

![img](https://diycode.b0.upaiyun.com/photo/2017/64096b0169de6ee48172c9513f05d7fd.gif)

## HiveLayoutManager

> [https://github.com/Chacojack/HiveLayoutManager](https://github.com/Chacojack/HiveLayoutManager)

国人写的一个蜂巢布局管理器，除了外观帅气外，其增删查改的动画效果也是很赞的。

![img](https://diycode.b0.upaiyun.com/photo/2017/7dbaaeb6ba1dcccf77d969bc925531c5.gif)

## vlayout

> [https://github.com/alibaba/vlayout](https://github.com/alibaba/vlayout)

vlayout 是手机天猫 Android 版内广泛使用的一个基础 UI 框架项目，提供了一个用于 RecyclerView 的自定义的 LayoutManger，可以实现不同布局格式的混排，目标是支撑客户端 native 页面的快速开发，它也是 Tangram 框架的基础模块。

![img](https://diycode.b0.upaiyun.com/photo/2017/d8350faebc5d37475360d7a1797a9653.gif)

## flexbox-layout

> [https://github.com/google/flexbox-layout](https://github.com/google/flexbox-layout)

flexbox-layout是Google开源的布局，其效果是实现类似CSS中的Flexbox布局效果（ 具体可看：[https://www.w3cplus.com/css3/a-guide-to-flexbox-new.html](https://www.w3cplus.com/css3/a-guide-to-flexbox-new.html) ），原本并不支持RecyclerView，但其最新的Alpha版本已经开始推出FlexboxLayoutManager用于支持RecyclerView实现效果。

![img](https://diycode.b0.upaiyun.com/photo/2017/28c862e9e31e6dbe25442a4002ed3816.gif)

![img](https://diycode.b0.upaiyun.com/photo/2017/87ca3159a60c8f16588f5b5ce4654eb8.gif)

## LondonEyeLayoutManager

> [https://github.com/danylovolokh/LondonEyeLayoutManager](https://github.com/danylovolokh/LondonEyeLayoutManager)

一个环形菜单的布局管理器，以前在建行的Android客户端就见过此效果，不过那时候是用ViewGroup实现的。

![img](https://diycode.b0.upaiyun.com/photo/2017/b8de9aefbfeef8a60677dcf72134dec2.gif)

## 总结

好了，大致就推荐以上这些开源布局管理器，如果你也有好推荐但文中没有提到，欢迎给我留言。偶尔搜集推荐一些不错的开源项目，如果你觉得文章不错，欢迎点赞和转发，关注本公众号可以了解更多技术知识。

- **我的个人博客：http://blog.coderclock.com/**
- **我的知乎专栏：https://zhuanlan.zhihu.com/coderclock**
- **我的Diycode：https://www.diycode.cc/d_clock**
- **我的新浪微博：D_clock爱吃葱花**
- **我的微信公众号：技术视界**