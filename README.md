# LSTM Stock Price Prediction

This repository contains code for predicting stock prices using Long Short-Term Memory (LSTM) neural networks. The project leverages technical indicators and time series data to forecast future stock prices.

## Overview

The project involves the following steps:

1. **Data Preprocessing**: Load and clean the data, convert volumes, and set the date as the index.
2. **Feature Engineering**: Add technical indicators such as SMA, EMA, and RSI to the dataset.
3. **Scaling**: Normalize the features and target variable using MinMaxScaler.
4. **Data Splitting**: Split the data into training and test sets using TimeSeriesSplit.
5. **Model Building**: Construct and compile an LSTM model with Bidirectional LSTM layers and Dropout.
6. **Model Training**: Train the model using early stopping to prevent overfitting.
7. **Prediction**: Make predictions on the test set and future prices, ensuring the price change is within a specified range.
8. **Evaluation**: Evaluate the model performance using MAE, MSE, and RMSE, and visualize the results.

## Getting Started

### Prerequisites

Ensure you have the following libraries installed:

- pandas
- numpy
- matplotlib
- scikit-learn
- tensorflow
- ta (Technical Analysis Library)

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib scikit-learn tensorflow ta
