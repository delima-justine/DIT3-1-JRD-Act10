# Cross-Platform To-Do List App

A simple, cross-platform to-do list application built with Flutter that runs from a single shared codebase.

## Features

✅ **Add Tasks** - Create new to-do items with descriptions  
✅ **Mark Complete** - Toggle tasks as completed/incomplete  
✅ **Delete Tasks** - Remove tasks from the list  
✅ **Clean UI** - Modern Material Design interface  
✅ **Cross-Platform** - Runs on Android, iOS, Web, Windows, macOS, and Linux from one codebase

## Supported Platforms

- 📱 Android
- 🍎 iOS
- 🌐 Web
- 🪟 Windows
- 🍏 macOS
- 🐧 Linux

## Getting Started

### Prerequisites

- Flutter SDK (3.10.7 or higher)
- For mobile development: Android Studio or Xcode
- For web: Chrome browser

### Installation

1. Clone this repository
2. Navigate to the project directory
3. Get dependencies:
   ```bash
   flutter pub get
   ```

### Running the App

**On Android/iOS (with device/emulator connected):**
```bash
flutter run
```

**On Web:**
```bash
flutter run -d chrome
```

**On Windows:**
```bash
flutter run -d windows
```

**On macOS:**
```bash
flutter run -d macos
```

**On Linux:**
```bash
flutter run -d linux
```

## How to Use

1. **Add a Task**: Tap the floating "+" button and enter your task description
2. **Complete a Task**: Tap the checkbox next to a task to mark it as complete
3. **Delete a Task**: Tap the red trash icon to remove a task

## Project Structure

```
lib/
  └── main.dart          # Main application code with TodoItem model and UI
```

## Technologies Used

- **Flutter** - UI framework for cross-platform development
- **Material Design 3** - Modern design system
- **Dart** - Programming language

## License

This project is part of Activity 10 - Mobile Application Development
