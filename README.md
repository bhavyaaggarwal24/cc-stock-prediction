# stock-prediction
Python code for predicting Stock price using LSTM

# Introduction
In this project, I ventured into the realm of stock market analysis, a domain where precision and data handling are paramount. The aim was to harness advanced machine learning algorithms, leveraging the vast computational resources and scalability offered by cloud computing. This fusion of technology was directed towards efficiently processing and analyzing extensive financial datasets from the stock market, with the ultimate goal of uncovering valuable insights into market trends and behaviors.
The approach was driven by the belief that the integration of machine learning and cloud computing could unveil patterns and predictive insights that were previously obscured by the sheer volume and complexity of financial data.

# Methodology

## Data Preprocessing
First step in the methodology was data preprocessing. This crucial phase involved cleaning the data to remove any inconsistencies or errors and normalizing it to ensure uniformity and comparability across different scales. Such preprocessing was vital to ensure the accuracy of our subsequent analyses and to facilitate the effective training of our machine learning models.

## Exploratory Data Analysis
The exploratory data analysis (EDA) encompassed several essential visualizations to gain insights into the stock market data.
Closing Price Over Time: Illustrated the overall trend of stock closing prices over the entire dataset period.

![image](https://github.com/bhavyaaggarwal24/stock-prediction/assets/163747248/f1ab2cde-3bda-477c-ae65-6c4d48353ae0)

Candlestick Chart: Displayed high, low, open, and close prices, providing a detailed view of intraday price movements.

![image](https://github.com/bhavyaaggarwal24/stock-prediction/assets/163747248/1c2119db-e206-45e8-8f31-20aac3a2b438)

Closing Prices and Moving Average Plot: Contrasted actual closing prices with moving average values, revealing trends and potential price crossovers.

![image](https://github.com/bhavyaaggarwal24/stock-prediction/assets/163747248/51172632-f6b7-4024-966c-c7a673e18e41)

Monthly Seasonality of Closing Prices: Highlighted monthly patterns in closing prices, aiding in identifying recurring trends or anomalies.

![image](https://github.com/bhavyaaggarwal24/stock-prediction/assets/163747248/182a4fee-5d3d-476f-95fe-b6bf10139a1a)

## Model Development
In the realm of model development, a suite of sophisticated machine learning algorithms used.

Primary among these was the LSTM (Long Short-Term Memory) network, a type of recurrent neural network known for its excellence in analyzing time-series data. The LSTM's ability to remember and utilize past information made it particularly suited for the prediction of stock prices, which are inherently influenced by their historical values.

Alongside LSTM, we also deployed Random Forest and Gradient Boosted Trees models. These models are renowned for their efficacy in handling non-linear data and extracting complex patterns, making them apt choices for the multifaceted nature of stock market data.

