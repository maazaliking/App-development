# Mobile Gallery App

A Flutter-based mobile gallery application that allows users to capture, store, and view images.

## Getting Started

This project is a Flutter application that implements a simple gallery with camera integration.

### Prerequisites

- Flutter SDK
- Android Studio or VS Code
- Android SDK for Android development
- Xcode for iOS development (Mac only)

### Installation

1. Clone the repository
2. Run `flutter pub get` to install dependencies
3. Run `flutter run` to start the app

## Features

- Capture images using device camera
- Pick images from device gallery
- View images in a grid layout
- Modern Material Design UI
- Local storage support

## Building

To build the release version:

For Android:
```bash
flutter build apk --release
```

For iOS:
```bash
flutter build ios --release
```

## Dependencies

- image_picker: For capturing and picking images
- path_provider: For accessing device storage
- permission_handler: For handling device permissions
