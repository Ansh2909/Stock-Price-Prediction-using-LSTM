# Stock Price Prediction with LSTM

This project implements a **Stock Price Prediction** model using **LSTM (Long Short-Term Memory)** neural networks to predict the future stock prices of a given company. The model is trained using historical stock price data, and it can forecast the stock prices for the next month.

## Introduction

In this project, we predict the stock price of a company using historical stock data and LSTM. The model learns from historical price data, and then predicts the stock prices for the next 30 days. The app is built using **Streamlit** and provides a simple, interactive interface to get predictions for any stock.

### Objective

- Predict future stock prices for the next month (30 days).
- Visualize historical stock prices alongside predicted future prices.


## Dependencies

This project requires the following libraries:

- `streamlit` - For creating interactive web applications.
- `yfinance` - To fetch historical stock price data.
- `numpy` - For numerical computations.
- `pandas` - For data manipulation and analysis.
- `scikit-learn` - For data preprocessing (MinMaxScaler).
- `matplotlib` - For data visualization.
- `tensorflow` - For training the LSTM model.
- `keras` - For building the neural network model.

## Model Architecture

This project uses an LSTM network to predict future stock prices. The architecture of the model consists of:

**LSTM layers**: These layers are used to capture the temporal dependencies in stock price data.
**Dropout layers**: Added to reduce overfitting by randomly setting a fraction of input units to zero during training.
**Dense layer**: The final layer, which outputs the predicted stock price for the next day.

## Model Training
**Training Data**: The model is trained on 75% of the data (historical stock prices).
**Test Data**: The remaining 25% is used to validate the model.

## Conclusion
This project demonstrates how to use **LSTM** for stock price prediction and how to deploy the model using **Streamlit** for easy access to users. By training the model on historical stock price data, the system can predict future prices for any given stock symbol.
