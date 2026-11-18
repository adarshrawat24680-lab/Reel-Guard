# ReelGuard (experimental starter)

A small native Android starter project for a privacy-first Reel activity estimate.

## Important limitations
- Instagram does not provide a public API that reports how many Reels a person watched.
- This prototype uses Android Accessibility events and visible UI labels as a heuristic.
- It can miss events or count incorrectly. Instagram UI, language, and versions can change the result.
- It does not block Instagram, read messages, save screenshots, or upload activity.
- Accessibility access is powerful. Enable it only if you understand and accept the disclosure shown by Android. You can disable it at any time in Android Settings.

## Build
Open this project in Android Studio on a computer or a compatible cloud Android build environment, sync Gradle, then build the debug APK.

The project is source code, not an APK. A real APK still needs to be compiled and tested on an Android device.
