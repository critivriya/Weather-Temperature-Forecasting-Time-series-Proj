


# 🌦️ Weather Temperature Forecasting using ARIMA and LSTM

## 📌 Overview
This project focuses on forecasting temperature using time-series modeling techniques and comparing the performance of a classical statistical model (ARIMA) with a deep learning model (LSTM).

---

## 🎯 Objective
To build an accurate temperature prediction system and evaluate whether deep learning models outperform traditional statistical approaches on time-series data.

---

## 📊 Dataset
- Historical weather data (temperature time-series)
- Preprocessed for missing values, scaling, and sequence generation

---

## ⚙️ Methodology

### 🔹 ARIMA Model
- Applied ARIMA for statistical time-series forecasting  
- Tuned parameters (p, d, q) for optimal performance  

### 🔹 LSTM Model
- Built a deep learning model using LSTM layers  
- Trained on sequential data to capture temporal dependencies  
- Handled non-linear patterns in the dataset  

---

## 📈 Results

- **LSTM RMSE:** 2.65°C  
- **ARIMA RMSE:** 3.33°C  
- **Improvement:** ~20% better accuracy with LSTM  

➡️ LSTM outperformed ARIMA by effectively capturing complex and non-linear patterns in temperature data.

---

## 📉 Visualization
- Plotted **actual vs predicted temperature trends**  
- Compared performance across models visually  

---

## 🛠️ Tech Stack
- Python  
- Statsmodels (ARIMA)  
- TensorFlow / Keras (LSTM)  
- Pandas, NumPy  
- Matplotlib  

---

## 🚀 Key Learnings
- Deep learning models like LSTM perform better on non-linear time-series data  
- Proper preprocessing and sequence generation are crucial for LSTM performance  
- Model evaluation using RMSE helps in comparing forecasting accuracy  

---

## 📂 Future Improvements
- Incorporate additional features (humidity, wind speed, etc.)  
- Use advanced models like GRU or Transformer-based architectures  
- Deploy the model as a web application  

---
