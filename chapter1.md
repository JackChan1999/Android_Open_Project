# **1、图片加载，缓存，处理**
| 框架名称  | 功能描述 |
|:---------------------------------------- |:------------------------ |
| [Android Universal Image Loader](https://github.com/nostra13/Android-Universal-Image-Loader) | 一个强大的加载，缓存，展示图片的库，<font color="red" ><b>已过时</b></font>|
| [Picasso](https://github.com/square/picasso) | 一个强大的图片下载与缓存的库           |
| [Fresco](https://github.com/facebook/fresco) | 一个用于管理图像和他们使用的内存的库       |
| [Glide](https://github.com/bumptech/glide) | 一个图片加载和缓存的库，使用的App有：网易新闻 |
|[GlidePalette](https://github.com/florent37/GlidePalette)|Android Lollipop Palette is now easy to use with Glide|
|[PicassoPalette](https://github.com/florent37/PicassoPalette)|Android Lollipop Palette is now easy to use with Picasso !|
| [Picasso-transformations](https://github.com/wasabeef/picasso-transformations) | 一个为Picasso提供多种图片变换的库|
| [Glide-transformations](https://github.com/wasabeef/glide-transformations) | 一个为Glide提供多种图片变换的库|
<br>
Picasso是著名的开源组织Square出品的图片处理框架，使用的比较多

Glide是Google的员工基于Picasso开发，优化的，Android官网推荐使用的图片处理框架

Fresco是Facebook开源的图片处理框架，真正做到了三级缓存，功能强大，强烈推荐使用

Android Universal Image Loader是一个老牌的图片处理框架，但是在2015年的9月份已经停止更新维护，所以不推荐使用

# **2、图片裁剪**
| 框架名称                                     | 功能描述                                     |
|:---------------------------------------- |:---------------------------------------- |
|[uCrop](https://github.com/Yalantis/uCrop) | [Image Cropping Library for Android](https://yalantis.com/blog/introducing-ucrop-our-own-image-cropping-library-for-android/)，使用的App有：薄荷，哔哩哔哩 |
|[android-crop](https://github.com/jdamcd/android-crop) | 图片裁剪，使用的App有：网易新闻，芒果TV  |
|[cropper](https://github.com/edmodo/cropper) | 图片裁剪开源框架   |
|[Android-Image-Cropper](https://github.com/ArthurHub/Android-Image-Cropper)|Image Cropping Library for Android, optimized for Camera / Gallery|
|[PhotoCropper](https://github.com/ryanhoo/PhotoCropper)|Android 大图片裁剪终极解决方案|
|[android-cropimage](https://github.com/lvillani/android-cropimage)|CropImage Activity from Gallery.apk packaged as a reusable Android library |
|[PhotoCrop](https://github.com/albinmathew/PhotoCrop)|A Library which can be used to crop images in Android similar to Facebook and Telegram，使用的App有：快手|


## uCrop

![](https://github.com/Yalantis/uCrop/raw/master/preview.gif)

## android-crop

![](https://github.com/jdamcd/android-crop/raw/master/screenshot.png)

## Android-Image-Cropper

![](https://github.com/ArthurHub/Android-Image-Cropper/raw/master/art/demo.gif?raw=true)

## PhotoCropper

![](https://github.com/ryanhoo/PhotoCropper/raw/master/images/photo-cropper-demonstration.gif)

## PhotoCrop

![](https://raw.githubusercontent.com/albinmathew/PhotoCrop/master/screenshots/pic1.png)



# **3、图片选择**
| 框架名称  | 功能描述    |
|:--------------- |:---------------- |
| [MultiImageSelector](https://github.com/lovetuzitong/MultiImageSelector) | 图片选择，使用的App有：薄荷|
| [BGAPhotoPicker-Android](https://github.com/bingoogolapple/BGAPhotoPicker-Android) | Android 图片选择、预览、九宫格图片控件、拖拽排序九宫格图片控件      |
| [TakePhoto](https://github.com/crazycodeboy/TakePhoto) | 轻量级Android照片处理框架  |
|[RxGalleryFinal](https://github.com/FinalTeam/RxGalleryFinal)|Android图片单选/多选、拍照、裁剪、压缩。视频选择和录制。[GalleryFinal](https://github.com/pengjianbo/GalleryFinal)|
|[boxing](https://github.com/Bilibili/boxing)|一个多媒体选择器库，B站出品。可以选择一张或者多张图片，提供预览和裁剪功能。同样支持gif图，选择视频和图像压缩功能。|

## boxing
<img src="https://github.com/Bilibili/boxing/raw/master/screenshot/multi_image.webp" width="300" /> <img src="https://github.com/Bilibili/boxing/raw/master/screenshot/single_image_crop.webp" width="300" /> <img src="https://github.com/Bilibili/boxing/raw/master/screenshot/video.webp" width="300" />

## MultiImageSelector

![](https://github.com/lovetuzitong/MultiImageSelector/raw/master/art/example_1.png) ![](https://github.com/lovetuzitong/MultiImageSelector/raw/master/art/select_1.png)

![](https://github.com/lovetuzitong/MultiImageSelector/raw/master/art/select_2.png) ![](https://github.com/lovetuzitong/MultiImageSelector/raw/master/art/select_3.png)

## BGAPhotoPicker-Android

![](https://cloud.githubusercontent.com/assets/8949716/17476407/7d54831e-5d92-11e6-83d0-4049039e0899.gif) ![](https://cloud.githubusercontent.com/assets/8949716/18590019/cde4acdc-7c5f-11e6-8877-b702aba7ae0c.png)

## TakePhoto
![预览图](https://raw.githubusercontent.com/crazycodeboy/TakePhoto/master/Screenshots/takephoto_preview.png)
![运行效果图](https://raw.githubusercontent.com/crazycodeboy/TakePhoto/master/Screenshots/%E9%A2%84%E8%A7%88%E5%9B%BE.jpg)

## RxGalleryFinal

![](https://github.com/pengjianbo/GalleryFinal/raw/master/images/gallery_final_effect.png)


# **4、图片转换，压缩，滤镜**
| 框架名称  | 功能描述    |
|:---------------------------------------- |:---------------------------------------- |
| [Android-gpuimage](https://github.com/CyberAgent/android-gpuimage) |一个开源的基于GPU的图像处理库，提供各种各样的图像处理滤镜，并且支持照相机和摄像机的实时滤镜，使用的App有：快手|
| [photoview](https://github.com/chrisbanes/PhotoView) | 使用的App有：薄荷,网易新闻 |
| [circleimageview](https://github.com/hdodenhof/CircleImageView) | 圆形图片，使用的App有：薄荷 |
| [RoundedImageView](https://github.com/vinc3m1/RoundedImageView) | 圆形图片，使用的App有：薄荷|
| [SelectableRoundedImageView](https://github.com/pungrue26/SelectableRoundedImageView) | Android ImageView that supports different radii on each corner |
| [android-gif-drawable](https://github.com/koral--/android-gif-drawable) | gif图片，使用的App有：网易新闻，快手|
|[Luban](https://github.com/Curzibn/Luban)|可能是最接近微信朋友圈的图片压缩算法|
|[Compressor](https://github.com/zetbaitsu/Compressor)|Compressor is a lightweight and powerful android image compression library|

## Android-gpuimage
![](http://dl2.iteye.com/upload/attachment/0093/2021/32e1bf04-8735-3c17-abac-c8bc267fede4.png) ![](http://dl2.iteye.com/upload/attachment/0093/2023/f7cd1809-f717-302a-bc60-0135264492aa.png)

![](http://dl2.iteye.com/upload/attachment/0093/2025/c6ade696-bfbb-3432-8fc9-375df8cfbfeb.png) ![](http://dl2.iteye.com/upload/attachment/0093/2027/0445a204-f6b1-37ae-b73c-40ea4376b54a.png)

![](http://dl2.iteye.com/upload/attachment/0093/2029/a619dd0c-98fe-3295-80bb-ccc64dfe352e.png)

## circleimageview

<img src="https://camo.githubusercontent.com/e17a2a83e3e205a822d27172cb3736d4f441344d/68747470733a2f2f7261772e6769746875622e636f6d2f68646f64656e686f662f436972636c65496d616765566965772f6d61737465722f73637265656e73686f742e706e67" width="400" />

## RoundedImageView

![](https://camo.githubusercontent.com/ed1e075be6ed97fa9091d3702e9b96d3e85b7a35/68747470733a2f2f7261772e6769746875622e636f6d2f6d616b6572616d656e2f526f756e646564496d616765566965772f6d61737465722f73637265656e73686f742e706e67) ![](https://camo.githubusercontent.com/d4970a90842c50a708f94b7bd996657c41ab62fb/68747470733a2f2f7261772e6769746875622e636f6d2f6d616b6572616d656e2f526f756e646564496d616765566965772f6d61737465722f73637265656e73686f742d6f76616c2e706e67)

## SelectableRoundedImageView

![](https://camo.githubusercontent.com/d359ae58a72bc330df60758703185777a15bd1a0/687474703a2f2f692e696d6775722e636f6d2f6953697a4838322e706e67))


# **5、高斯模糊，毛玻璃，图片模糊**

| 框架名称   | 功能描述 |
|:--------------- |:----------------------- |
|[android-stackblur](https://github.com/kikoso/android-stackblur)|Android StackBlur is a library that can perform a blurry effect on a Bitmap based on a gradient or radius, and return the result. The library is based on the code of Mario Klingemann.|
|[Blurry](https://github.com/wasabeef/Blurry)|Blurry is an easy blur library for Android|
|[blurkit-android](https://github.com/wonderkiln/blurkit-android)|The missing Android blurring library. Fast blur-behind layout that parallels iOS.|
|[BlurView](https://github.com/Dimezis/BlurView)|Dynamic iOS-like blur of underlying Views for Android|
|[ImageBlurring](https://github.com/qiujuer/ImageBlurring)|Android blurring image(bitmap) by java and jni|

## 

<img src="https://camo.githubusercontent.com/9c26fa38f23bb218558ad1843f59042ae3d90309/68747470733a2f2f7261772e6769746875622e636f6d2f6b696b6f736f2f616e64726f69642d737461636b626c75722f6d61737465722f6172742f73637265656e73686f74312e706e67" height="400" />

