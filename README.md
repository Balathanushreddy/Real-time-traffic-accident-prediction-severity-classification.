# Real-time-traffic-accident-prediction-severity-classification.
# 🚦 Real-Time Traffic Accident Prediction & Severity Classification

## 🧠 Project Overview
This project predicts **whether a traffic accident will occur** and classifies its **severity level** in real-time based on weather, traffic, and historical data.  
It leverages machine learning and deep learning models (LSTM, Random Forest, PyCaret pipelines) to provide proactive alerts for road safety and emergency planning.

---

## 🎯 Objectives
- Predict accident occurrence using live traffic and weather data.
- Classify accident severity (Minor / Major / Critical).
- Visualize accident-prone zones on an interactive map.
- Send real-time alerts via email when accident risk is high.

---

## 📊 Data Sources
| Source | Description |
|---------|-------------|
| [Google Maps API](https://developers.google.com/maps) | Real-time traffic congestion and location data |
| [OpenWeatherMap API](https://openweathermap.org/api) | Real-time weather metrics (rain, fog, temperature, humidity) |
| [Kaggle Accident Dataset](https://www.kaggle.com/datasets) | Historical accident patterns |
| IoT / Simulated Sensor Data | Road conditions, speed variations, potholes |

---

## ⚙️ Tech Stack
**Languages:** Python, JavaScript  
**Frameworks:** FastAPI / Flask, React (optional frontend)  
**Machine Learning:** PyCaret, scikit-learn, LSTM, TensorFlow  
**Cloud / Deployment:** Streamlit Cloud / Render / Azure App Service  
**Visualization:** Plotly, Matplotlib  
**Tracking & MLOps:** MLflow, Docker, GitHub Actions  
**Database:** PostgreSQL / SQLite  

---

## 🗂️ Project Structure
real-time-traffic-accident-prediction/
│
├── data/ # Raw & processed datasets
├── src/ # Core ML & API code
│ ├── data_collection.py
│ ├── feature_engineering.py
│ ├── model_training.py
│ ├── model_evaluation.py
│ └── utils/
│ ├── email_alert.py
│ └── plotly_map.py
├── notebooks/ # Jupyter notebooks for exploration
├── models/ # Trained ML models
├── frontend/ # Streamlit or FastAPI frontend
├── docs/ # Design & architecture documentation
├── requirements.txt
├── README.md
└── .gitignore

---
