<div dir = "rtl">

#  تمرين مسار الأندرويد الأول 💚
## التمرين سهل و بسيط 💪🏻

### الخطوات:




<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:background="#f0e2d0"
        android:orientation="vertical"

        tools:layout_editor_absoluteX="203dp"
        tools:layout_editor_absoluteY="82dp">

        <TextView
            android:id="@+id/textView"
            android:layout_width="200dp"
            android:layout_height="60dp"
            android:layout_gravity="center_horizontal"
            android:layout_margin="100dp"
            android:layout_marginStart="10dp"
            android:layout_marginTop="30dp"
            android:fontFamily="sans-serif-smallcaps"
            android:text="Grade Calculator"
            android:textAlignment="center"
            android:textAppearance="@style/TextAppearance.AppCompat.Medium"
            android:textColor="#70af85"
            android:textSize="24sp"
            android:typeface="sans" />

        <EditText
            android:id="@+id/editTextNumber"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:layout_margin="10dp"
            android:background="#c6ebc9"
            android:ems="10"
            android:hint="Quizzes 15%"
            android:inputType="number"
            android:textAlignment="center"
            android:textColor="#70af85" />

        <EditText
            android:id="@+id/editTextNumber2"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:layout_margin="10dp"
            android:background="#c6ebc9"
            android:ems="10"
            android:hint="Homework 25%"
            android:inputType="number"
            android:textAlignment="center"
            android:textColor="#70af85" />

        <EditText
            android:id="@+id/editTextNumber3"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:layout_margin="10dp"
            android:background="#c6ebc9"
            android:ems="10"
            android:hint="Mideterms 30%"
            android:inputType="number"
            android:textAlignment="center"
            android:textColor="#70af85" />

        <EditText
            android:id="@+id/editTextNumber4"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:layout_margin="10dp"
            android:background="#c6ebc9"
            android:ems="10"
            android:hint="Final 30%"
            android:inputType="number"
            android:textAlignment="center"
            android:textColor="#70af85" />

        <Button
            android:id="@+id/button2"
            android:layout_width="150dp"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:layout_margin="30dp"
            android:background="#f0e2d0"
            android:fontFamily="sans-serif-smallcaps"
            android:text="Calculate"
            android:textColor="#aa8976"
            app:iconTint="#f0e2d0" />

        <TextView
            android:id="@+id/textView2"
            android:layout_width="150dp"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:fontFamily="sans-serif-smallcaps"
            android:text="Result"
            android:textAlignment="center"
            android:textColor="#70af85"
            android:textSize="24sp" />

    </LinearLayout>

</androidx.constraintlayout.widget.ConstraintLayout>

</div>
