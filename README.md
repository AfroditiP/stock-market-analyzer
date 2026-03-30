# Stock Market Trend Analyzer

Analysis of 5 major stocks (AAPL, TSLA, MSFT, GOOGL, AMZN) from 2020 to 2024, covering exploratory data analysis, technical indicators, machine learning prediction and SQL querying.

## Tech Stack
Python, Pandas, Matplotlib, Seaborn, Scikit-learn, SQLite

## Machine Learning
Linear Regression model trained on technical indicators (SMA, RSI, MACD, Bollinger Bands) to predict Apple's closing price. Achieved a Mean Absolute Error of $2.28 on unseen data from 2024.

## SQL Analysis
All stock data was loaded into a SQLite database and queried to extract insights such as yearly price summaries, highest volume trading days, and cross-stock comparisons.

## Data Source
Historical stock data fetched via the `yfinance` library from Yahoo Finance.