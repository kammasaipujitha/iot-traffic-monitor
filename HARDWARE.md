# Hardware Components for IoT-Based Traffic Monitoring System

## 🎯 Purpose
This file lists all the hardware components required to build and test the IoT-based traffic monitoring system using Raspberry Pi and Deep Learning.

---

## 🧠 Core Components

| Component | Description | Purpose |
|------------|-------------|----------|
| **Raspberry Pi 4 Model B (2GB/4GB RAM)** | Single-board computer with Wi-Fi and USB ports | Acts as the main IoT edge device to process and send camera data |
| **Raspberry Pi Camera Module v2 (or USB Webcam)** | 8MP camera with CSI interface | Captures real-time traffic images and videos |
| **MicroSD Card (32GB or higher)** | Storage for Raspberry Pi OS and project files | Stores operating system, scripts, and local data |
| **Power Supply (5V 3A)** | Official Raspberry Pi adapter or power bank | Provides stable power to the Raspberry Pi |
| **Wi-Fi Network** | Local wireless connection | Enables the Pi to communicate with the MQTT broker/server |
| **Laptop or Desktop Server** | Acts as a receiver for MQTT messages and runs the deep learning model | Used to store, analyze, and visualize the data |

---

## ⚙️ Optional Sensors (for Advanced Features)
| Sensor | Purpose |
|---------|----------|
| **Ultrasonic Sensor (HC-SR04)** | Detects object distance — can help count vehicles physically |
| **IR Sensor Module** | Detects vehicle presence on specific lanes |
| **Temperature Sensor (DHT11)** | For collecting environmental data (optional for paper’s IoT expansion) |

---

## 🧩 Connectivity & Cables
- HDMI cable (for setup and debugging)
- USB keyboard and mouse (for initial Pi setup)
- Ethernet cable (optional if Wi-Fi is unstable)
- Camera ribbon cable (if using official Pi Camera)

---

## 🧰 Notes
- The Raspberry Pi 4 can run lightweight deep learning models (like YOLOv5n or MobileNet).
- If high performance is needed, the Pi will act as a data-capturing device and send images to a cloud or laptop for processing.
- Total approximate cost: ₹8,000 – ₹10,000 (complete setup).

---

## ✅ Hardware Setup Goal for Step 1
- Raspberry Pi boots successfully.  
- Camera connected and captures one frame.  
- Pi sends a sample MQTT message to the server.  
- Verification photo (`frame.jpg`) is saved in the repo.
