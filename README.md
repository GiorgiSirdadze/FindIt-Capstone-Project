# FindIt – Lost & Found Android Application

FindIt is an Android application developed as a bachelor thesis project at Kutaisi International University.  
The application provides a secure and organized digital platform for reporting, locating, and returning lost or found items within a university campus environment.

Instead of relying on unstructured social media posts or notice boards, FindIt offers a dedicated mobile solution with real-time communication and location-based features.

---

## Project Motivation

In university life, students constantly move between buildings, classrooms, dormitories, and shared spaces.  
As a result, personal belongings such as wallets, phones, keys, or ID cards are often misplaced.
# 📱 FindIt – Lost & Found Android Application

FindIt is an Android application developed as a bachelor thesis project at **Kutaisi International University**.  
It provides a secure and organized digital platform for reporting, locating, and returning lost or found items within a university campus.

Instead of relying on unstructured social media posts or notice boards, FindIt offers a dedicated mobile solution with real-time communication and location-based features.

---

## 🎯 Project Motivation

In university life, students constantly move between buildings, classrooms, dormitories, and shared spaces.  
As a result, personal belongings such as wallets, phones, keys, or ID cards are often misplaced.

At the same time, people who find lost items usually have no safe and structured way to contact the owner without exposing private information.

✅ FindIt was created to solve this everyday problem by providing:

- structured item reporting
- authenticated users
- location-based visualization
- secure in-app communication

---

## ✨ Core Features

- 🔐 Secure login and registration using Firebase Authentication
- 📝 Create lost or found posts with description, image, and item type
- 📍 Add location details and view posts on an interactive map
- 🗺️ Marker clustering for better performance in crowded areas
- 💬 Real-time chat between users without exposing contact information
- 🔎 Search and filtering functionality on the home screen
- 👤 Profile management (edit profile, logout, language switching)
- 🌍 Language support (English / Georgian)

---

## 🏗️ Architecture and Design

The application follows **Clean Architecture** with a single-module structure:

- **Data Layer** – Firebase repositories and data mapping
- **Domain Layer** – Use cases and business logic
- **Presentation Layer** – UI screens and ViewModels

The presentation layer is implemented using the **MVI (Model–View–Intent)** pattern, ensuring predictable state management and clear separation between:

- UI events
- state updates
- side effects

---

## 🛠️ Technologies Used

- 🟣 Kotlin
- 📐 Android XML + ConstraintLayout
- 🔥 Firebase Authentication
- 🗄️ Firebase Firestore Database
- 🖼️ Firebase Storage
- 🗺️ Google Maps SDK
- ⚡ Coroutines + Flow
- 💉 Hilt Dependency Injection
- 💾 DataStore (language persistence)

---

## 🧪 Testing

Basic unit testing was performed mainly on ViewModels in the presentation layer, including:

- ✅ Registration form validation
- ✅ Login form state testing
- ✅ Home screen post loading logic

Testing tools used:

- 🧾 JUnit
- 🎭 MockK
- 🧪 Mockito
- ⏱️ Kotlin Coroutines Test

---

## 📊 User Feedback

The application was tested by several university students using an APK version.  
Feedback was collected through a Google Form.

Most responses were positive, especially regarding:

- 🗺️ Map-based post visualization
- 💬 Built-in chat system

Suggested improvements included:

- 🎨 UI refinements
- 🔔 Notification support

---

## 🚀 Future Improvements

Possible extensions of FindIt include:

- 🔔 Push notifications for new matching posts
- 🛡️ Moderation or admin support for content verification
- 🔎 More advanced filtering options
- 📡 Offline support and performance optimization
- 🌍 Expansion to multiple campuses

---

## 📂 Repository

This repository contains the full implementation of the FindIt application, including:

- architecture
- UI
- Firebase integration
- map + chat features
- core lost & found functionality

---

## 📜 License

This project was developed for educational purposes as part of a bachelor thesis.
