# 📈 Stock Price Predictor using Linear Regression

This project predicts future stock prices based on historical data using Linear Regression. It uses real-time stock data from Yahoo Finance via the `yfinance` API.

## 🔧 Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Scikit-learn (Linear Regression)
- Yahoo Finance API (`yfinance`)
- Google Colab

## 📥 Dataset
The stock data is fetched from Yahoo Finance:
- Stock Symbol: AAPL (Apple Inc.)
- Duration: Jan 2018 – Dec 2023
- Source: [Yahoo Finance](https://finance.yahoo.com)

## 🔍 How It Works
1. Fetch historical stock data
2. Convert date into numerical format (days)
3. Split the dataset into training and test sets
4. Train a Linear Regression model
5. Predict and visualize actual vs predicted prices

## 📉 Output
A line plot showing actual vs predicted prices of AAPL stock from 2018–2023.

## 📂 File Included
- `Stock_Price_Predictor.ipynb` — Colab notebook
- `AAPL_stock_prediction.csv` — CSV file with predicted values 
- `README.md` — Project overview
