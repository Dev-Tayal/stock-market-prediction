# stock-market-prediction
Stock market price trend prediction using LSTM and economic indicator

# Stock Market Prediction Using LSTM

This project predicts stock prices using Long Short-Term Memory (LSTM) neural networks trained on historical stock data from Yahoo Finance.

## Project Overview

- Download historical stock data using `yfinance`.
- Preprocess and normalize the stock price data.
- Create time series sequences for LSTM input.
- Build and train an LSTM model to predict stock closing prices.
- Evaluate the model using Root Mean Squared Error (RMSE).
- Visualize actual vs predicted stock prices.
- (Future) Option to integrate news sentiment data for enhanced predictions.

## Technologies Used

- Python 3.x
- TensorFlow / Keras
- yfinance
- scikit-learn
- pandas, numpy, matplotlib

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Dev-Tayal/stock-market-prediction
   cd stock-prediction

2. Install required Packages:
   pip install -r requirements.txt

3. Navigate to the notebook folder and open the notebook or script:

   For Jupyter Notebook or JupyterLab:
      cd notebook
      jupyter notebook 01_lstm_stock_prediction.ipynb

   Or open the .py script in your favorite editor.
