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

```
🌾 Smart Agriculture Dashboard
----------------------------------------
| Temperature 🌡️ | Moisture 💧 trends |
----------------------------------------


```
📁 Smart-Agriculture-IoT
│
├── device_simulator.py       # Simulates IoT sensor device data
├── local_function.py         # Processes and checks IoT data
├── dashboard.py              # Streamlit dashboard for visualization
├── iot_messages.json         # Raw simulated data file
├── processed_data.json       # Processed and cleaned data file
└── README.md                 # Documentation

```

Step 1: Install Dependencies

Make sure Python is installed, then run:
```json
pip install streamlit pandas


```
Step 2: Start the Device Simulator

Begin generating simulated IoT sensor data:
```json
python device_simulator.py


```
Step 3: Start the Local Function

Process and log alerts locally:
```json
python local_function.py



```
Step 4: Launch the Dashboard

Start the Streamlit dashboard:
```json
streamlit run dashboard.py



```
