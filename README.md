# 24012011147_MAD_PRACTICAL-2

This project is an Android application developed as part of a Mobile Application Development (MAD) practical assignment. It primarily focuses on demonstrating and understanding the **Android Activity Lifecycle**.

## Project Overview

The application consists of two main activities:
1. **MainActivity**: The entry point of the application.
2. **LoginActivity**: An activity that overrides various lifecycle methods to show how Android manages activity states.

## Key Features

- **Lifecycle Monitoring**: Both activities log their lifecycle transitions (e.g., `onCreate`, `onStart`, `onResume`, `onPause`, `onStop`, `onDestroy`) to the Android **Logcat**.
- **User Feedback**: `LoginActivity` uses `Toast` messages to provide visual feedback whenever a lifecycle method is triggered.

## How to use

1. **Clone/Open**: Open the project in **Android Studio**.
2. **Sync**: Ensure Gradle synchronization is complete.
3. **Run**: Deploy the app to an Android Emulator or a physical device.
4. **Monitor Logcat**:
   - Open the **Logcat** tab in Android Studio.
   - Filter by the tag `LoginActivity` or `MainActivity` to see the lifecycle method calls.
   - Example Log: `I/LoginActivity: onCreate method is called`

## Technical Details

- **Language**: Kotlin
- **Minimum SDK**: Defined in `build.gradle` (likely 24 or higher)
- **UI Framework**: XML Layouts with AppCompat
- **Components**: `Log.i` for logging, `Toast` for UI notifications.

---
*Developed as part of the MAD Practical Course.*
