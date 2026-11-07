# File editor (starter Android project)

A non-root, offline-first Android starter built with Kotlin and Jetpack Compose.

## Included in this first build
- Nothing OS-inspired dark glassmorphism home screen
- Android system document picker (Storage Access Framework)
- APK/ZIP archive inspection (lists up to 300 archive entries)
- No INTERNET permission, analytics SDK, or advertising SDK
- Does not request root access

## Important limitations
This is a starter project, not a complete MT Manager replacement. It does not yet edit/rebuild/sign APKs, modify DEX/Smali, access other apps' private data, or bypass Android storage restrictions. Non-root Android cannot provide unrestricted root-level access.

## Build
1. Open this folder in Android Studio (recent version).
2. Allow Gradle sync.
3. Connect an Android device or start an emulator.
4. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Install the generated debug APK on your own device.

Requires JDK 17 and Android SDK 35. Gradle wrapper is not included; Android Studio can generate/use the wrapper during project setup.
