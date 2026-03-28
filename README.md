# 📊 AI-Based Stock Trading Strategy using Machine Learning

## 🔹 Overview
This project aims to predict stock price movement (UP/DOWN) using Machine Learning techniques and generate trading signals based on predictions.

The system uses historical stock data, performs feature engineering, trains models, and evaluates performance through backtesting.

---

## 🎯 Objective
- Predict next-day stock direction
- Build a trading strategy using ML predictions
- Compare performance with market baseline

---

## ⚙️ Features
- Logistic Regression and Random Forest models
- Technical indicators:
  - Moving Averages (MA5, MA10)
  - RSI (Relative Strength Index)
  - Volatility
  - Momentum
- Backtesting strategy performance
- Visualization of returns
- Command-line interface (CLI)

---

## 📂 Project Structure

stock-ml-project/
│
├── src/
│ ├── data_loader.py
│ ├── features.py
│ ├── train.py
│ ├── backtest.py
│
├── models/
├── app.py
├── requirements.txt
├── README.md
└── report.pdf


---

## 📥 Installation

```bash
pip install -r requirements.txt
