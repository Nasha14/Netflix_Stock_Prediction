# 🎯 Netflix Stock Prediction

A predictive analytics project to forecast **Netflix (NFLX)** stock prices using historical market data.  
This project applies **time series analysis, feature engineering**, and **machine learning** techniques to improve forecasting accuracy for informed investment decisions.

---

## 📊 Objective
To predict Netflix's next-day closing price using past stock data and engineered technical indicators (moving averages, lags, and returns).

---

## 🧠 Methodology
1. **Data Cleaning & Preparation**
   - Removed missing and duplicate values  
   - Created features: Moving Averages (10/20/50/100), Lag1–Lag3, and Returns

2. **Modeling**
   - Linear Regression (baseline model)  
   - Holt–Winters (time series smoothing)  
   - XGBoost (tree-based regression model)

3. **Evaluation Metrics**
   - Mean Absolute Error (MAE)  
   - Root Mean Squared Error (RMSE)  
   - R² Score

---

## 📈 Results Summary

| Model | MAE | RMSE | R² |
|--------|------|------|----|
| Linear Regression | 8.66 | 13.82 | 0.9608 |
| XGBoost | 45.28 | 63.82 | 0.1652 |
| Holt–Winters | 78.45 | 96.90 | -0.9245 |

✅ **Linear Regression** performed best, showing that simple feature-engineered models can outperform complex algorithms for structured financial data.

---

## 📉 Key Insights
- Strong linear trend captured through moving averages and lags  
- Holt–Winters struggled due to lack of seasonal patterns in Netflix’s stock  
- XGBoost underperformed but has potential with feature expansion and tuning



## 🧑‍💻 Author
**Nuuraishah Noor Mohamed**  
💼 *Data Analyst | Accounting Background | Financial Analytics Enthusiast*  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/nuuraishah-noor-mohamed-6001b981/)  
📍 *Open to Remote Roles*
