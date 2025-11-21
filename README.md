# Bitcoin Price Prediction using Linear Regression

A beginner-friendly quantitative finance project that predicts Bitcoin closing prices using Python, Pandas, Scikit-Learn, and several technical indicators.
This project is a simple entry point into Quant Finance, Algorithmic Trading, and Financial Machine Learning.

# Overview

This notebook trains a Linear Regression model on historical Bitcoin price data.
Multiple technical indicators are engineered and used as model features to improve prediction accuracy.

# Features Used

Close_lag1 (previous day's close)

Moving Averages: MA7, MA30, MA20

Bollinger Bands (upper & lower)

RSI (Relative Strength Index)

Price volatility indicators

## Tools & Libraries

Python

Pandas

NumPy

Scikit-Learn

Matplotlib / Seaborn

yfinance

# Results

The Linear Regression model captures the general trend of Bitcoin prices but struggles with rapid volatility.
This project serves as a solid foundation for more advanced models such as LSTM, Prophet, or ARIMA.

# Future Work Ideas

Add more technical indicators

Compare models (Linear Regression vs Random Forest vs XGBoost)

Build a trading strategy (backtesting with vectorbt/backtrader)

Predict returns instead of raw price

Add LSTM / GRU models
