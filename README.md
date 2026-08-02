<div align="center">

# IoT-based Water Quality Monitoring System

### ESP32 | DS18B20 | TDS Sensor | ThingSpeak

![ESP32](https://img.shields.io/badge/ESP32-Embedded-blue)
![IoT](https://img.shields.io/badge/ThingSpeak-IoT-green)
![Arduino](https://img.shields.io/badge/Arduino-IDE-blue)

</div>

---

# Overview

This project presents an IoT-based Water Quality Monitoring System using an ESP32 microcontroller. The system continuously measures **water temperature** and **electrical conductivity (EC)** using dedicated sensors and displays the readings locally while simultaneously uploading them to the ThingSpeak cloud platform for remote monitoring.

The project demonstrates embedded programming, sensor interfacing, Wi-Fi communication, and cloud-based IoT data acquisition.

---

# Features

- Real-time temperature monitoring
- Electrical Conductivity (EC) measurement
- OLED display interface
- ESP32 Wi-Fi communication
- ThingSpeak cloud integration
- Continuous sensor monitoring

---

# System Design

<p align="center">
<img src="images/block diagram.png" width="700">
</p>

The ESP32 receives sensor readings from the DS18B20 temperature sensor and TDS sensor, processes the data, displays it on an OLED display, and uploads it to ThingSpeak over Wi-Fi for remote visualization.

---

# Hardware Prototype

<p align="center">
<img src="images/setup.jpg" width="550">
</p>

Prototype assembled using an ESP32 development board, temperature sensor, TDS sensor, OLED display, and breadboard for real-time water quality monitoring.

---

# Working Principle

1. Initialize ESP32 and connected peripherals.
2. Read temperature from the DS18B20 sensor.
3. Measure Electrical Conductivity (EC) using the TDS sensor.
4. Display readings on the OLED display.
5. Connect to the Wi-Fi network.
6. Upload sensor readings to the ThingSpeak cloud.
7. Repeat continuously for real-time monitoring.

---

# Hardware Used

- ESP32 Development Board
- DS18B20 Temperature Sensor
- TDS Sensor
- OLED Display
- Breadboard
- Jumper Wires

---

# Software Used

- Arduino IDE
- Embedded C++
- ThingSpeak Cloud Platform

---

# Skills Demonstrated

- Embedded Systems
- ESP32 Programming
- Sensor Interfacing
- IoT
- Wi-Fi Communication
- Embedded C++
- Analog Signal Acquisition

---

# Applications

- Water Quality Monitoring
- Environmental Monitoring
- Smart Agriculture
- Industrial Water Monitoring
- IoT-based Monitoring Systems

---

# Repository Structure

```text
esp32-water-quality-monitoring/

├── README.md
├── LICENSE
│
├── code/
│   └── water_quality_monitor.ino
│
├── docs/
│   └── Water_Quality_Monitoring_Report.pdf
│
└── images/
    ├── block diagram.png
    └── setup.jpg
```

---

# Future Improvements

- pH Sensor Integration
- Turbidity Monitoring
- Mobile Dashboard
- MQTT-based Communication
- Battery-powered Deployment

---

# Author

**Ayush Kumar**

B.E. Electronics & Communication Engineering

Dayananda Sagar College of Engineering

GitHub: https://github.com/ayushhkr
