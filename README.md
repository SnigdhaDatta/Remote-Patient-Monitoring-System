# 🧠 Remote Patient Monitoring (RPM) System

A smart healthcare project integrating **IoT sensors** and **AI models** to enable **real-time remote patient monitoring** (RPM) for vital signs such as heart rate, oxygen saturation (SpO₂), and temperature. This system is designed to support chronic disease management through predictive analytics and early alerts.

---

## 📌 Project Objectives

- Monitor patient vitals continuously and remotely using IoT sensors.
- Use AI/ML models to detect abnormal trends and trigger real-time alerts.
- Support healthcare professionals with data-driven insights for proactive care.
- Demonstrate the feasibility of low-cost, scalable remote monitoring systems.

---

## ⚙️ Hardware Components

| Component | Description |
|----------|-------------|
| **ESP32** | Microcontroller with built-in WiFi & Bluetooth for wireless data transmission. |
| **MAX30100** | Sensor for heart rate and SpO₂ (oxygen saturation) measurement. |
| **DHT11** | Temperature and humidity sensor for ambient environment monitoring. |
| **DS18B20** | High-precision digital temperature sensor (for body or surface readings). |
| **Zero PCB** | Base for connecting and soldering components. |
| **4.7kΩ Resistor** | Pull-up resistor required for DS18B20 communication. |

---

## 🧠 AI & ML Models Used

| Model | Use Case |
|-------|----------|
| **Decision Tree** | Initial classification for abnormal vitals. |
| **SVM (Support Vector Machine)** | Detects binary events such as normal vs abnormal SpO₂. |
| **CNN (Convolutional Neural Network)** | Used for ECG or facial emotion pattern recognition. |
| **LSTM (Long Short-Term Memory)** | Processes time-series data like heart rate and SpO₂ trends. |
| **Random Forest** | Ensemble learning for risk scoring and ICU-level triage. |

---

## 📊 Features

- ✅ Real-time vital sign monitoring (HR, SpO₂, temperature)
- ✅ Edge + Cloud integration (ESP32 + cloud dashboard)
- ✅ Predictive alerts based on AI model inference
- ✅ Emotion detection for mental health context
- ✅ Secure and HIPAA-aligned data handling

---

## 🏗️ System Architecture

