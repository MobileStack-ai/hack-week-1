# Mobile HackWeek Starter Pack

Starter repo for hack week 1 (Money) with starter **Android** and **iOS** apps. The iOS and Android projects are both named **Money**.

## Setup

1. **Fork** this repository to your own account to implement your features.
2. **Clone your fork** locally (use your fork’s URL so you can push branches).
3. Open the projects:
   - **Android Studio**: **File → Open** → select the `android/` directory.
   - **Xcode**: open `ios/Money.xcodeproj`.

## Repository layout

- **`android/`** — Kotlin, Jetpack Compose (Material 3). Open `android/` in Android Studio.
- **`ios/`** — SwiftUI app. Open `ios/Money.xcodeproj` in Xcode.

## Requirements

### Xcode

- **Xcode 26.3 or newer** (project created with Xcode 26.3).
- **macOS** is required for iOS development.
- This project targets **iOS 26.2** and uses **Swift 5.0**. Use an Xcode / SDK / simulator stack that matches those settings (including any beta or preview channel your team standardizes on).

### Android Studio

- A recent **Android Studio** release that supports **Android Gradle Plugin 9.1.0** and **Gradle 9.3.1** (see `android/gradle/libs.versions.toml` and `android/gradle/wrapper/gradle-wrapper.properties`).
- **JDK 17** (use the JDK bundled with Android Studio unless you have a specific reason not to).
- App module SDK levels: **minSdk 24**, **targetSdk 36**, **compileSdk** API 36 with minor level 1.
- **Kotlin 2.2.10** with Jetpack Compose (Compose BOM is declared in `android/gradle/libs.versions.toml`).