
# Stock Market Trend Analyzer

Analysis of 5 major stocks (AAPL, TSLA, MSFT, GOOGL, AMZN) covering the period from 2020 to 2024. The project goes through the full pipeline — data collection, exploratory analysis, technical indicators, machine learning prediction, and SQL querying — all in one place.

Historical data was fetched directly via the `yfinance` library from Yahoo Finance. The analysis includes technical indicators such as SMA, RSI, MACD, and Bollinger Bands, which were then used to train a Linear Regression model to predict Apple's closing price. The model achieved a Mean Absolute Error of $2.28 on unseen 2024 data.

All stock data was also loaded into a SQLite database to run queries for insights like yearly price summaries, highest volume trading days, and cross-stock comparisons.

## Notebooks

- `data_collection.ipynb` — fetching and storing historical stock data
- `EDA.ipynb` — exploratory data analysis and visualization
- `technical_analysis.ipynb` — computing technical indicators
- `prediction_model.ipynb` — ML model training and evaluation

## Tech Stack

Python, Pandas, Matplotlib, Seaborn, Scikit-learn, SQLite
