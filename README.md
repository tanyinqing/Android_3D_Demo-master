# [exlipse如何github上传](#20171228_1)

<h1 id="20171228_1">exlipse如何github上传</h1>

- 先在github上建立一个库
- 把https的地址配置到url = "" 配置文件中

```
studio配置
[user]
  name = tg
  email = 2@qq.com

exlipse配置
[core]
 repositoryformatversion = 0
 filemode = false
 bare = false
 logallrefupdates = true
 symlinks = false
 ignorecase = true
 hideDotFiles = dotGitOnly
[remote "origin"]
 url = "" 

fetch = +refs/heads/*:refs/remotes/origin/*
[branch "master"]
 remote = origin
 merge = refs/heads/master
[user]
 name = tg
 email = 27@qq.com

```

- geocoder.GeocoderActivity  地理编码 功能
- basic.ScreenShotActivity  地图截屏功能


Android_3D_Demo
===============
本工程为高德地图Android SDK 3D版本的官方Demo，基于3D地图2.2.1版本。

##前述：
 
- [高德官方网站申请key](http://id.amap.com/?ref=http%3A%2F%2Fapi.amap.com%2Fkey%2F).
- 阅读[参考手册](http://api.amap.com/Public/reference/Android%20API%20v2/).
- 如果有任何疑问也可以发问题到[官方论坛](http://bbs.amap.com/forum.php?gid=1).

##效果图如下：

* ![图片](https://raw.githubusercontent.com/amapapi/Android_3D_Demo/master/resource/%E5%9F%BA%E6%9C%AC%E5%8A%9F%E8%83%BD.jpg)
* ![图片](https://raw.githubusercontent.com/amapapi/Android_3D_Demo/master/resource/%E6%90%9C%E7%B4%A2%E5%8A%9F%E8%83%BD.jpg)
* ![图片](https://raw.githubusercontent.com/amapapi/Android_3D_Demo/master/resource/%E8%B7%AF%E5%BE%84%E8%A7%84%E5%88%92%E5%8A%9F%E8%83%BD.jpg)
* ![图片](https://raw.githubusercontent.com/amapapi/Android_3D_Demo/master/resource/%E5%8A%9F%E8%83%BD.jpg)
* ![图片](https://raw.githubusercontent.com/amapapi/Android_3D_Demo/master/resource/%E5%85%B6%E4%BB%96%E5%8A%9F%E8%83%BD.jpg)

##使用方法：

[使用方法](http://developer.amap.com/api/android-sdk/summary/)

##下载资源如下：

+ [实例应用](https://github.com/amapapi/Android_3D_Demo/raw/master/resource/AMapApiV2Demo.apk) (apk)

+ 扫一扫下载应用

![图片](https://raw.githubusercontent.com/amapapi/Android_3D_Demo/master/resource/%E4%BA%8C%E7%BB%B4%E7%A0%81.png )