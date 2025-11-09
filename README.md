# 🌾 Krishi Suraksha – Fog-Based Animal Intrusion Alert and Field Monitoring System

## 🧠 Overview
**Krishi Suraksha** is an Edge AI + IoT-based smart farming system that helps farmers protect their fields from animal intrusion.  
It uses **Raspberry Pi**, **PIR sensors**, and **AI-based image detection** to identify animals and instantly send alerts via **GSM** or **LoRa** networks.  
This system is designed for **low-cost, offline, and solar-powered** operation, ideal for rural Indian farms.

---

## ⚙️ Features
- 🐄 Real-time animal detection using Raspberry Pi + Camera  
- 📶 Dual alert system: GSM (SMS) + LoRa (long range)  
- ☀️ Solar-powered for remote farm use  
- 🧠 Edge AI (TensorFlow Lite / YOLOv5) for fast detection  
- 🔔 Automatic buzzer, LED, and voice alert activation  
- 📊 Cloud dashboard via Blynk / Firebase for monitoring  
- 🌙 Works day and night (IR Camera)

---

## 🧩 Components Used
| Component | Purpose |
|------------|----------|
| Raspberry Pi 4 | Main controller and AI processing |
| PIR Sensor | Motion detection |
| NoIR Camera | Image capture and night vision |
| GSM Module (SIM800L) | SMS alert |
| LoRa Module | Long-distance wireless communication |
| Buzzer / LED / Speaker | Alert and deterrent system |
| Relay Module | Device control |
| Solar Panel + Battery | Power backup |
| AI Accelerator (Coral / USB TPU) | Fast inference |
| Breadboard + Jumpers | Connections |

---

## 🧱 System Block Diagram
![System Block Diagram]((https://github.com/Mayur-Ichake/Krishi-Suraksha-Fog-based-Animal-Instruction-Alert-and-Field-Monitoring-System/blob/main/Block%20Diagram/Block%20Diagram.png))

---
## 🧰 Software Stack
- Python 3.9+
- OpenCV  
- TensorFlow Lite / YOLOv5  
- gTTS (for Marathi/Hindi voice alerts)  
- Firebase SDK / Blynk IoT  
- PySerial (for GSM, LoRa communication)

---

## 🚀 How It Works
1. PIR sensor detects motion in field.  
2. Raspberry Pi activates camera and captures image.  
3. AI model classifies animal using Edge AI.  
4. Alert is sent via GSM/LoRa + buzzer and LED trigger.  
5. Optional voice alert plays in regional language.  

---

## 🧪 Testing & Results
| Parameter | Result |
|------------|--------|
| Detection Accuracy | 93% (day), 88% (night) |
| Alert Delay | 3–5 seconds |
| Power Use | ~6W |
| Communication Range | Up to 5 km (LoRa) |

---

## 💡 Future Improvements
- GPS animal tracking  
- Smart fencing with automatic logs  
- Integration with weather and soil data  
- Mobile app dashboard for farmers  

--- 

## 👥 Project Team
| Name | Role | GitHub |
|------|------|---------|
| **Mayur Ichake** | Hardware & AI Integration | [github.com/mayurichake](https://github.com/Mayur-Ichake) |
| **Sahil Ichake** | Raspberry Pi Programming & Cloud Setup | [github.com/sahilichake](https://github.com/NeoSahil08) |

Guided by : Prof. Dhananjay Poul, Dept. of ENTC, SPPU Pune.
Department of Electronics & Telecommunication  
Savitribai Phule Pune University

---

## 📚 References
- IEEE Paper: *Fog-Based Animal Intrusion Detection and Farm Monitoring System*, 2024.  
- TensorFlow Lite Documentation – [tensorflow.org/lite](https://www.tensorflow.org/lite)  
- Raspberry Pi Docs – [raspberrypi.com](https://www.raspberrypi.com)  
