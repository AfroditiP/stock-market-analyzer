# 📈 Stock Market Trend Analyzer

A complete data analysis project that collects, analyzes, and predicts stock prices 
for 5 major companies (AAPL, TSLA, MSFT, GOOGL, AMZN) from 2020 to 2024.

## 🛠️ Tech Stack
- Python
- Pandas
- Matplotlib / Seaborn
- Scikit-learn
- SQLite

## 🤖 Machine Learning
- **Model:** Linear Regression
- **Features:** SMA_20, SMA_50, SMA_200, RSI, MACD, Bollinger Bands
- **Why Linear Regression:** Technical indicators have a strong linear relationship with stock prices, making it an ideal and interpretable baseline model
- **Result:** MAE of $2.28 — predicting Apple's price within $2.28 on average

## 🗄️ SQL Analysis
- Built a SQLite database with all 5 stocks
- Queried highest and lowest price days
- Built yearly price summaries
- Joined multiple tables to compare stocks side by side

## 📌 Data Source
All stock data is fetched live from Yahoo Finance using the `yfinance` library.