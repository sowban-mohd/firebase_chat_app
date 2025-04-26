# Firebase Chat App

A simple Flutter chat application using **Firebase Firestore** for real-time messaging.

> **Note**: This project requires Firebase setup. It won't work until you connect your own Firebase project.

## Features
- Real-time chat powered by Firebase Firestore
- Basic chat UI with message sending and receiving
- Multi-platform support (Android, iOS, Web, macOS)

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/sowban-mohd/firebase_chat_app.git
   ```

2. Install dependencies:
   ```
   flutter pub get
   ```

3. Set up Firebase:
   - Create a Firebase project.
   - Add your app (Android/iOS/Web).
   - Download `google-services.json` (Android) or `GoogleService-Info.plist` (iOS) and place them in the respective folders.
   - Enable Firestore in the Firebase console.

4. Run the app:
   ```bash
   flutter run
   ```

## Tech Stack
- Flutter
- Firebase Firestore
- Dart
