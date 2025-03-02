Multivariate Regression for Stock Price Prediction (AAPL)

Overview
This project implements a Multivariate Regression Model in Python to predict the stock price of Apple Inc. (AAPL) using key technical indicators. The model leverages statistical regression to analyze the relationship between moving averages, Relative Strength Index (RSI), and stock price trends over a period from January 2020 to January 2023.

Technical Indicators Used
50-Day Moving Average (50-MA)
200-Day Moving Average (200-MA)
Relative Strength Index (RSI)

Dataset
Stock price data is retrieved using Yahoo Finance (yfinance library). The dataset includes daily stock prices, volume, and calculated technical indicators.

Installation
To run this project, install the required dependencies:

pip install yfinance pandas numpy statsmodels matplotlib scikit-learn

Implementation Steps
Fetch AAPL stock data from Yahoo Finance.

Calculate technical indicators (50-MA, 200-MA, RSI).

Prepare dataset by handling missing values.

Build a Multivariate Regression Model using statsmodels.

Evaluate the model using R-squared and other statistical metrics.

Predict stock prices based on trained regression.

Visualize actual vs predicted stock prices.

Usage
Run the Python script to train and evaluate the model:
Satyam_Multivariate Regression for Stock Price Prediction Using Technical Indicators (AAPL).ipynb

Results & Analysis
Statistical Summary: The model provides insights into how moving averages and RSI influence stock prices.

Performance Metrics: Includes R-squared, MAE, MSE, and RMSE for accuracy evaluation.

Visualization: Compares actual vs predicted stock prices using Matplotlib.

Future Improvements
Include additional technical indicators like MACD, Bollinger Bands, ATR.

Implement a train-test split to better assess model performance.

Explore machine learning models (Random Forest, XGBoost) for better predictive accuracy.

Author
Satyam, University at Buffalo School of Management, MS in Business Analytics (Finance)



