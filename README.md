# Predicting Future Stock Prices Using Time Series Data and Sentiment Analysis of Tweets
## Overview

This project aims to predict future stock prices by combining time series analysis of historical stock data with sentiment analysis of tweets. By integrating these two approaches, we aim to improve prediction accuracy by taking into account both past stock behavior and current market sentiment.

### Key Components:
- Time Series Analysis: We use historical stock price data to forecast future prices based on trends, seasonality, and other time-based patterns.
- Sentiment Analysis of Tweets: Sentiment analysis is applied to Twitter data to gauge public opinion on stocks. This is used as an additional feature in the stock price prediction model.

### Dependencies
- Python 3.9
**Libraries**:
- numpy, pandas (for data manipulation)
- yfinance, talib (for stock market analysis)
- matplotlib, seaborn (for data visualization)
- scikit-learn, statsmodels, xgboost (for modeling)
- nltk, vaderSentiment, autocorrect, demoji (for sentiment analysis)
- requests, bs4  (for scrapping comments from Yahoo Finance Conversetation)
