# tourism_app

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
##Overview
 The Tourism App is a Flutter-based smartphone application that lets users manage their dream trip destinations. 

 Development Environment

IDE: IntelliJ was used to create this project.

Instructions to Open and Run the Project

1. Installation Requirements
Ensure you have the following installed on your development environment:

Flutter SDK: Download and install Flutter from the official website.
Dart SDK: Comes bundled with Flutter. Ensure Dart is correctly set up.
Hive: A lightweight and fast key-value database for Flutter.

2. Unzip the folder
3. Add Project Dependencies
Go to your pubspec.yaml file and add the following under dependencies:

dependencies:
  flutter:
    sdk: flutter
  hive: ^2.0.4
  hive_flutter: ^1.1.0
And the following under dev_dependencies:
dev_dependencies:
  flutter_test:
    sdk: flutter
  hive_generator: ^1.1.0
  build_runner: ^2.0.5
Ensure the indentation is correct. After making these changes, run the following command to install the dependencies:

flutter pub get
This will download all the Hive DB dependencies needed for your project.

Step 6: Run Your Flutter App

After ensuring everything is set up correctly, run your Flutter app:

flutter run

Additional Notes
Database Initialization: On first launch, the app will initialize the Hive database. Ensure your device has write permissions.
Error Handling: If you encounter issues, check the console output for error messages and ensure all dependencies are properly installed.


Troubleshooting

Ensure you have the latest versions of Flutter and Dart installed.
