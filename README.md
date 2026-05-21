# Flutter Starter Project

A Flutter starter project with a simple counter demo app, scaffolded for cross-platform development.

## Features

- Counter demo with increment functionality
- Material Design UI with blue theme
- Cross-platform support (Android, iOS, Web, Linux, macOS, Windows)

## Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (>=2.19.5 <3.0.0)

## Getting Started

```bash
# Install dependencies
flutter pub get

# Run the app
flutter run

# Run on a specific platform
flutter run -d chrome    # Web
flutter run -d android   # Android
flutter run -d ios       # iOS
```

## Running Tests

```bash
flutter test
```

## Project Structure

```
lib/
  main.dart       # App entry point, home page with counter
test/
  widget_test.dart # Widget tests for the counter
```
