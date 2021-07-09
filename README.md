__Step 1.__ Add the JitPack repository to your build file

    allprojects {
        repositories {
            ...
            maven { url 'https://jitpack.io' }
        }
    }
    

__Step 2.__ Add the dependency    
    
    dependencies {
            implementation 'com.github.kisoojo:kscalendar:1.0'
    }


__How to use__
    
    <com.zenoation.library.KSCalendar
        android:layout_width="match_parent"
        android:layout_height="wrap_content"/>
    
    - setOnClickPrevListener() : Prev arrow click listener
    - setOnClickNextListener() : Next arrow click listener
    - setOnClickDayListener() : Day click listener
