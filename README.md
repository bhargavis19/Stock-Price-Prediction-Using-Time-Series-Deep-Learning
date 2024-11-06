# Stock-Price-Prediction-Using-Time-Series-Deep-Learning-

# Univariate Time Series Forecasting

This project demonstrates stock price prediction using historical data with deep learning models for multi-step time series forecasting.

## Overview

This project involves applying deep learning techniques using recurrent neural networks (RNNs) to predict stock prices. Sequential models like stacked LSTM, Bidirectional LSTM, and NeuralProphet, all built with PyTorch, are used to analyze and forecast stock prices based on historical data.

## Table of Contents

1. Introduction to Time Series
2. Understanding LSTM
3. Overview of Bidirectional LSTM
4. Introduction to NeuralProphet
5. Data Collection: Stock Data
6. Model Development
7. Training and Validation Results
8. Conclusions

This project accompanies the article: "Univariate Time Series with Stacked LSTM, BiLSTM, and NeuralProphet." 

## Stock Data

Data was gathered from January 4, 2010, to November 2, 2021 (over 11 years), focusing on Apple Inc. (AAPL). This period includes critical market events, such as those during the Covid-19 pandemic.

The Yahoo Finance API was used to source stock data. 

## Model Implementation

The project employs three primary models:

- **Stacked LSTM**: A multi-layered LSTM designed to capture sequential dependencies in stock price data.
- **Bidirectional LSTM**: An LSTM model that processes data in both forward and backward directions, capturing patterns from both perspectives.
- **NeuralProphet**: A model inspired by Facebook's Prophet, tailored for time series forecasting with additional capabilities for handling seasonal trends.

Each model was implemented using PyTorch, with training and validation performed on historical stock price data.

## Visualizing Results

Each model's forecasted results are visualized, allowing for a comparison of their effectiveness in predicting stock prices. Below are sample visuals for each model's predictions:

- **Stacked LSTM**
- **Bidirectional LSTM**
- **NeuralProphet**

## Technology Stack

- Google Colab
- numpy
- pandas
- sklearn
- scipy
- matplotlib
- tensorflow
- keras
- Plotly
- NeuralProphet
- h5py
- Facebook Prophet (included for benchmarking)

## Final Thoughts

The analysis showcases the potential of using deep learning for stock price forecasting. However, investment decisions should always involve comprehensive research beyond algorithmic predictions. This project serves as a practical guide for implementing time series forecasting models and is not intended as financial advice.
