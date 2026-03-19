# 🌦️ LSTM-based Weather Forecasting System (Edge-Enabled)

## 📌 Overview
This project implements a deep learning-based time series forecasting system using LSTM (Long Short-Term Memory) networks to predict temperature and rainfall based on historical weather data.

---

## 🚀 Key Features
- 📈 Time-series forecasting using LSTM  
- 🌡️ Temperature prediction  
- 🌧️ Rainfall prediction  
- 📊 Visualization of Actual vs Predicted values  
- 📉 Model performance tracking using loss curves  
- 🔄 Data preprocessing and scaling using MinMaxScaler  

---

## 🧠 Tech Stack & Tools

### 👨‍💻 Programming & Libraries
- Python  
- NumPy  
- Pandas  

### 🤖 Machine Learning / Deep Learning
- TensorFlow  
- Keras  
- Scikit-learn  

### 📊 Visualization
- Matplotlib  
- Seaborn  

### 🛠️ Development Tools
- Jupyter Notebook / Google Colab  
- Git & GitHub  

---

## ⚙️ Workflow
1. Data Collection & Cleaning  
2. Feature Engineering  
3. Data Scaling (MinMaxScaler)  
4. Sequence Creation for LSTM  
5. Model Building (LSTM Layers)  
6. Model Training & Validation  
7. Prediction Generation  
8. Result Visualization  

---

## 📂 Project Structure

- **data/** → Contains raw dataset used for training  
- **notebooks/** → Jupyter Notebook with model implementation  
- **outputs/** → Generated graphs and prediction results
  
---

## 📈 Model Performance

- **R² Score:** 0.9875  
- **RMSE:** 0.6511  
- **MAE:** 0.5607  

- **Data Frequency:** 15-minute intervals  

---

## 📊 Results

### 📈 Actual vs Predicted
![Actual vs Predicted](outputs/actual_vs_predicted.png)

### 📉 Loss vs Epoch
![Loss vs Epoch](outputs/loss_vs_epoch.png)

---

## 📁 Output Files
- Graphs showing model performance  
- `predictions.csv` containing forecasted values  

---

## 👨‍💻 Author
**Aaryan Bhandare**
