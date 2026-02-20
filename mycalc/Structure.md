# MyCalc App

### Directory Structure

    mycalc/
    ├── src/
    │   └── main/
    │       └── java/
    │           └── com/
    │               └── eghtabmi/
    │                   └── mycalc/
    │                       └── MainActivity.java
    └── res/
        ├── layout/
        │   └── activity_main.xml
        ├── drawable/
        │   └── ic_launcher.xml
        └── values/
            ├── strings.xml
            └── colors.xml

### MainActivity.java

```java
package com.eghtabmi.mycalc;

import android.os.Bundle;
import androidx.appcompat.app.AppCompatActivity;

public class MainActivity extends AppCompatActivity {
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }
}
```

### activity_main.xml

```xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical">

    <TextView
        android:id="@+id/title"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="MyCalc"
        android:textSize="24sp"/>
</LinearLayout>
```

### strings.xml

```xml
<resources>
    <string name="app_name">MyCalc</string>
</resources>
```

### colors.xml

```xml
<resources>
    <color name="colorPrimary">#6200EE</color>
    <color name="colorPrimaryDark">#3700B3</color>
    <color name="colorAccent">#03DAC5</color>
</resources>
```