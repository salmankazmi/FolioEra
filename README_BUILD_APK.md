# FolioEra Premium — Android APK Build Guide

This zip package contains the complete native Android Capacitor wrapper for FolioEra Premium.

### Option 1: Automated 1-Click APK Build via GitHub Actions (Easiest)
1. Create a GitHub repository and push this project folder.
2. Go to the **Actions** tab on your GitHub repository.
3. The "Build Android APK" workflow will automatically run and compile your signed debug APK.
4. Download the compiled `FolioEra-Premium-Debug-APK` (.apk file) directly from GitHub Artifacts onto your Android tablet or phone!

### Option 2: Build locally using Android Studio
1. Unzip this package.
2. Open the `android` directory in **Android Studio**.
3. Let Gradle sync and resolve Android SDK 34 packages.
4. Click **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Your APK will be generated at:
   `android/app/build/outputs/apk/debug/app-debug.apk`
6. Transfer to your phone or tablet via USB/Google Drive and tap to install!

### Features included in this APK configuration:
- ReadEra-style `IntentFilter` to open .epub and .pdf files directly from your Android file manager.
- Hardware-accelerated WebView with full offline storage (IndexedDB).
- Native status bar and tablet split-screen support.
