# StockPrediction

This project aims at predicting closing stock prices using multiple techniques.

![Example of closing stock price prediction with uncertainty boundaries](https://github.com/AmL-Dev/StockPrediction/assets/61467804/11647b33-3031-4d73-912c-553e6e1c9b28)

## Description

This project uses different techniques to predict upcoming closing stock price trends. The use-case consists of the Apple stock price data.

The following techniques were impemented:

- Arithmetic average
- Exponential moving average
- Polynomial regression, for long-term trends
- ARIMA to predict mutltiple days in advance
- LSTM
- CNN-LSTM Encoder-Decoder

## Built With

This project was build using the following technologies:

- [Python](https://www.python.org/)
- [Jupyter Notebook](https://jupyter.org/)

## Installation

### Libraries

Tested on:

- [Tensorflow Keras 2.10.0](https://www.tensorflow.org/guide/keras?hl=fr)
- [scikit-learn 1.1.2](https://scikit-learn.org/stable/)
- [statsmodels 0.14.1](https://www.statsmodels.org/stable/index.html)
- [yfinance 0.2.33](https://pypi.org/project/yfinance/)

### Run the project

Execute the Jupyter code cells sequentially.

## Sources

- [Forecasting: Principles and Practice](https://otexts.com/fpp2/arima.html)

- [Autoregressive Integrated Moving Average ARIMA(p, d, q) Models for Time Series Analysis](https://www.quantstart.com/articles/Autoregressive-Integrated-Moving-Average-ARIMA-p-d-q-Models-for-Time-Series-Analysis/)

- [Multi-Step LSTM Time Series Forecasting Models for Power Usage](https://machinelearningmastery.com/how-to-develop-lstm-models-for-multi-step-time-series-forecasting-of-household-power-consumption/)

- [Predicting Netflix stock prices using Machine Learning, using Python](https://medium.com/geekculture/predicting-netflix-stock-prices-using-machine-learning-using-python-d7ca73ae7d4e)
