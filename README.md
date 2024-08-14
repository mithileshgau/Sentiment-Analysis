# Sentiment-Analysis
Time Series analysis using News Sentiment Data

## Project Overview
This project investigates the relationship between historical stock data and real-time news sentiment to develop a predictive model for forecasting future stock prices. By combining quantitative analysis of stock market dynamics with qualitative assessment of news sentiment, the project aims to enhance predictive accuracy and provide valuable insights into market behavior.

We leverage Long Short-Term Memory (LSTM) networks alongside traditional models like ARIMA to explore the efficacy of incorporating sentiment analysis into stock price prediction. The project utilizes libraries such as TensorFlow and NLTK for implementation, with evaluation metrics like Mean Absolute Error (MAE), Root Mean Square Error (RMSE), and directional accuracy to assess model performance.

## Features
Data Collection:

Historical stock data from 10 prominent companies.
Over 6000 curated news articles relevant to financial markets.
Data Preprocessing:

Extensive data cleaning and normalization processes to prepare both textual and stock data for analysis.
Sentiment analysis using the DistilRoBERTa model to classify news articles as positive, negative, or neutral.
Modeling:

LSTM Model: Combines historical stock prices with sentiment scores to predict future trends.


The project evaluates models based on RMSE, comparing LSTM models with and without sentiment analysis to showcase the impact of incorporating news sentiment.

## Results
LSTM with Sentiment Analysis: Demonstrates improved accuracy in predicting stock price trends by integrating news sentiment data.
LSTM without Sentiment Analysis: Provides a baseline comparison to highlight the added value of sentiment analysis.
ARIMA Model: Offers insights from traditional time series forecasting methods without sentiment integration.

## Visualization
The project includes visualizations comparing actual stock prices with predicted prices across different stocks such as Google, Coca-Cola, Home Depot, Nvidia, and Pfizer, illustrating the performance of the models.

## Conclusion
This project showcases the potential of integrating news sentiment with historical stock data for more accurate stock price predictions. The interdisciplinary approach provides a holistic understanding of market behavior, aiding in improved decision-making in financial markets.
