# Mobile HackWeek Starter Pack

- Starter repo for hack week 1 with starter **Android** and **iOS** apps. 
- The iOS and Android projects are both named **Money**.
- You are only required to build an Android or iOS Money app but you could build out both if you would like to.

## Setup

1. **Fork** this repository to your own account.
2. **Clone your fork** locally (use your fork’s URL so you can push changes).
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

### Android Studio (Recommended)

- A recent **Android Studio** release that supports **Android Gradle Plugin 9.1.0** and **Gradle 9.3.1** (see `android/gradle/libs.versions.toml` and `android/gradle/wrapper/gradle-wrapper.properties`).
- **JDK 17** (Use the JDK bundled with Android Studio unless you have a specific reason not to).
- **Minimum SDK 24**.
- **Kotlin 2.2.10** with Jetpack Compose.