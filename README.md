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
- IoT Sensors → ESP32 → WiFi → Cloud Server / Edge AI → ML Model Inference → Dashboard / Alerts

---

---

## 🚑 Application Areas

- Cardiology (arrhythmia monitoring, pacemaker tracking)
- Diabetes (CGM data interpretation)
- Chronic pain (neuromodulation control)
- ICU and Emergency care (early warnings via LSTM/Random Forest)
- Mental health (emotion recognition via AI + sensors)

---

## 📉 Sample SpO₂ Trend Analysis

> Time-series visualization of SpO₂ levels collected using the MAX30100 sensor. AI detects gradual drops that may indicate respiratory risk, sending early alerts to caregivers.

---

## ⚠️ Challenges & Considerations

| Challenge | Mitigation |
|----------|------------|
| Data Overload | AI-based filtering and compression |
| Bias in Models | Use of diverse and inclusive training datasets |
| Privacy | HIPAA/GDPR-compliant platform and federated learning |
| Workflow Integration | EHR interoperability APIs |
| Cost | Use of affordable sensors and open-source software |

---

## 🔮 Future Enhancements

- Digital twin simulation of patients
- Integration with mobile apps for patients and doctors
- Federated learning for privacy-preserving AI
- AI in oncology and behavioral health
- Adaptive wearable implants

---

## 🧾 Citation & References

- Patel et al. (2024) – _Journal of Pain Research_
- Tsvetanov (2024) – _AI in Chronic Disease RPM Review_
- Clinical Trials: TRUST, CONNECT, IN-TIME

---

## 🧑‍💻 Author

**[Snigdha Datta]**  
Cloud Facilitator @ Google Developer Student Club  
B.Tech, Computer Science and Engineering  

---

