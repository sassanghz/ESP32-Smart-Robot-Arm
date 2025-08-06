# 🤖 ESP32-Based Smart Robot Arm

A 4-DOF smart robotic arm powered by the ESP32 microcontroller. This project combines mechanical design, wireless control (Bluetooth & Wi-Fi), and IoT technologies for real-time manipulation via a mobile app or browser-based interface.

---

## 📸 Demo

<img src="images/full_setup.jpg" width="400"/> <img src="images/mobile_control.png" width="400"/>

---

## 🛠 Features

- 🔧 4 Degrees of Freedom (base, shoulder, elbow, gripper)
- 📱 Wireless Control via Bluetooth and Wi-Fi
- 🌐 Web-based GUI for real-time servo control
- ⚙️ Custom mobile app interface (MIT App Inventor)
- 📦 Arduino-compatible and open-source

---

## 🧰 Hardware Components

| Component             | Quantity | Description                            |
|-----------------------|----------|----------------------------------------|
| ESP32 Dev Board       | 1        | Keyestudio ESP32                        |
| SG90 Servo Motors     | 4        | For joint control                      |
| Acrylic Arm Frame     | 1        | Custom or kit-based                     |
| Power Supply (USB/5V) | 1        | External or battery powered            |
| Smartphone            | 1        | For control interface (Bluetooth/Wi-Fi)|

---

## 💻 Software Stack

- **Arduino IDE** (with ESP32 board support)
- **MIT App Inventor** (Bluetooth control app)
- **HTML/CSS/JS** (Web interface via ESP32 server)
- **Libraries:**
  - `WiFi.h`
  - `WebServer.h`
  - `ESP32Servo.h`

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/esp32-robot-arm.git
cd esp32-robot-arm
