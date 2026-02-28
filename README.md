# DroidCore Monitor

A production-ready Android Mobile Monitoring System Application built with Kotlin, MVVM, Coroutines, and Material Design 3.

## Features
- **RAM Monitoring**: Total, Used, Free, Percentage
- **Storage Monitoring**: Internal Storage Total, Used, Free, Percentage
- **Battery Monitoring**: Percentage, Status, Health, Temperature, Voltage, Technology, Power Source
- **Network Monitoring**: Network Type
- **CPU Monitoring**: Usage, Cores
- **Device Information**: Model, Brand, Android Version, SDK, Hardware, Board

## Architecture
- **Language**: Kotlin
- **Architecture**: MVVM (Model-View-ViewModel)
- **UI**: XML + Material Design 3 (Glassmorphism, Neon Cyberpunk style)
- **Concurrency**: Kotlin Coroutines
- **Build System**: Gradle (KTS)

## How to use
1. Open this project in Android Studio or AndroidIDE.
2. Sync the Gradle files.
3. Build and Run the application on an Android device or emulator (API 26+).

## Permissions
The app requests the following permissions on the first launch:
- `INTERNET`
- `ACCESS_NETWORK_STATE`
- `ACCESS_WIFI_STATE`
- `READ_PHONE_STATE`
