# DashedLineSample
虚线

## 使用
```
  implementation 'com.zm.common:dashedline:1.0.0'
  
```

## 示例[activity_main.xml](https://github.com/scalling/DashedLineSample/blob/master/app/src/main/res/layout/activity_main.xml)
```
        <com.zm.common.view.DashedLine
                android:layout_width="match_parent"
                android:layout_height="wrap_content" />
                
        <com.zm.common.view.DashedLine
                android:layout_width="match_parent"
                android:layout_height="1dp"
                app:dashWidth="0.1dp"
                app:dashedLineColor="@android:color/holo_orange_dark"//虚线详情
                app:dashedBgColor="@android:color/darker_gray"//虚线背景颜色
                android:layout_margin="30dp"/>//虚线粗细
```
<img src="https://github.com/scalling/DashedLineSample/blob/master/screenshot/1.jpg" width = "500"/>
