# Flutter Starter Project

A minimal Flutter starter template demonstrating core Flutter concepts including stateful widgets, Material Design, and widget testing. Supports Android, iOS, Web, Linux, macOS, and Windows.

## Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (Dart >= 2.19.5, < 3.0.0)

## Getting Started

```bash
# Install dependencies
flutter pub get

# Run the app
flutter run

# Run on a specific platform
flutter run -d chrome    # Web
flutter run -d macos     # macOS
flutter run -d linux     # Linux
```

## Project Structure

```
lib/
└── main.dart          # App entry point, MyApp and MyHomePage widgets
test/
└── widget_test.dart   # Counter increment smoke test
```

## Running Tests

```bash
flutter test
```

## Dependencies

| Package | Purpose |
|---------|---------|
| `cupertino_icons` | iOS-style icons |
| `flutter_lints` | Recommended lint rules |
