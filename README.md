# 📐 Asude Matematik — Kotlin Multiplatform App

> 🔒 **The source code of this project is private.** This repository is a public showcase. Code walkthroughs are available on request.

A cross-platform mobile application built for a primary school mathematics teacher, helping her manage students, share content and stay in touch with families — on both **Android** and **iOS** from a single Kotlin codebase.

## ✨ Features

- 📅 **Appointment scheduling** between the teacher and students/parents
- 💬 **Real-time messaging**
- 🎮 **Interactive math games** for students
- 🔔 **Push notifications** with Firebase Cloud Messaging
- 🎛️ **Teacher-controlled feature toggles** — features can be enabled/disabled dynamically without an app update
- 👩‍🏫 Student & content tracking

## 🛠️ Tech Stack

| Area | Technologies |
|---|---|
| Platform | Kotlin Multiplatform (Android & iOS), Compose Multiplatform |
| Backend | Firebase — Firestore, Authentication, Cloud Messaging (FCM), Storage |
| Architecture | MVVM, shared business logic in `commonMain` |
| Language | Kotlin |

## 🏗️ Project Structure

```
composeApp/
 ├── commonMain/   → shared UI & business logic (Android + iOS)
 ├── androidMain/  → Android-specific code
 └── iosMain/      → iOS-specific code
iosApp/            → iOS entry point
```

## 📬 Contact

Interested in the code or a demo? Reach me on [LinkedIn](https://www.linkedin.com/in/mehmetfurkaneroglu) or at mehmetfurkaneroglu@hotmail.com.
