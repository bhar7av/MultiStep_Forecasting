# 📈 Multi-Step Time Series Forecasting

This project implements a **multi-step time series forecasting model**
to predict future values using lag-based feature engineering and
machine learning techniques.

## 🚀 Key Features
- 7-day ahead forecasting horizon
- Lag features (1–30 days)
- Rolling statistics (mean & standard deviation)
- Calendar features (day, month, weekday)
- Temporal train-test split
- XGBoost regression model

## 🧠 Technologies Used
- Python
- NumPy, Pandas
- Matplotlib
- Scikit-learn
- XGBoost
- TensorFlow (for future deep learning extension)

## 📊 Workflow
1. Data preprocessing
2. Feature engineering
3. Model training
4. Multi-step prediction
5. Model evaluation (MAE, RMSE)

## ▶️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook
