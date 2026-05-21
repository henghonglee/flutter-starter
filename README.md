# Flutter Starter Project

A Flutter starter project demonstrating fundamental concepts of Flutter application development, including stateful widgets, Material Design, and cross-platform support.

## Features

- Counter demo with reactive state management using `setState()`
- Material Design UI with AppBar, floating action button, and themed components
- Cross-platform support: Android, iOS, Web, Linux, macOS, and Windows

## Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (Dart >= 2.19.5)
- An IDE with Flutter support (VS Code, Android Studio, or IntelliJ)

## Getting Started

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd flutter_starter_project
   ```

2. Install dependencies:

   ```bash
   flutter pub get
   ```

3. Run the app:

   ```bash
   flutter run
   ```

## Running Tests

```bash
flutter test
```

## Project Structure

```
lib/
  main.dart          # App entry point, root widget, and home page
test/
  widget_test.dart   # Widget tests for counter functionality
```

## Building for Production

```bash
# Android
flutter build apk

# iOS
flutter build ios

# Web
flutter build web

# Desktop (Linux, macOS, Windows)
flutter build linux
flutter build macos
flutter build windows
```

## Resources

- [Flutter Documentation](https://docs.flutter.dev/)
- [Write Your First Flutter App](https://docs.flutter.dev/get-started/codelab)
- [Flutter Cookbook](https://docs.flutter.dev/cookbook)
- [Dart Language Tour](https://dart.dev/language)
