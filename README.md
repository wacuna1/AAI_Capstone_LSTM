# Stock Price Prediction using Deep Learning

This project explores the use of deep learning models to predict stock prices, focusing on the SPY (S&P 500 ETF) as a case study.

## Project Overview

We compare three types of neural network models:
1. Long Short-Term Memory (LSTM)
2. Artificial Neural Network (ANN)
3. Gated Recurrent Unit (GRU)

Our goal is to predict the next day's closing price of the SPY ETF using historical price data and technical indicators.

## Data

We use data from the Alpha Vantage API, including:
- Daily stock prices (open, high, low, close, adjusted close)
- Technical indicators (SMA, RSI, MACD, Bollinger Bands, etc.)

## Code
Capstone_Time_Series_Neural_Network_Model_Comparison.ipynb has all our code for this project.


## Models

1. LSTM: 12 layers, hidden size of 32, dropout rate of 0.3
2. ANN: 2 fully connected layers, dropout rate of 0.2
3. GRU: 3 layers, hidden size of 32, dropout rate of 0.1

## Results

All models achieved similar error metrics:
- Mean Absolute Error (MAE): 0.14
- Median Absolute Error (MedAE): 0.13
- Mean Absolute Percentage Error (MAPE): 16.85%

However, their predictions for the next day's SPY closing price varied:
- LSTM: $508.71
- ANN: $489.95
- GRU: $490.08

## Contributors

William Acuna, Sinthuja Bates, Frank Ivey
