# 🏍️ SURAKSHA – Smart Helmet Companion

> Intelligent IoT-enabled Smart Helmet for Real-Time Accident Detection and Emergency Response.

![Banner](Images/Helmet.jpg)

---

## 📌 Overview

SURAKSHA is an IoT-based smart helmet designed to improve rider safety by automatically detecting accidents and immediately notifying emergency contacts with the rider's live GPS location.

The system combines embedded hardware, intelligent accident detection logic, cloud connectivity, and a modern web dashboard to provide fast emergency response while minimizing false alarms.

This project was demonstrated as a working prototype during **SRISHTI 2026 Project Exhibition**.

---

# Features

- 🚨 Automatic Accident Detection
- 📍 Live GPS Tracking
- 📲 SMS Alert to Emergency Contacts
- 🌐 Live Web Dashboard
- ❤️ Heart Rate Monitoring
- 🧭 Gyroscope Based Crash Detection
- 🔔 Emergency Buzzer
- 🛑 False Alert Cancellation Button
- 🪖 Helmet Wear Detection using IR Sensors

---

# Hardware Used

| Component | Purpose |
|-----------|----------|
| ESP32 | Main Controller |
| MPU6050 | Motion & Tilt Detection |
| Neo-6M GPS | Live Location |
| MAX30100 | Heart Rate & SpO₂ |
| IR Sensors | Helmet Detection |
| Buzzer | Emergency Warning |
| Push Button | Cancel False Alert |
| Battery | Portable Power |

---

# Software Stack

- Arduino IDE
- ESP32 Framework
- HTML
- CSS
- JavaScript
- Firebase / Web Server
- SMS API
- GPS Parsing

---

# Working Principle

1. Rider wears helmet.
2. IR sensors confirm helmet usage.
3. ESP32 continuously monitors:

   - Motion
   - Impact
   - Heart Rate
   - GPS

4. Crash is detected.

5. Buzzer starts a countdown.

6. Rider can cancel if it is a false alarm.

7. If no response:

   - GPS Location captured
   - SMS sent
   - Dashboard updated
   - Emergency alert generated

---

# Flow

Helmet Detection
↓

Monitor Sensors
↓

Accident?

├── No → Continue Monitoring

└── Yes

↓

Start Buzzer

↓

False Alarm?

├── Yes → Resume Monitoring

└── No

↓

Read GPS

↓

Send SMS

↓

Update Dashboard

↓

Emergency Response

---

# Dashboard

The companion dashboard provides

- Rider Login
- Live Sensor Values
- Crash Alerts
- GPS Location
- Emergency Contact Information
- Medical Information
- Live Accident Status

---

# Future Improvements

- GSM Module Integration
- AI-based Crash Classification
- Camera Module
- Voice SOS
- Fall Severity Prediction
- Mobile App
- Cloud Analytics
- Edge AI

---

# Project Highlights

- Embedded Systems
- IoT
- Web Development
- Real-Time Monitoring
- Human Safety
- Smart Decision Logic
- Industry-Oriented Prototype

---

# Exhibition

Presented during

**SRISHTI 2026**

Received valuable feedback from

- Faculty Mentors
- Students
- Industry Visitors

---
## Author 
Chinmay N. Yalawatti

## License

MIT License
