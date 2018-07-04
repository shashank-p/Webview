# Webview

Webview App

It is a simple application by using which you can make android app of any website, If website is responsive it'll look better as an app.
To edit URL use below code.
```
mWebView.loadUrl("http://www.symist.com/");
mWebView.setWebViewClient(new MyWebViewClient());
```
It also support the concept of running local html file as information page without any internet. To edit this use below code.
```
mWebView.loadUrl("file:///android_asset/index.html");
```
In this local html files are stored in assets folder

It is built to work on Android 5.1 & above

Technologies used: Android, Java, XML

IDE: Android Studio 3.1.1

ScreenShots

![picture](img/1.png)
![picture](img/2.png)
