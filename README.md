# 🌾 Smart Agriculture IoT System

## 📘 Overview
The **Smart Agriculture IoT System** is a simulation-based project built using **Python** to demonstrate how IoT devices can monitor agricultural parameters like **temperature** and **soil moisture**.  

It showcases how sensor data is generated, processed, and visualized in real time using a **Streamlit dashboard**. This project can serve as a foundation for developing more advanced IoT-based smart farming solutions.

---

## 🧠 Working Principle

### 1️⃣ Device Simulator (`device_simulator.py`)
- Simulates an IoT device that sends random sensor readings.
- Generates **temperature** and **moisture** values every 3 seconds.
- Stores these readings in `iot_messages.json`.
  
**Example output:**
```json
{"device_id": "simDevice01", "temperature": 36.33, "moisture": 45.79}
