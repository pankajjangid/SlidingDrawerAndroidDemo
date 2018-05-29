# SlidingDrawerAndroidDemo
Sliding Drawer In Android Without Lib

#Setting up the layout

**activity_main.xml**


`<?xml version="1.0" encoding="utf-8"?>
<android.support.v4.widget.DrawerLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:id="@+id/drawerLayout"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@color/profile_menu_bg">

    <LinearLayout
        android:id="@+id/content"

        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="vertical">

        <include layout="@layout/toolbar" />

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="@color/colorPrimary"
            android:gravity="center_horizontal"
            android:orientation="vertical"
            android:padding="16dp">

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Sliding Drawer Tutorial"
                android:textColor="@android:color/white"
                android:textSize="24sp" />

        </LinearLayout>
    </LinearLayout>

    <LinearLayout
        android:id="@+id/drawer"
        android:layout_width="200dp"
        android:layout_height="match_parent"
        android:layout_gravity="start"
        android:gravity="center_horizontal"
        android:orientation="vertical">

        <include layout="@layout/profile_menu" />

    </LinearLayout>

</android.support.v4.widget.DrawerLayout>`





