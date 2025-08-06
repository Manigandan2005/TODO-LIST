# Todo Task Management App

A cross-platform mobile application built using **Flutter** that helps users manage personal tasks efficiently on the go. This project is a part of a hackathon run by [https://www.katomaran.com](https://www.katomaran.com).

---

## 🚀 Features

- 🔐 **Google Authentication** via Firebase
- ✅ **Full CRUD Support** for managing tasks
- 📅 Task fields include:
  - Title
  - Description
  - Due Date
  - Status (Open/Complete)
  - Priority (Low/Medium/High)
- 💾 Tasks stored locally in session using provider-based state management
- 🔍 Search and filter capabilities
- ✨ Smooth animations for task list interactions
- 🧹 Swipe to delete & Pull-to-refresh
- 📱 Intuitive, responsive UI for both Android and iOS
- 🚨 Crash reporting via **Firebase Crashlytics**

---

## 📲 APK Download

👉 [Download APK here](https://your-apk-link.com)  
_Use an Android device to install._

---

## 🏗️ Architecture Diagram

![Architecture Diagram](https://your-image-upload-url.com/architecture.png)

> Assumes:
> - Internet connection is required for login
> - All tasks are stored in memory only (offline session, not persisted)
> - One social login provider (Google) is sufficient
> - Backend/API integration is skipped as per instructions (local-only CRUD)

---

## 🔧 Tech Stack

| Layer            |    Technology                     |
|---------------   |--------------------               |
| Frontend         |    Flutter                        |
| Authentication   |    Firebase Auth (Google Sign-In) |
| Crash Reporting  |    Firebase Crashlytics           |
| State Management |    Provider                       |
| Animations       |    Flutter’s built-in transitions |

---
lib/
├── main.dart
├── models/
│ └── task.dart
├── screens/
│ ├── login_screen.dart
│ ├── home_screen.dart
│ └── task_detail_screen.dart
├── widgets/
│ ├── task_tile.dart
│ └── task_form.dart
├── services/
│ └── auth_service.dart
└── providers/
└── task_provider.dart

---

## 🧪 How to Run the App

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/todo-task-app.git
   cd todo-task-app
Install dependencies:

bash

flutter pub get
Run the app on emulator or device:

bash

flutter run
To build the APK:

bash

flutter build apk --release
🎥 Demo Video
🎦 Watch the demo on Loom

📌 Assumptions
Google login is sufficient for demonstration.

All data is stored in local memory (session-based).

There is no backend; all task logic is handled on-device.

User must be online to authenticate but can use the app offline after that.

One Firebase project is used for Auth & Crashlytics.

🧑‍💻 Developer Setup Instructions
Make sure you have Flutter and Dart installed.

bash

flutter doctor
Then follow the steps under "How to Run the App".

For Firebase:

Add your google-services.json file to android/app/

Enable Google Sign-In and Crashlytics in Firebase Console.

✅ Checklist
 Google Authentication

 CRUD on tasks

 Swipe to delete, Pull-to-refresh

 Clean UI with smooth transitions

 Firebase Crashlytics integrated

 APK attached

 Architecture diagram included

 Loom video included

 Assumptions documented

🏁 This project is a part of a hackathon run by https://www.katomaran.com
markdown

---

## ✅ What You Still Need to Do

- Replace placeholders like:
  - `your-apk-link.com`
  - `your-image-upload-url.com`
  - `yourusername`
  - `your-video-link`
- Make sure your Firebase project is correctly set up
- Push your code to a **public GitHub repository**
- Test APK on devices for release version

If you want help generating the architecture diagram or a sample UI, let me know!

## 📂 Project Structure

