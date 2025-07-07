# 📱 Smart Pothole Detection using Smartphone Sensors

This project focuses on **automated pothole detection and road quality evaluation** using smartphone sensor data and machine learning techniques. It classifies road conditions into:
- ✅ Good roads  
- ⚠️ Bad roads  
- ⛔ Potholes  

Unlike image-based approaches, this project uses **only sensor data** (accelerometer, gyroscope, GPS) for real-time and cost-effective detection.

---

## 🚀 Features

- 📦 Merges multi-class sensor data into one labeled dataset
- 🔍 Handles missing values and class imbalance using SMOTE
- 📊 Visualizes class distributions via count plots
- 🤖 Implements two ML models:
  - **K-Nearest Neighbors (KNN)** – _100% Accuracy_
  - **Random Forest Classifier** – _99.98% Accuracy_
- 🧪 Evaluates performance with precision, recall, F1-score, confusion matrix
- 💾 Saves trained models and predicts on new test data


## 📊 Dataset Overview

| Feature           | Description |
|------------------|-------------|
| `timestamp`       | Timestamp of each sample |
| `latitude`        | GPS latitude |
| `longitude`       | GPS longitude |
| `speed`           | Movement speed of smartphone |
| `accelerometerX`  | Forward/backward acceleration |
| `accelerometerY`  | Up/down motion |
| `accelerometerZ`  | Side-to-side motion |
| `gyroX`, `gyroY`, `gyroZ` | Angular rotation axes |
| `Class`           | Target class: `Pothole`, `RoadCondition bad`, `RoadCondition good` |

## 📍 Applications

- 🏙️ **Smart City Monitoring**  
  Integrate with urban infrastructure for real-time road condition reporting and automated alerts.

- 📡 **GPS-based Driver Alerts**  
  Warn drivers in real time about upcoming potholes or bad road conditions through navigation systems.

- 🤖 **Autonomous Vehicles**  
  Improve safety and navigation accuracy in self-driving cars by detecting road surface anomalies.

- 🛠️ **Municipal Road Maintenance**  
  Assist civic bodies in identifying high-risk zones and prioritizing pothole repair work.

- 📑 **Insurance Claims Validation**  
  Provide sensor-based evidence of road conditions at the time of accidents or vehicle damage.

- 🚨 **Public Safety Alert Systems**  
  Notify emergency services and the public about hazardous road conditions, especially during rains.

- 📊 **Infrastructure Quality Auditing**  
  Help government bodies monitor long-term road degradation trends for audits and reporting.

- 🧪 **Research and Policy-making**  
  Support transport research institutes and policymakers in analyzing traffic safety and infrastructure needs.
