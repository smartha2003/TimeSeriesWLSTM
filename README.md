# 🧠 Time Series Forecasting with LSTM: Predicting Shampoo Sales

This project is part of my ongoing journey into learning **Long Short-Term Memory (LSTM)** networks and their applications in time series forecasting. I implemented and adapted this project from Jason Brownlee's tutorial to solidify my understanding of LSTM-based sequence modeling in Python using Keras and TensorFlow.

> 📌 **Goal**: Predict future monthly shampoo sales using historical data with a stateful LSTM network.

---

## 🚀 What I Learned

✅ How to reframe time series data as a **supervised learning** problem  
✅ The importance of making time series **stationary** (differencing)  
✅ How to **scale** data correctly for neural network training  
✅ Building, training, and evaluating an **LSTM network** in Keras  
✅ Using **walk-forward validation** (rolling forecasts)  
✅ Comparing model performance to a **persistence (baseline) model**

This project helped me move beyond just applying LSTMs — I started understanding **why** each preprocessing step matters and how **model architecture choices affect performance** in a temporal context.

---

## 🗂 Dataset

- [`shampoo-sales.csv`](shampoo-sales.csv): Monthly shampoo sales for 3 years (36 observations)
- Source: Makridakis, Wheelwright, and Hyndman (1998)

---

## 🛠 Tech Stack

- Python 3.x
- NumPy, Pandas, Matplotlib
- Scikit-learn for RMSE evaluation and scaling
- TensorFlow / Keras for the LSTM model

---

## 📊 Results

- The LSTM model achieved an average **Test RMSE of ~71**, outperforming the baseline **persistence model (~136)**.
- Walk-forward validation was used to simulate a real-world forecasting scenario.

---
