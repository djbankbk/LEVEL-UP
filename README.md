# LEVEL UP Android

A simple offline-first Android app built with a native Android WebView shell. Workout checks, meal checks, weight, notes, and history are stored locally in WebView localStorage.

## Build APK

The included GitHub Actions workflow builds a debug APK. Upload this folder to a GitHub repository, then open **Actions → Build LEVEL UP APK → Run workflow**. Download the `LEVEL-UP-debug-apk` artifact and install `app-debug.apk` on your Android phone. You may need to allow installation from that source.

For local build, install Android Studio / Android SDK (platform 35, build tools 35.0.0), Java 17, and Gradle 8.9, then run `gradle assembleDebug`.

Data is stored on the device and can be lost if app data is cleared or the app is uninstalled. Use the export button for a backup.
