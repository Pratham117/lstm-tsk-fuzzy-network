# lstm-tsk-fuzzy-network

This repository contains the core components of my Final Year Project on interpretable time series modeling using a deep fuzzy Takagi–Sugeno–Kang (TSK) inference system integrated with LSTM neural networks. The model is applied to stock price prediction and trading signal generation using the MACD indicator.

## Overview

- **Model**: LSTM-TSK fuzzy neural network with Gaussian membership functions and rule-based inference
- **Goal**: Predict 13-day-ahead stock prices and generate interpretable trading signals
- **Data Source**: Historical stock data from Yahoo Finance via the `yfinance` API
- **Implementation**: Implemented using PyTorch, scikit-learn, and yfinance
- **Interpretability**: Fuzzy rules provide insight into model decisions using dynamic sliding planes

## MACD Variants

The project evaluates two types of MACD signals:

- **Vanilla MACD (vMACD)**: Based on historical closing prices (standard approach)
- **Forecasted MACD (fMACD)**: Computed on 13-day-ahead predicted prices (reduces lag)

## Why LSTM-TSK?

This architecture uniquely combines:

1. LSTMs: For temporal modeling

2. TSK Fuzzy Rules: For rule-based interpretability

3. Gaussian Membership Functions: Learnable partitions of input space

4. Infinite Sliding Planes: Dynamically learned surfaces that fit each fuzzy rule

Thus, it achieves both forecast accuracy and model transparency, which is valuable for algorithmic trading and risk analysis.
