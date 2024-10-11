# Stock-price-prediction

*This repository contains code that could be used to predict the NTT's stock price using the time-series data and LSTM (Long Short-Term Memory) neural networks. This project is based on building a forecasting model for the stock price data using exploratory data analysis (EDA), feature engineering, model selection, and model evaluation.*

# Project Overview
The project workflow includes:

Exploratory Data Analysis (EDA):
Stock data analysis to understand the trends and seasonality as well as outliers.
Visualization of historical data and key statistics.
Data Preprocessing & Feature Engineering:
Handling missing values, normalization, and scaling of feature attributes.
Transformation of raw stock data (Open, High, Low, Close prices, Volume, % Change) for training model.

# Modeling
Implementation of LSTM for forecasting in time series model.
Comparison of conventional approach such as ARIMA and Legitimatization of taking LSTM.
Model Evaluation and Analysis
Checking the accuracy through metrics such as MAE, MSE, RMSE, R², and so on.
Visualizing the actual stock prices vs. predictions.

# Results and Presentation:

Presentation of forecasting results, residual analysis, and retraining results.
Future plans for further enhancing the performance of the model.
Important Features
Use of an LSTM model to capture the long-term dependencies existing in the data of the stocks.
Data preprocessing steps including normalization of the data of stock price and volume.
Visualization of time-series trends, seasonal patterns, and residuals distribution.
Libraries
The project is constructed by using the following libraries from Python.
tensorflow/keras: building and training the LSTM mode.
