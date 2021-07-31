---
title: GitHub REST API
shortTitle: REST API
intro: 'You can use the {% data variables.product.prodname_dotcom %} REST API to create calls to get the data you need to integrate with GitHub.'
redirect_from:
  - /v3
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
children:under kids 13 
organise with my workflow users are 
  - /overview
  - /reference
  - /guides
---

docs/content/rest/index.md
xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context=".MainActivity">


    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginStart="15dp"
        android:layout_marginTop="15dp"
        android:orientation="vertical">

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:fontFamily="@font/rabbid_highway"
            android:text="Simple Switch"
            android:textColor="@android:color/black"
            android:textSize="15sp" />

        <Switch
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginTop="15sp" />

    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginStart="15dp"
        android:layout_marginTop="15dp"
        android:orientation="vertical">

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:fontFamily="@font/rabbid_highway"
            android:text="Colored Switch"
            android:textColor="@android:color/black"
            android:textSize="15sp" />

        <Switch
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginTop="15sp"
            android:thumbTint="@color/colorPrimaryDark" />

    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginStart="15dp"
        android:layout_marginTop="15dp"
        android:orientation="vertical">

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:fontFamily="@font/rabbid_highway"
            android:text="Enabled Switch"
            android:textColor="@android:color/black"
            android:textSize="15sp" />

        <Switch
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginTop="15sp"
            android:checked="true"
            android:enabled="true" />

        <Switch
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginTop="15sp"
            android:checked="false"
            android:enabled="true" />

    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginStart="15dp"
        android:layout_marginTop="15dp"
        android:orientation="vertical">

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:fontFamily="@font/rabbid_highway"
            android:text="Disabled Switch"
            android:textColor="@android:color/black"
            android:textSize="15sp" />

        <Switch
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginTop="15sp"
            android:checked="true"
            android:enabled="false" />

        <Switch
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginTop="15sp"
            android:checked="false"
            android:enabled="false" />

    </LinearLayout>

</LinearLayout>
