# 🔧 Predictive Maintenance Using Machine Learning

A machine learning project designed to predict equipment failures before they occur, enabling proactive maintenance in industrial settings. This approach helps minimize downtime, optimize repair schedules, and extend the lifecycle of critical machinery.

---

## 📚 Table of Contents

- [Overview](#overview)
- [Dataset & Variables](#dataset--variables)
- [Methodology](#methodology)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Contact](#contact)

---

## 📌 Overview

Predictive maintenance uses data from sensors installed in machines to predict potential failures. This project builds several machine learning models—including Random Forest, Decision Trees, Bagging, and LSTM Neural Networks—to classify and predict failure types in industrial equipment like pumps, motors, and compressors.

---

## 📊 Dataset & Variables

This synthetic dataset simulates real-world sensor readings collected from manufacturing machinery.

| Variable         | Description |
|------------------|-------------|
| `Temperature`     | Operating temperature of the equipment (°C) |
| `Vibration`       | Level of vibration detected (0 to 1) |
| `Pressure`        | Internal pressure in bars |
| `Humidity`        | Ambient humidity (%) |
| `RPM`             | Rotations per minute |
| `Voltage`         | Voltage supply (V) |
| `Current`         | Current usage (A) |
| `Sound_Level`     | Noise level in decibels |
| `Oil_Quality`     | Index of oil degradation (0 to 1) |
| `Load`            | Machine load percentage (%) |
| `Machine Type`    | Equipment type: Pump, Motor, Compressor |
| `Component Type`  | Specific part being monitored |
| `Failure Type`    | Target variable showing failure type (mechanical, electrical, etc.) |

---

## 🔍 Methodology

1. **Data Generation & Preprocessing**
   - Randomized synthetic data generation
   - Feature encoding, scaling, and train-test split

2. **Model Development**
   - Classical ML models: Random Forest, Decision Tree, Bagging
   - Deep learning: LSTM (for sequential data analysis)

3. **Model Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1 Score

---

## 📈 Results

- **Random Forest** delivered strong classification accuracy.
- **LSTM Neural Network** effectively captured temporal relationships in sensor data.
- **Bagging models** enhanced robustness and generalization.
- Early prediction of failure types enables better planning and minimized downtime.

---

## 🛠 Technologies Used

- Python
- NumPy, Pandas
- Scikit-learn
- Matplotlib, Seaborn
- TensorFlow / Keras
