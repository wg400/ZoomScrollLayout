# ZoomScrollLayout
## android 自定义的可以平移缩放的ViewGroup

    话不多说，直接上图：
![](https://github.com/wg400/ZoomScrollLayout/blob/master/image/1.gif?raw=true)  
![](https://github.com/wg400/ZoomScrollLayout/blob/master/image/66.gif?raw=true)  

    使用方法
```xml
<com.wanggang.ZoomScrollLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="vertical"
        android:gravity="center"
        android:background="@color/blue">
        <ImageView
            android:layout_width="90dp"
            android:layout_height="90dp"
            android:scaleType="fitXY"
            android:src="@mipmap/ic_launcher" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="天才的我， 啊哈哈"
            android:textColor="@color/white"/>

        <Button
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="点击我啊"/>
    </LinearLayout>
</com.wanggang.ZoomScrollLayout>
```
