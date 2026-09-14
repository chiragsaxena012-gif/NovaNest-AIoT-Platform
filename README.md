# NovaNest – AI-Powered Smart IoT Automation Platform

NovaNest is a modular and affordable IoT-based smart automation platform that integrates home automation, security, safety, AI, remote monitoring and long-range communication into a scalable ecosystem.

Built around ESP32-based edge controllers, the system combines sensors, actuators, IoT platforms, AI services and multiple communication methods for connected as well as local operation.

---

## Key Features

- Smart appliance and electrical socket control
- Smartphone and manual control with local override
- ESP32-CAM based face detection and smart door security
- Offline ESP32-based door lock operation
- Google Gemini, Google Assistant and Amazon Alexa integration
- Voice control and voice modulation
- IoT-based plant irrigation and automatic water-pump control
- Smart water-tank monitoring and control
- Automatic pet feeding with scheduling and remote control
- Gas, rain, temperature, humidity and motion monitoring
- Real-time sensor monitoring and Telegram alerts
- LoRa-based long-range communication for rural and agricultural applications
- Modular architecture for smart parking, agriculture and additional IoT modules

---

## Technology Stack

### Hardware
- ESP32 / ESP32-CAM
- Relay Modules
- Soil Moisture, Gas, Rain, Temperature & Humidity, Motion and Water-Level Sensors
- Water Pump
- Door Lock Mechanism
- Pet Feeder Motor
- LoRa Module

### Software & Platforms
- **C++ / Arduino IDE** – Embedded firmware and hardware interfacing
- **ESP RainMaker** – IoT control, monitoring and automation
- **Blynk 2.0** – Remote control and IoT dashboards
- **FAVRIOT** – IoT data and device integration
- **Sinric Pro** – Smart-device and voice-assistant integration
- **Google Gemini** – AI-assisted interaction and automation
- **Google Assistant / Amazon Alexa** – Voice-based control
- **Telegram Bot** – Real-time notifications
- **Wi-Fi / LoRa** – Connected and long-range communication

---

## System Architecture

```text
Smartphone / Manual / Voice / AI
              │
              ▼
       ESP32 Edge Controller
              │
     ┌────────┼─────────┐
     ▼        ▼         ▼
  Smart     Security   Automation
 Control    & Safety   & Monitoring
     │        │         │
     └────────┼─────────┘
              ▼
       Sensors & Actuators
              │
     ┌────────┼─────────┐
     ▼        ▼         ▼
  IoT Cloud Telegram    LoRa
 Platforms    Alerts   Remote Nodes
