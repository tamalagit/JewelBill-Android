# Jewel Bill — Android project

This packages the supplied `index.html` app in a native Android WebView.

## Build an APK (Android Studio)

1. Install Android Studio and the Android SDK (API 35 or newer).
2. Open this `JewelBillAndroid` folder in Android Studio.
3. Allow Gradle sync and install any SDK components Android Studio requests.
4. Select **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
5. Android Studio will show the generated APK location (normally `app/build/outputs/apk/debug/app-debug.apk`).

For a shareable release APK, use **Build → Generate Signed Bundle / APK → APK** and create a signing key.

## App behavior

- App title: Jewel Bill
- Package ID: `com.jewelbill.app`
- Minimum Android: Android 6.0 (API 23)
- Billing data is stored locally in the WebView's browser storage on that phone.
- Use **More → Settings → Export backup** regularly. Reinstalling or clearing app data can erase local records.
- Printing is connected to Android's print service.

This is an Android Studio project, not a precompiled APK. It requires Android Studio/Android SDK to compile.
