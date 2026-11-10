# NEXUS TV DESKTOP V6.0

An Android TV launcher project targeting Android 9-compatible devices, including testing intended for Skyworth platforms.

## Build APK

The repository includes `.github/workflows/android.yml`. After pushing, open the **Actions** tab and run or wait for **Build Android APK**. Download the `nexus-tv-desktop-v6-debug` artifact if the build succeeds.

## Build locally

Open the project in Android Studio, sync Gradle, then select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.

## V6.0 remote-only app sorting

1. Use the remote arrows to focus an app tile.
2. Press MENU / INFO to enter sorting mode.
3. Use LEFT / RIGHT to move one tile; UP / DOWN to move five positions.
4. Press OK / ENTER to save, or BACK to cancel.

This is source code, not a prebuilt APK. It has not yet been compiled or physically tested on the target television.