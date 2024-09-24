# Prodigy InfoTech Internship: Android Development Task

Welcome to the Prodigy InfoTech Internship repository! This repository documents Task 5 of the internship, which focuses on building a QR Code Scanner app for Android.

## Task Overview

The objective of this task is to develop a QR Code Scanner app for Android using Android Studio and Google’s ML Kit Barcode Scanning API. The app will:
- **Scan QR Codes** in real-time using the device's camera.
- **Leverage ML Kit** for accurate and efficient QR code detection.
- **Include a Simple and Clean UI** for ease of use.
- **Handle Camera Permissions** to ensure user privacy and app functionality.

## Features

- **Real-time QR Code Scanning**: Uses the camera to scan QR codes in real-time.
- **ML Kit Integration**: Utilizes Google’s ML Kit Barcode Scanning API for efficient and accurate QR code detection.
- **Simple and Clean UI**: A straightforward user interface designed for ease of use.
- **Permission Handling**: Manages camera permissions to ensure user privacy and app functionality.

## Prerequisites

- **Android Studio**: 4.0 or higher
- **Minimum SDK Version**: 21
- **Target SDK Version**: 31

## Steps

1. **Setup Project**:
   - Create a new Android project in Android Studio.
   - Configure project settings including project name, package name, and target SDK.

2. **Integrate Dependencies**:
   - Add ML Kit Barcode Scanning API and Camera2 API dependencies to your `build.gradle` file.
   - Ensure the necessary permissions are included in the `AndroidManifest.xml` file.

3. **Design UI**:
   - Implement the user interface using XML to create a layout for the QR code scanner.
   - Include a `SurfaceView` or `TextureView` to display the camera preview and an overlay for scanning QR codes.

4. **Implement QR Code Scanning**:
   - Set up the Camera2 API to capture images from the device's camera.
   - Integrate ML Kit’s Barcode Scanning API to process and decode QR codes.
   - Implement logic to handle camera permissions and manage QR code scanning in real-time.

5. **Handle Permissions**:
   - Request camera permissions at runtime to ensure that the app can access the device's camera.
   - Implement logic to handle cases where permissions are denied or not granted.

6. **Build & Run**:
   - Compile the app using Android Studio and resolve any build issues.
   - Test the app on an Android device or emulator to ensure it operates as expected.
   - Verify that all functionalities work correctly and that the app handles user input gracefully.

## Knowledge Gained

- **Android Application Development**:
  - Gained practical experience in setting up and managing an Android app project.
  - Learned how to use Android Studio for development and debugging.

- **Camera Integration**:
  - Acquired skills in using the Camera2 API for capturing images and managing camera functionality.
  - Implemented real-time QR code scanning with the device’s camera.

- **ML Kit Integration**:
  - Integrated Google’s ML Kit Barcode Scanning API for efficient and accurate QR code detection.
  - Developed logic to process and decode QR codes using machine learning capabilities.

- **UI Design**:
  - Designed a simple and clean user interface for the QR code scanner.
  - Implemented layouts using XML to create a user-friendly scanning experience.

- **Permission Handling**:
  - Managed camera permissions to ensure app functionality and user privacy.
  - Implemented runtime permission requests and handled different permission scenarios.

## Summary

This task involved the development of a QR Code Scanner app for Android, covering the following aspects:
- **Project Setup**: Configured and initialized an Android project.
- **Dependency Integration**: Added ML Kit and Camera2 API dependencies.
- **UI Design**: Designed and implemented a user-friendly interface for the QR code scanner using XML.
- **QR Code Scanning Implementation**: Developed core functionality to scan and decode QR codes in real-time.
- **Permission Handling**: Implemented runtime permission requests and managed camera access.

The app’s functionality is verified through its ability to accurately scan QR codes and handle camera permissions effectively.

## Conclusion

The task successfully demonstrated the fundamental steps required to build a QR Code Scanner app for Android, including:
- Effective integration of camera and ML Kit functionalities.
- Development of a user-friendly interface for scanning QR codes.
- Handling of runtime permissions and ensuring app reliability.

