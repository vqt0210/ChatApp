# 📱 ChatApp

A minimal real-time chat application built with **Flutter** and **Firebase**.  
This app allows users to send and receive messages in real time using Firebase Authentication and Cloud Firestore.

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- Dart (comes with Flutter)
- Android Studio or VS Code (with Flutter and Dart plugins)
- Firebase account ([Firebase Console](https://console.firebase.google.com/))

Verify your Flutter installation:

```bash
flutter doctor
```

### 🔥 Firebase Configuration

```bash
npm install -g firebase-tools
```
- Download the google-services.json file if using android
- Place it inside your Flutter project at:
```bash
android/app/google-services.json
```
- Download the GoogleService-Info.plist file if using ios
```bash
ios/Runner/GoogleService-Info.plist
```

### 📦 Installing Dependencies & ▶️ Running the App
```bash
git clone https://github.com/vqt0210/chatapp.git
```
```bash
cd chatapp
flutter pub get
flutter run
```


