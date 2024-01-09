# Stock Price Prediction Using BERT-Based Sentiment Analysis and LSTM

## Overview

This project, titled "Stock Price Prediction Based on Multiple Data Sources and Sentiment Analysis Using a BERT-Based Model," aims to enhance the accuracy of stock market forecasts by integrating traditional financial analysis with modern AI techniques. Utilizing historical stock data, sentiment analysis from social media, and cutting-edge machine learning models, this project offers a novel approach to predict stock prices.

## Features

- **Technical Indicator Calculation Model**: Calculates various technical indicators like Moving Averages, RSI, %K, %R using historical stock data.
- **Sentiment Index Calculation Model**: Analyzes sentiments in tweets using a fine-tuned DistilBERT model (distilRoBERTa-financial-sentiment), classifying them into positive, negative, or neutral categories.
- **Attention-Based LSTM Model**: Combines technical indicators and sentiment indices to predict stock prices, employing an LSTM model enhanced with an attention mechanism for improved accuracy.

## Data Sources

- **Historical Stock Data**: From Google (GOOG), Amazon (AMZN), and Microsoft (MSFT) spanning January 1, 2015, to January 31, 2019.
- **Sentiment Data from Tweets**: Dataset of over 1.7 million public tweets about key technology companies, analyzed for sentiment.

## Technical Stack

- **Data Manipulation**: Python, Pandas
- **Sentiment Analysis**: DistilBERT (Transformers library)
- **Machine Learning Model**: Keras, TensorFlow

## Evaluation Criteria

- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**

## Results

- Achieved high accuracy in stock price predictions with an MSE of 1.0972e-04 and an MAE of 0.0086.
- Visualizations confirming the model's efficacy include plots of predicted vs. actual stock prices and error distribution histograms.
