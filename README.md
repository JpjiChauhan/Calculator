<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity"
    tools:ignore="ExtraText">

    <ImageView
        android:id="@+id/inputTxt"
        android:layout_width="wrap_content"
        android:layout_height="match_parent"
        android:layout_above="@+id/outPuttxt"
        android:gravity="right"
        android:paddingRight="20dp"
        android:textColor="#675B5B"
        android:textSize="40dp"/>
    <ImageView
        android:id="@+id/outPuttxt"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_above="@id/Buttons"
        android:gravity="right"
        android:paddingRight="20dp"
        android:textColor="@color/black"
        android:textSize="90dp"/>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/Buttons"
        android:orientation="vertical"
        android:backgroundTint="#000"
        android:layout_alignParentBottom="true" />


    <LinearLayout
        android:layout_marginTop="10dp"
        android:layout_marginBottom="10dp"
        android:paddingTop="5dp"
        android:gravity="center"
        android:paddingBottom="5dp"
        android:orientation="horizontal"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"/>
    <ImageView
        android:layout_width="70dp"
        android:layout_marginStart="25dp"
        android:background="@drawable/btn_1"
        android:layout_height="70dp"
        android:visibility="invisible"
        android:layout_marginLeft="25dp"
        android:layout_marginEnd="25dp"
        android:layout_marginRight="25dp"/>

    <ImageView
        android:id="@+id/btn_ac"
        android:layout_width="70dp"
        android:background="@drawable/btn_ac"
        android:layout_marginRight="25dp"
        android:layout_height="70dp"/>
        
    <ImageView
        android:layout_width="70dp"
        android:background="@drawable/btn_dot"
        android:visibility="invisible"
        android:layout_marginRight="25dp"
        android:layout_height="70dp"/>

    <ImageView
        android:id="@+id/btn_divide"
        android:layout_width="70dp"
        android:background="@drawable/btn_divide"
        android:layout_marginRight="25dp"
        android:layout_height="70dp" />

    <LinearLayout
        android:layout_marginTop="10dp"
        android:layout_marginBottom="10dp"
        android:paddingTop="5dp"
        android:gravity="center"
        android:paddingBottom="5dp"
        android:orientation="horizontal"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"/>
    <ImageView
        android:id="@+id/btn_7"
        android:layout_width="70dp"
        android:layout_marginStart="25dp"
        android:background="@drawable/btn_7"
        android:layout_height="70dp"
        android:layout_marginLeft="25dp"
        android:layout_marginEnd="25dp"
        android:layout_marginRight="25dp"/>
    <ImageView
        android:id="@+id/btn_8"
        android:layout_width="70dp"
        android:background="@drawable/btn_8"
        android:layout_marginRight="25dp"
        android:layout_height="70dp"/>
    <ImageView
       android:id="@+id/btn_9"
        android:layout_width="70dp"
        android:background="@drawable/btn_9"
        android:layout_marginRight="25dp"
        android:layout_height="70dp"/>
   <ImageView
       android:id="@+id/btn_multiplication"
       android:layout_width="70dp"
       android:background="@drawable/btn_multiplication"
       android:layout_marginRight="25dp"
       android:layout_height="70dp"/>

    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="match_parent"
        android:layout_marginTop="10dp"
        android:layout_marginBottom="10dp"
        android:gravity="center"
        android:orientation="horizontal"
        android:paddingTop="5dp"
        android:paddingBottom="5dp" />

    <ImageView
        android:id="@+id/btn_4"
        android:layout_width="70dp"
        android:layout_marginStart="25dp"
        android:background="@drawable/btn_4"
        android:layout_height="70dp"
        android:layout_marginLeft="25dp"
        android:layout_marginEnd="25dp"
        android:layout_marginRight="25dp" />
    <ImageView
        android:id="@+id/btn_5"
        android:layout_width="70dp"
        android:background="@drawable/btn_5"
        android:layout_marginRight="25dp"
        android:layout_height="70dp"/>
    <ImageView
        android:id="@+id/btn_6"
        android:layout_width="70dp"
        android:background="@drawable/btn_6"
        android:layout_marginRight="25dp"
        android:layout_height="70dp"/>
    <ImageView
        android:id="@+id/btn_minus"
        android:layout_width="70dp"
        android:background="@drawable/btn_minus"
        android:layout_marginRight="25dp"
        android:layout_height="70dp"/>
/>
    <LinearLayout
        android:layout_marginTop="10dp"
        android:layout_marginBottom="10dp"
        android:paddingTop="5dp"
        android:gravity="center"
        android:paddingBottom="5dp"
        android:orientation="horizontal"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"/>
    <ImageView
        android:id="@+id/btn_1"
        android:layout_width="70dp"
        android:layout_marginStart="25dp"
        android:background="@drawable/btn_1"
        android:layout_height="70dp"
        android:layout_marginLeft="25dp"
        android:layout_marginEnd="25dp"
        android:layout_marginRight="25dp" />
    <ImageView
        android:id="@+id/btn_2"
        android:layout_width="70dp"
        android:background="@drawable/btn_2"
        android:layout_marginRight="25dp"
        android:layout_height="70dp"/>
    <ImageView
        android:id="@+id/btn_3"
        android:layout_width="70dp"
        android:background="@drawable/btn_3"
        android:layout_marginRight="25dp"
        android:layout_height="70dp"/>
    <ImageView
        android:id="@+id/btn_plus"
        android:layout_width="70dp"
        android:background="@drawable/btn_plus"
        android:layout_marginRight="25dp"
        android:layout_height="70dp"/>
/>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginTop="10dp"
        android:layout_marginBottom="10dp"
        android:gravity="center"
        android:orientation="horizontal"
        android:paddingTop="5dp"
        android:paddingBottom="5dp" />
    <ImageView
        android:layout_width="70dp"
        android:layout_marginStart="25dp"
        android:background="@drawable/btn_1"
        android:layout_height="70dp"
        android:visibility="invisible"
        android:layout_marginLeft="25dp"
        android:layout_marginEnd="25dp"
        android:layout_marginRight="25dp" />
    <ImageView
        android:id="@+id/btn_0"
        android:layout_width="70dp"
        android:background="@drawable/btn_0"
        android:layout_marginRight="25dp"
        android:layout_height="70dp"/>

    <ImageView
        android:id="@+id/btn_dot"
        android:layout_width="70dp"
        android:layout_height="70dp"
        android:layout_marginRight="25dp"
        android:background="@drawable/btn_dot" />

    <ImageView
        android:id="@+id/btn_equal"
        android:layout_width="70dp"
        android:layout_height="70dp"
        android:layout_marginRight="25dp"
        android:background="@drawable/btn_equal" />
    />


</RelativeLayout>
