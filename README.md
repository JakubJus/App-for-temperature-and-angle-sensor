# App-and-hardware-for-temperature-and-angle-sensor

This project consists of two components:

1. 🧠 **Sensor Firmware (Hardware)**  
   Arduino-based firmware running on a **Seeed Studio XIAO nRF52840 Sense** that measures **temperature, acceleration, and gyroscope data**, and transmits it via **Bluetooth Low Energy (BLE)**.

2. 📱 **Android App (Software)**  
   An Android application built with **Jetpack Compose** that connects to the BLE device, visualizes sensor data in real-time, and saves sessions to **Firebase** for later viewing.

---

## 📦 Repository Structure

```
App-and-hardware-for-temperature-and-angle-sensor/
├── sensor/       # Arduino firmware for the XIAO nRF52840 BLE IMU
├── app/          # Android app to connect, visualize, and store data
└── README.md     # This file
```

---

## ⚙️ How to Set It Up

### 🔧 Hardware Setup

To set up the **BLE sensor firmware**, visit the [`sensor/`](sensor/) folder and follow the instructions in the [`README.md`](sensor/README.md) inside.

- Connect your XIAO nRF52840 Sense and IMU sensor (LSM6DS3)
- Upload the Arduino sketch
- Power the device

### 💻 Software Setup

To set up the **Android app**, visit the [`app/`](app/) folder and follow the instructions in the [`README.md`](app/README.md).

- Connect to the BLE device
- View real-time graphs
- Save data to Firebase
- View historical sessions and plan future ones

---

## 📋 Summary

| Component | Folder | Technology | Purpose |
|----------|--------|-------------|---------|
| 🔌 Sensor Firmware | `sensor/` | Arduino + BLE + IMU | Streams sensor data via BLE |
| 📲 Android App | `app/` | Jetpack Compose + Firebase | Graphs & stores the data |

---

## 🧪 Sensor Output Example

```
0.01,0.02,9.81,0.05,0.00,0.01,27,8
accelX,accelY,accelZ,gyroX,gyroY,gyroZ,temp
```

---

## 🛠️ Future Work

- Improve user profile section in the app
- Export session as CSV or PDF
- Orientation or tilt visualizer

---

## 📄 License

MIT License – see individual folders for full license details.
