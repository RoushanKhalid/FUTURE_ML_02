# Stock Price Prediction using LSTM

This repository contains the work for Task 2 of my internship at Future Interns.  
The objective was to build a predictive model using LSTM to forecast future stock prices based on historical data.

## Objective

- Predict future stock closing prices using historical data.
- Visualize and evaluate model performance.
- Analyze trends using deep learning techniques.

## Tools and Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- TensorFlow/Keras
- Matplotlib, Seaborn
- Git LFS (Large File Storage)

## Dataset Structure

The dataset includes the following columns:

- Date – trading date
- Open – opening price
- High – highest price during the day
- Low – lowest price during the day
- Close – closing price adjusted for splits
- Adj Close – adjusted close price for dividends/splits
- Volume – number of shares traded

## Project Workflow

- Data loading and preprocessing
  - Parsing dates
  - Normalizing prices
  - Creating sequences for LSTM
- Model development
  - Stacked LSTM layers
  - Compilation using MSE loss and Adam optimizer
- Model evaluation
  - Compared predicted vs actual prices
  - Used RMSE and MAE for performance
- Forecasting
  - Predicted next 30 days of closing prices
