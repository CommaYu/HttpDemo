# HttpDemo
HttpURLConnection和HttpClient基本入门
Android上发送HTTP请求的方式一般两种：HttpURLConnection和HttpClient
#Android Stduio使用注意
1. AndroidManifest.xml中网络权限开启<uses-permission android:name="android.permission.INTERNET" />（如果没有也不会报错，切记）
2. 由于Android 6.0已结抛弃了HttpClient了，所以要在Android Studio中使用的时候需要在build.gradle中android{}加一句useLibrary 'org.apache.http.legacy'
