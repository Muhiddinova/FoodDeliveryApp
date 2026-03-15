# 🍔 Food Delivery App

Modern Android food delivery application that allows users to browse restaurants, choose meals, add them to cart and place orders easily.

The project demonstrates modern Android development practices using scalable architecture and clean code principles.

---

## 🏗 **Architecture**

The project follows **MVVM (Model – View – ViewModel)** architecture.

Data flow:

UI → ViewModel → Repository → API / Local Storage → UI

This architecture helps to keep the project modular, maintainable and easy to test.

---

## ⚙️ **Tech Stack**

### 📱 Core
- Kotlin
- MVVM Architecture
- Coroutines & Flow

### 🌐 Networking
- Retrofit
- OkHttp
- REST API

### 💾 Database
- Room Database
- SharedPreferences

### 🎨 UI
- Jetpack Compose
- Navigation Component

### 🛠 Tools
- Android Studio
- Git & GitHub
- Gradle

---

## 🍟 **Features**

✔ Browse restaurants and food menu  
✔ View food details  
✔ Add products to cart  
✔ Create food orders  
✔ User authentication  
✔ View restaurant branches  
✔ Order history tracking  

---

## 📂 **Project Structure**

app
│
├── presentation → UI layer (Screens, ViewModels)
├── domain → Business logic
├── data → API + Repository implementation
└── di → Dependency Injection modules
