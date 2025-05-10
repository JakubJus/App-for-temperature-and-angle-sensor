# 📱 IMU Measurement App (Android - Jetpack Compose)

This Android app connects to a Bluetooth Low Energy (BLE) IMU device (like the Seeed XIAO nRF52840 Sense), streams real-time accelerometer and gyroscope data, visualizes it in interactive graphs, and stores it in Firebase. Users can view past sessions via a calendar interface and plan future measurements.

---

## ✨ Features

- 📶 Connect to BLE IMU device
- 📈 Real-time graphing of 6-axis motion data (Accel & Gyro)
- ☁️ Firebase integration (store and retrieve sessions)
- 📅 Calendar view to navigate past measurements
- 📋 Schedule upcoming measurement sessions
- 👤 Profile page (currently under development)

---

## 🛠 Built With

- **Jetpack Compose** (UI)
- **Kotlin**
- **Bluetooth Low Energy (BLE) APIs**
- **Firebase Realtime Database / Firestore**
- **MPAndroidChart** or equivalent (for plotting)

---

## 🔧 Setup Instructions

### 1. Prerequisites

- Android Studio Giraffe or newer
- Android device with BLE support (recommended Android 10+)
- Firebase project with Firestore or Realtime Database

### 2. Clone the Repository

```bash
git clone https://github.com/JakubJus/App-for-temperature-and-angle-sensor/tree/main/App.git
cd newble
