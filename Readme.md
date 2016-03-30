MEGA Android Client
================

A fully-featured client to access your Cloud Storage provided by MEGA.

This document will guide you to build the application on a Linux machine with Android Studio.

### Setup development environment

* [Android Studio](http://developer.android.com/intl/es/sdk/index.html)

* [Android SDK Tools](http://developer.android.com/intl/es/sdk/index.html#Other)

* [Android NDK](http://developer.android.com/intl/es/ndk/downloads/index.html)

### Build & Run the application

* Get the source code

```
git clone --recursive https://github.com/meganz/android2.git
```

* Configure the variable `NDK_ROOT` to point to your Android NDK installation path at `jni/Makefile`.

* Run the previous `Makefile` in order to build the MEGA SDK, its dependencies and the required bindings for Java. Moreover, it will automatically download and build several libraries required by the SDK: OpenSSL, cURL, ares, Crypto++, Sodium and SQLite.

* Open the project with Android Studio, let it build the project and hit _*Run*_
