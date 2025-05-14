# lstm-tsk-fuzzy-network

This repository contains the core components of my Final Year Project on interpretable time series modeling using a deep fuzzy Takagi–Sugeno–Kang (TSK) inference system integrated with LSTM neural networks. The model is applied to stock price prediction and trading signal generation using the MACD indicator.

## Overview

- **Model**: LSTM-TSK fuzzy neural network with Gaussian membership functions and rule-based inference
- **Goal**: Predict 15-day-ahead stock prices and generate interpretable trading signals
- **Data Source**: Real-time historical stock data from Yahoo Finance via the `yfinance` API
- **Implementation**: Fully implemented in Google Colab, leveraging TensorFlow, scikit-learn, and yfinance
- **Interpretability**: Fuzzy rules provide insight into model decisions using dynamic sliding planes

## Repository Structure

