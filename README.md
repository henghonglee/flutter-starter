# Flutter Starter Project

A Flutter starter template demonstrating a simple counter application with Material Design. Supports Android, iOS, Web, Linux, macOS, and Windows.

## Features

- Material Design UI with theming
- Stateful widget pattern with `setState()` for state management
- Cross-platform support (Android, iOS, Web, Linux, macOS, Windows)
- Widget testing example

## Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install)
- Platform-specific tooling (e.g., Android SDK, Xcode, Chrome)

## Getting Started

```bash
# Install dependencies
flutter pub get

# Run the app
flutter run

# Run on a specific platform
flutter run -d chrome
flutter run -d macos
```

## Running Tests

```bash
flutter test
```

## Project Structure

```
lib/
└── main.dart          # App entry point, home page, and counter logic
test/
└── widget_test.dart   # Widget tests for the counter UI
```

## Building

```bash
flutter build apk      # Android
flutter build ios       # iOS
flutter build web       # Web
flutter build linux     # Linux
flutter build macos     # macOS
flutter build windows   # Windows
```
