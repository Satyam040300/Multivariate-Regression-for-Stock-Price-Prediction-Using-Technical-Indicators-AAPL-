Multivariate Regression for Stock Price Prediction (AAPL)

Overview

This project implements a Multivariate Regression Model to predict the stock price of Apple Inc. (AAPL) using key technical indicators. The model uses the following technical indicators:
50-Day Moving Average (50-MA)
200-Day Moving Average (200-MA)
Relative Strength Index (RSI)
The regression model analyzes the relationship between these indicators and stock prices over a period from January 2020 to January 2023.

Technical Indicators

50-Day Moving Average (50-MA): A short-term trend indicator.
200-Day Moving Average (200-MA): A long-term trend indicator.
Relative Strength Index (RSI): A momentum oscillator indicating overbought and oversold conditions.

Installation

To run this project, you will need to install the required Python dependencies. You can install them using the following command:
bash
Copy
Edit
pip install yfinance pandas numpy statsmodels matplotlib scikit-learn
Usage
1. Fetch Stock Data
The yfinance library is used to fetch historical stock data for Apple Inc. (AAPL) between January 2020 and January 2023.

2. Calculate Technical Indicators
50-MA and 200-MA are computed using the moving average formula.
RSI is calculated based on price changes over a 14-day period.
3. Build Multivariate Regression Model
The model uses the 50-MA, 200-MA, and RSI as independent variables and the Close price as the dependent variable.

4. Evaluate the Model
The model's performance is evaluated using metrics such as R-squared, Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

5. Visualize the Results
A plot is generated to compare the actual vs predicted stock prices.

Running the Script

To run the script, simply execute the Python file (stock_price_prediction.py or your preferred filename) after ensuring all dependencies are installed.
bash
Copy
Edit
Satyam_Multivariate Regression for Stock Price Prediction Using Technical Indicators (AAPL).ipynb
The script will output the regression model summary, display the plot comparing actual vs predicted prices, and print the model's performance metrics.

Results

Regression Model Summary
The regression model provides insights into how the 50-day moving average, 200-day moving average, and RSI influence the stock price of AAPL.

Performance Metrics

The following metrics are calculated to evaluate the performance of the model:
R-squared: Measures how well the model fits the data.
Mean Absolute Error (MAE): Average of absolute errors.
Mean Squared Error (MSE): Average of squared errors.
Root Mean Squared Error (RMSE): Square root of MSE.

Example Plot

Below is an example of the plot that compares the actual vs predicted stock prices of Apple Inc. (AAPL).


Future Improvements

Additional Technical Indicators: Add indicators like MACD, Bollinger Bands, or ATR for more comprehensive analysis.
Train-Test Split: Implement a train-test split to evaluate the model on unseen data
Machine Learning Models: Explore Random Forest, XGBoost, or other machine learning models for better prediction accuracy.

Author

Satyam
University at Buffalo School of Management
MS in Business Analytics (Finance)

