# birthdaycardapp
<RelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">


    <ImageView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:src="@drawable/androidparty"
        android:scaleType="centerCrop"/>

    <TextView
        android:text="Happy Birthday Udit"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textSize="36sp"
        android:fontFamily="sans-serif-light"
        android:textColor="@android:color/white"
        android:layout_margin="20dp"/>


    <TextView
        android:text="From VJ"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_alignParentRight="true"
        android:textSize="36sp"
        android:fontFamily="sans-serif-light"
        android:textColor="@android:color/white"
        android:layout_margin="20dp" />

</RelativeLayout>
