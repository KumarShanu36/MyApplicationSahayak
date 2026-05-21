<div align="center">

# 🚀 Sahayak — Mutual Aid Platform

### Native Android Application for Campus Peer-to-Peer Resource Sharing

<img src="https://img.shields.io/badge/Platform-Android-green?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Language-Kotlin-blue?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Architecture-MVVM-orange?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Database-Firebase-yellow?style=for-the-badge"/>
<img src="https://img.shields.io/badge/UI-Material%20Design%203-purple?style=for-the-badge"/>

### Empowering Campus Communities Through Smart Resource Sharing

A scalable Native Android application designed to help students share academic resources such as books, lab equipment, notes, and study materials through a decentralized peer-to-peer ecosystem.

</div>

---

# 📌 Overview

**Sahayak** is an enterprise-grade Android application developed to bridge the gap between students who need academic resources and those willing to help.

The platform creates a smart, lightweight, and highly intuitive mutual-aid ecosystem inside university campuses by enabling students to:

- 📚 Request Books & Study Materials
- 🧪 Share Lab Equipment
- 📝 Exchange Notes & Resources
- 🔔 Receive Real-Time Notifications
- 📊 Track Activity Logs
- 🌙 Experience Dynamic Light/Dark Mode

This project focuses on:
- Community-driven collaboration
- Financial accessibility
- Sustainable academic resource utilization
- Modern Android architecture principles

---

# ✨ Key Features

## 🔐 Authentication System
- Secure Login & Registration
- Campus-based user onboarding
- User profile management

## 📢 Help Request System
- Create and publish help requests
- Add descriptions, categories, urgency levels
- Attach media support

## 🤝 Offer Help Module
- View all active requests
- Respond to resource requests
- RecyclerView optimized listing system

## 🔔 Real-Time Notifications
- Instant confirmation alerts
- Android Notification Channels support
- Foreground broadcast integration

## 🌙 Dynamic Theme Engine
- Light/Dark mode switching
- Runtime UI adaptation
- Material Design 3 compliance

## 📜 Activity Tracking
- Transaction history logs
- Campus contribution records
- Status-based request tracking

---

# 🏗️ System Architecture

## MVVM Architecture

The project follows a clean and scalable **Model-View-ViewModel (MVVM)** architecture to ensure:

- Better maintainability
- Modular development
- Separation of concerns
- Efficient state management
- Enhanced scalability

---

# 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Kotlin | Native Android Development |
| Firebase Firestore | Real-Time Database |
| Material Design 3 | Modern UI Components |
| RecyclerView | Optimized Dynamic Lists |
| View Binding | Safe UI Binding |
| Android Jetpack | Core Android Architecture |
| Notification Channels | Real-Time Alerts |
| Git & GitHub | Version Control |

---

# 📱 Application Modules

## 1️⃣ Client Interface & Presentation Layer
- Splash Screen System
- Login & Registration
- Dashboard Navigation
- Dynamic Theme Rendering

## 2️⃣ View Rendering Engine
- RecyclerView Optimization
- Custom Adapter Pipeline
- Efficient View Recycling
- Dynamic Data Population

## 3️⃣ Alert & Notification Engine
- Push Notifications
- Foreground Broadcast Handling
- Transaction Confirmation Alerts

---

# 📂 Project Structure

```bash
Sahayak-MutualAid-Platform/
│
├── app/
│   ├── activities/
│   ├── adapters/
│   ├── models/
│   ├── notifications/
│   ├── utils/
│   └── firebase/
│
├── res/
│   ├── layout/
│   ├── drawable/
│   ├── values/
│   └── mipmap/
│
├── screenshots/
├── README.md
└── build.gradle
