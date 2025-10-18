# 💬 ChatApp

A modern real-time chat application built with **Kotlin** and **Jetpack Compose** for Android.  
This app demonstrates clean architecture, API integration, and an intuitive chat UI — similar to ChatGPT-style conversations.

---

## 🚀 Overview

**ChatApp** allows users to send and receive real-time messages through an integrated backend API.  
It showcases how to build a smooth and responsive chat interface using **XML**, **Retrofit**, and **ViewModel (MVVM)** architecture.

---

## ✨ Features

- 🗨️ Real-time chat messaging  
- 💎 XLM ui 
- 🧠 Smart bot response system (via API integration)  
- 🕒 Message timestamps  
- 🗂️ Local chat history storage using Room Database  
- ⚡ Asynchronous API calls using Retrofit + Coroutines  
- 🔄 Conversation sync with backend  
- 📱 Responsive layout for all screen sizes  

---

## 🧰 Tech Stack

| Category | Technology |
|-----------|-------------|
| **Language** | Kotlin |
| **UI Toolkit** | XML |
| **Architecture** | MVVM (Model-View-ViewModel) |
| **Networking** | Retrofit |
| **Database** | Room Database | FireBase
| **Asynchronous Handling** | Kotlin Coroutines |
| **Build System** | Gradle (Kotlin DSL) |

---

## 📂 Project Structure

ChatApp/
│
├── app/
│ ├── java/com/example/chatapp/
│ │ ├── data/ # Data layer (models, API service, DAO)
│ │ ├── ui/ # Jetpack Compose UI components
│ │ ├── viewmodel/ # ChatViewModel for managing chat logic
│ │ └── utils/ # Helper classes and extensions
│ │
│ └── res/ # Layouts, drawables, and other resources
│
├── build.gradle.kts
├── settings.gradle.kts
└── README.md


---

## ⚙️ Getting Started

### 🔹 Prerequisites
Make sure you have the following installed:
- Android Studio (latest stable version)
- JDK 17 or above
- Android SDK 33+
- Internet connection for API access

### 🔹 Installation

1. Clone the repository  
   ```bash
   git clone https://github.com/AyushTurak/ChatApp.git
   cd ChatApp
🖼️ Screenshots

Splash Screen :- 
<img width="381" height="812" alt="image" src="https://github.com/user-attachments/assets/b6cb59e0-e519-4bfa-a805-a9bde460f60d" />

Login Screen:-
<img width="336" height="698" alt="image" src="https://github.com/user-attachments/assets/438273fa-b1d6-4db0-b6d8-a5d8d3f9fb77" />

SignUp Screen:-
<img width="396" height="812" alt="image" src="https://github.com/user-attachments/assets/ac80e07e-ecf4-46ca-b109-7c353a45d2bd" />

ChatScreen:-
<img width="400" height="813" alt="image" src="https://github.com/user-attachments/assets/4e24a9a4-9257-4e1a-96bb-f2d612494446" />

🧑‍💻 Contributing

Contributions are welcome!
To contribute:

Fork the project

Create a new branch

git checkout -b feature/YourFeature


Commit your changes

git commit -m "Add your feature"


Push to your fork

git push origin feature/YourFeature


Create a Pull Request 🚀

---

Would you like me to **add badges** (like build status, Kotlin version, license, stars, etc.) at the top of your README for a more professional look?

