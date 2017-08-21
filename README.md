<?xml version="1.0" encoding="utf-8"?>
<menu xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto">

    <group android:checkableBehavior="single">

        <item
            android:id="@+id/home"
            android:icon="@drawable/home"
            android:title="@string/home" />
        <item
            android:id="@+id/men"
            android:icon="@drawable/men"
            android:title="@string/men" />
        <item
            android:id="@+id/women"
            android:icon="@drawable/women"
            android:title="@string/women" />
        <item
            android:id="@+id/electronics"
            android:icon="@drawable/electronics"
            android:title="@string/electronics" />

        <item
            android:id="@+id/home_living"
            android:icon="@drawable/furniture"
            android:title="@string/home_living" />

        <item
            android:id="@+id/art_crafts"
            android:icon="@drawable/craft"
            android:title="@string/art_crafts" />
    </group>

    <item android:title="Other">
        <menu>
            <item
                android:id="@+id/nav_about_us"
                android:title="@string/about_us" />
            <item
                android:id="@+id/nav_privacy_policy"
                android:title="@string/privacy_policy" />
        </menu>
    </item>

</menu>
