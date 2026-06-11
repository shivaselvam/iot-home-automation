# 🏠 IoT Based Home Automation
### Arduino + ESP8266 + Mobile App | Smart Home Control System

![Status](https://img.shields.io/badge/Status-Completed-00C853?style=for-the-badge)
![Hardware](https://img.shields.io/badge/Hardware-Arduino%20%7C%20ESP8266-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![Protocol](https://img.shields.io/badge/Protocol-MQTT%20%7C%20WiFi-0078D4?style=for-the-badge)

---

## 📌 Overview

A **mobile-controlled smart home automation system** that allows users to remotely control home appliances via IoT. Built using Arduino and ESP8266, the system connects home devices to the internet and enables real-time control through a mobile app.

---

## ✨ Features

- 📱 **Mobile app control** — control appliances from anywhere
- 💡 **Light control** — ON/OFF and dimming
- ❄️ **Fan control** — speed regulation via PWM
- 🔌 **Multi-appliance support** — up to 4 devices per module
- 🌡️ **Sensor monitoring** — temperature and humidity display
- ⏰ **Scheduling** — timer-based automation
- 🔔 **Status feedback** — real-time appliance status on app

---

## 🛠️ Hardware Components

| Component | Purpose | Quantity |
|---|---|---|
| Arduino Uno | Main controller | 1 |
| ESP8266 (NodeMCU) | WiFi connectivity | 1 |
| Relay Module (4-channel) | Appliance switching | 1 |
| DHT11 Sensor | Temperature & humidity | 1 |
| PIR Motion Sensor | Occupancy detection | 1 |
| 5V Power Supply | System power | 1 |

---

## 🔌 System Architecture

```
Mobile App (Blynk / MIT App Inventor)
          ↓ (WiFi / MQTT)
    ESP8266 (NodeMCU)
          ↓ (Serial)
      Arduino Uno
          ↓
  Relay Module (x4)
    ↓    ↓    ↓    ↓
 Light Fan  AC  Other
```

---

## 💻 Software & Platforms

| Tool | Purpose |
|---|---|
| Arduino IDE | Firmware development |
| Blynk Platform | Mobile app & cloud |
| MQTT Protocol | IoT messaging |
| ESP8266 WiFi Library | Network connectivity |
| DHT Library | Sensor interfacing |

---

## 🚀 Setup Instructions

1. Install **Arduino IDE** and required libraries
2. Flash ESP8266 with WiFi credentials
3. Upload Arduino sketch with relay control logic
4. Set up **Blynk app** and get auth token
5. Wire relay module to appliances
6. Power on and test via mobile app

---

## 📊 Project Outcome

- Successfully automated 4 home appliances
- Remote control from any location via internet
- Reduced manual switching by 100%
- Foundation for further IoT project development

---

## 👨‍💻 Developer

**Sivaselvam P** — IoT & Embedded Systems Engineer  
📧 psivaselvam2@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/sivaselvam-p-976097192/)
