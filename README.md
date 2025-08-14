# 📈 AI/ML Internship — Short-Term Stock Price Forecasting

This repository contains my **AI/ML internship Task 2** project, where I work with real stock market data to **predict the next day’s closing price** using regression models.  
Data is pulled directly from **Yahoo Finance** via the `yfinance` library.

---

## 🎯 Task Overview
The aim is to practice **time series regression** by:
- Downloading historical market data.
- Preparing relevant features for model training.
- Building and testing machine learning models to forecast short-term price movement.

---

## 📊 Dataset Information
- **Source:** [Yahoo Finance](https://finance.yahoo.com/)  
- **Fetched with:** [`yfinance`](https://pypi.org/project/yfinance/)  
- **Stocks Analyzed:**
  - **Apple (AAPL)** — Data from 2015 to 2024
  - **Tesla (TSLA)** — Data from 2015 to 2024
- **Input Features:** `Open`, `High`, `Low`, `Volume`
- **Prediction Target:** Next day's `Close` price

---

## 🤖 Models Used
1. **Random Forest Regressor** — Applied to **AAPL** data for testing an ensemble-based approach.  
2. **Linear Regression** — Applied to **TSLA** data as a baseline for comparison.

---

## 📌 Insights & Results
- The **Random Forest model** gave reasonable predictions for Apple’s prices but had difficulty with high volatility.  
- Surprisingly, **Linear Regression** performed comparably well on Tesla data despite its simplicity.  
- This shows that **more complex models aren’t always better** when feature sets are limited.

---

## 🔮 Future Improvements
- Add engineered features like **moving averages**, **RSI**, or **lag values**.
- Test **LSTM** or other recurrent neural networks for sequential learning.
- Perform **hyperparameter tuning** for improved performance.

---

## 📂 Files in Repository
- `stock_price_prediction.ipynb` — Jupyter Notebook containing full code, model training, and plots.
- `README.md` — Task description, methods, and results.

---

✅ **Status:** Task Completed Successfully
