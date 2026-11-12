# NotHub Pro Android

This repository contains the NotHub Pro Android WebView wrapper and the full HTML application.

## Build APK
GitHub Actions runs the Android build on pushes to `main` or `master`, and can also be started manually from **Actions → Build NotHub Pro APK → Run workflow**.

The workflow uses JDK 17, Android SDK 35 and Gradle 8.9. On success, download the `NotHub-Pro-debug-APK` artifact and extract `app-debug.apk`.

The debug APK is intended for personal installation/testing. A Play Store release requires a separately signed release build.

The app stores notes and browser data locally on the device. Internet access is used for online services and AI features.
