# Project Name: Crypto Sentiment
# Objective
This project predicts bitcoin prices using sentiment analysis as an additional feature because the price is mainly linked to emotion/sentiment.   

# Motivation
Bitcoin prices are extremely volatile due to its high speculative nature. A big part of the trading is backed by emotions and not fundamentals and logic. This project tries to capitalize on this inherently strong sentiment investing that makes up a majority of the trading of bitcoin. 

# Data Source 
The data was acquired from 3 different API's:
- https://www.coindesk.com/coindesk-api
- https://alternative.me/crypto/fear-and-greed-index/
- http://api-dev.augmento.ai/v0.1/documentation#introduction

# Model
- Prophet

# Deployment
- GCP & Heroku

# Project Description

## Data
1. Identify datasets to use as exogenous features for the Prophet model.
2. Retrieve the data from chosen API's
3. Clean and explore the data.

## Modelling
1. Choose the period to train and test the model.
2. Tuning the model.

## Predicting
1. Make prediction for the next day.


## Backtesting
1. Create the buy and sell signal for the strategy.
2. Implement it across different time periods.
3. Compare strategy using only price with and without sentiment scores.