# ShadowLayout
一个简单的阴影布局库

[![](https://jitpack.io/v/qzc0537/ShadowLayout.svg)](https://jitpack.io/#qzc0537/ShadowLayout)

![ShadowLayout](https://github.com/qzc0537/ShadowLayout/blob/master/img.png)


使用
--
1.project build.gradle下添加：
maven { url 'https://jitpack.io' }

如下：

```
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}
```

2.app build.gradle下添加依赖 ：

```
implementation 'com.github.qzc0537:ShadowLayout:1.0.1'
```

3.愉快的使用：
```
<com.qzc.shadowlayout.ShadowLayout
        android:layout_width="120dp"
        android:layout_height="120dp"
        android:layout_marginTop="20dp"
        app:sl_shadow_color="#66000000"
        app:sl_background_color="#FFFFFF"
        app:sl_offsetX="3dp"
        app:sl_offsetY="3dp"
        app:sl_layout_radius="5dp"
        app:sl_shadow_radius="5dp">

    <TextView
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:text="Hello World!"
            android:gravity="center"/>
</com.qzc.shadowlayout.ShadowLayout>

