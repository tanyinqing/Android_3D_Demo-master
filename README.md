<h1 id="20171228_0">目录</h1>

# [exlipse如何github上传](#20171228_1)
# [文件清单](#20171228_2)
# [其他](#20171228_3)
# [效果图](#20171228_4)

+ [实例应用下载apk文件](https://github.com/amapapi/Android_3D_Demo/raw/master/resource/AMapApiV2Demo.apk) (apk)

<h1 id="20171228_">测试</h1>
[返回](#20171228_0)

<h1 id="20171228_2">文件清单</h1>

|包名|名称|说明|备注|
|--|--|--|--|
|activity|MainActivity|主页|备注|
|basic|ScreenShotActivity|地图截屏|备注|

[返回](#20171228_0)
<h1 id="20171228_3">其他</h1>

- **如果本地和远程出现了不匹配，就把远程的删除了，重新从本地上传上去。因为本地的文件一般不会出现问题，一个人用的情况下，千万不要合并**。
- 出现错误，先删除res下的crunch文件
- 同一台电脑exlipse和studio如何切换
 **JAVA_HOME**
**C:\Program Files(x86)\Java\jdk1.8.0_40**
- 高德地图的模型图
- **值得学习的地方把apk文件和效果一起打包**
[返回](#20171228_0)

<h1 id="20171228_1">exlipse如何github上传</h1>

- 先在github上建立一个库
- 把https的地址配置到url = "" 配置文件中
- 建立一个库
	- 项目右键team-share Project 
	- 打钩 use or create repository in parent folder of project
	- 项目打钩  点击 create repository
	- finish
- 推送到本地 pull
- 提交到库并保存 commit and push  全选

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
[返回](#20171228_0)
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

+ 扫一扫下载应用

![图片](https://raw.githubusercontent.com/amapapi/Android_3D_Demo/master/resource/%E4%BA%8C%E7%BB%B4%E7%A0%81.png )


<h1 id="20171228_4">效果图</h1>

* 这个是apk的主页的页面
* ![图片](https://raw.githubusercontent.com/amapapi/Android_3D_Demo/master/resource/主页.png)
* 这个是apk的地理反编码页面
* ![图片](https://raw.githubusercontent.com/amapapi/Android_3D_Demo/master/resource/地理反编码.png)

[返回](#20171228_0)



