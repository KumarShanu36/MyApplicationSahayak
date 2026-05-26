# 🎓 Sahayak App - LPU Campus Care Connect

[![Kotlin](https://img.shields.io/badge/Kotlin-2.0.21-purple.svg)](https://kotlinlang.org/)
[![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-2024.09.00-blue.svg)](https://developer.android.com/jetpack/compose)
[![Firebase](https://img.shields.io/badge/Firebase-Latest-orange.svg)](https://firebase.google.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 📱 About The App

**Sahayak App** is a campus care connect application designed for **Lovely Professional University (LPU)** students. It enables students to request help, accept help requests, earn credits, and track their contributions in real-time.

## ✨ Features

### 🔐 Authentication
- User Registration with Email & Password
- Secure Login System
- Guest Mode Access
- Email Validation

### 🏠 Dashboard
- Real-time LPU Campus Map (OpenStreetMap)
- Block 1-60 Location Markers
- Auto-rotating Thoughts Section
- Urgent & Basic Need Options
- Statistics Overview (Tasks, Completed, Credits)

### 📢 Request Aid
- Choose Need Type (URGENT/BASIC)
- Add Title & Description
- Select Block Number (1-60)
- Image Upload Support
- Success Popup Confirmation
- Real-time Notifications

### 🤝 Accept Help
- View All Pending Requests
- Accept Request with Details
- Reply to Requester
- Completion Confirmation

### 📋 My Requests
- Track Your Requests
- View Status (Pending/Accepted/Completed)
- View Helper Details
- Mark Task as Completed
- Earn +5 Credits Per Task

### 👤 Profile Management
- View & Edit Profile Details
- Upload Profile Image (Local Storage)
- Display Credits Earned
- Edit Name, Email, Course, Phone

### ⚙️ Settings
- Profile Information Display
- Statistics Overview
- App Information
- Logout Option

### 🔔 Notifications
- Real-time Push Notifications
- Notification Sound
- Unread Count Badge
- Notification History

### 🗺️ LPU Campus Map
- OpenStreetMap Integration
- Block 1-60 Markers
- Request Location Display
- Click Marker to View Block Info

## 🛠️ Tech Stack

| Technology | Version | Purpose |
|------------|---------|---------|
| Kotlin | 2.0.21 | Primary Language |
| Jetpack Compose | 2024.09.00 | UI Framework |
| Firebase Auth | Latest | Authentication |
| Firebase Firestore | Latest | Database |
| Firebase Storage | Latest | Image Storage |
| Firebase Messaging | Latest | Push Notifications |
| OpenStreetMap (OSMDroid) | 6.1.17 | Free Maps |
| Coil | 2.5.0 | Image Loading |
| Material 3 | Latest | UI Components |

## 📂 Project Structure

com.example.myapplicationsahayak/
├── MainActivity.kt # Navigation Controller
├── HelpModels.kt # Data Models & Firebase Logic
├── AppComponents.kt # Splash & Login Screens
├── MainDashboardScreen.kt # Dashboard with Map
├── SeekHelpScreen.kt # Request Aid Screen
├── AcceptHelpScreen.kt # Accept Help Screen
├── MyRequestsScreen.kt # My Requests Screen
├── ProfileScreen.kt # Profile Management
├── SettingsScreen.kt # Settings Screen
└── ui/theme/ # Theme Configuration

## 🚀 Installation

### Prerequisites
- Android Studio Ladybug | 2024.2.1 or later
- JDK 11 or later
- Android SDK API 36
- Firebase Account (for backend)

### Steps to Run

1. **Clone the repository**
```bash
git clone https://github.com/KumarShanu36/MyApplicationSahayak.git
cd MyApplicationSahayak
```
