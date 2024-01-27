# LoadingView

[![Download](https://img.shields.io/badge/download-App-blue.svg)](https://raw.githubusercontent.com/jenly1314/LoadingView/master/app/release/app-release.apk)
[![Jitpack](https://jitpack.io/v/jenly1314/LoadingView.svg)](https://jitpack.io/#jenly1314/LoadingView)
[![CI](https://travis-ci.org/jenly1314/LoadingView.svg?branch=master)](https://travis-ci.org/jenly1314/LoadingView)
[![CircleCI](https://circleci.com/gh/jenly1314/LoadingView.svg?style=svg)](https://circleci.com/gh/jenly1314/LoadingView)
[![API](https://img.shields.io/badge/API-16%2B-blue.svg?style=flat)](https://android-arsenal.com/api?level=16)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/mit-license.php)

LoadingView for Android 是一个圆弧加载过渡动画，圆弧个数，大小，弧度，渐变颜色，完全可配。

## Gif 展示
![Image](GIF.gif)

> 你也可以直接下载 [演示App](https://raw.githubusercontent.com/jenly1314/LoadingView/master/app/release/app-release.apk) 体验效果

## 引入

### Gradle:

1. 在Project的 **build.gradle** 或 **setting.gradle** 中添加远程仓库

    ```gradle
    repositories {
        //...
        mavenCentral()
        maven { url 'https://jitpack.io' }
    }
    ```

2. 在Module的 **build.gradle** 里面添加引入依赖项

    ```gradle
    implementation 'com.github.jenly1314:LoadingView:1.0.0'
    ```

## 使用

## LoadingView自定义属性说明（默认渐变色）

| 属性 | 值类型 | 默认值 | 说明 |
| :------| :------ | :------ | :------ |
| lvCount | integer | 1 | 圆弧数量 |
| lvStartAngle | integer | 0 | 圆弧开始角度，默认三点钟方向 |
| lvSweepAngle | integer | 360 | 圆弧扫描角度范围 |
| lvStrokeWidth | dimension | 3dp | 笔画描边的宽度 |
| lvMaxSpeed | integer | 5 | 最大速度 |
| lvMinSpeed | integer | 3 | 最小速度 |
| lvCirclePadding | dimension | 2dp | 圆弧之间的间距 |
| lvRefreshInterval | integer | 15 | 刷新间隔时间，单位ms |
| lvColor | color | | 圆弧颜色，默认渐变色 |
| lvCounterclockwise | boolean | false | 是否逆时针方向旋转 |

## 示例

布局示例
```Xml
    <com.king.view.load.LoadingView
        android:id="@+id/loadingView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"/>
```

更多使用详情，请查看[app](app)中的源码使用示例或直接查看 [API帮助文档](https://jitpack.io/com/github/jenly1314/LoadingView/latest/javadoc/)

## 版本记录

#### v1.0.0：2019-8-9
*  LoadingView初始版本

## 赞赏
如果您喜欢LoadingView，或感觉LoadingView帮助到了您，可以点右上角“Star”支持一下，您的支持就是我的动力，谢谢 :smiley:
<p>您也可以扫描下面的二维码，请作者喝杯咖啡 :coffee:

<div>
   <img src="https://jenly1314.github.io/image/page/rewardcode.png">
</div>

## 关于我

| 我的博客                                                                                | GitHub                                                                                  | Gitee                                                                                  | CSDN                                                                                 | 博客园                                                                            |
|:------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------|
| <a title="我的博客" href="https://jenly1314.github.io" target="_blank">Jenly's Blog</a> | <a title="GitHub开源项目" href="https://github.com/jenly1314" target="_blank">jenly1314</a> | <a title="Gitee开源项目" href="https://gitee.com/jenly1314" target="_blank">jenly1314</a>  | <a title="CSDN博客" href="http://blog.csdn.net/jenly121" target="_blank">jenly121</a>  | <a title="博客园" href="https://www.cnblogs.com/jenly" target="_blank">jenly</a>  |

## 联系我

| 微信公众号        | Gmail邮箱                                                                          | QQ邮箱                                                                              | QQ群                                                                                                                       | QQ群                                                                                                                       |
|:-------------|:---------------------------------------------------------------------------------|:----------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------|
| [Jenly666](http://weixin.qq.com/r/wzpWTuPEQL4-ract92-R) | <a title="给我发邮件" href="mailto:jenly1314@gmail.com" target="_blank">jenly1314</a> | <a title="给我发邮件" href="mailto:jenly1314@vip.qq.com" target="_blank">jenly1314</a> | <a title="点击加入QQ群" href="https://qm.qq.com/cgi-bin/qm/qr?k=6_RukjAhwjAdDHEk2G7nph-o8fBFFzZz" target="_blank">20867961</a> | <a title="点击加入QQ群" href="https://qm.qq.com/cgi-bin/qm/qr?k=Z9pobM8bzAW7tM_8xC31W8IcbIl0A-zT" target="_blank">64020761</a> |

<div>
   <img src="https://jenly1314.github.io/image/page/footer.png">
</div>
