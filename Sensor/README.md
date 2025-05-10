# BLE IMU Device - XIAO nRF52840 Sense + LSM6DS3

This project streams real-time accelerometer and gyroscope data over **Bluetooth Low Energy (BLE)** using a **Seeed Studio XIAO nRF52840 Sense** and an **LSM6DS3 IMU** sensor. It transmits 6-axis motion data (Accel + Gyro) at 50Hz to a BLE central device such as a smartphone or PC.

## 📦 Features

- Bluetooth LE advertisement and data streaming
- Sends data as comma-separated values: `accelX, accelY, accelZ, gyroX, gyroY, gyroZ`
- Uses BLE service UUID `19B10000-E8F2-537E-4F6C-D104768A1214`

---

## 🔧 Hardware Required

- [Seeed Studio XIAO nRF52840 Sense](https://wiki.seeedstudio.com/XIAO_BLE/)
- LSM6DS3 Accelerometer + Gyroscope sensor (I2C)
- Breadboard and jumper wires
- Micro USB cable

---

## 💻 Setup Instructions

### 1. Install Arduino IDE & Board Support
- Install [Arduino IDE](https://www.arduino.cc/en/software)
- Go to **Preferences** and add this URL to "Additional Board URLs": https://files.seeedstudio.com/arduino/package_seeeduino_boards_index.json, follow the guide on [Seeed Studio XIAO nRF52840 Sense Setup](https://wiki.seeedstudio.com/XIAO_BLE/)
