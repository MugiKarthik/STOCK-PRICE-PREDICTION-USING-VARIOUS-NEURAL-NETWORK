# STOCK-PRICE-PREDICTION-USING-VARIOUS-NEURAL-NETWORK

# Actual goal of this project:
# 1. Not to beat any research paper model
# 2. But to emphasize that neural network can do
# better prediction than traditional models and
# explain why??
# 
# Done:
# 1. Data Collection
# 2. Data Preprocessing
# 3. EDA
# 4. LSTM,GRU,RNN,CNN,Bi-LSTM
# 5. MA,EMA
# 6. ARIMA
# 7. Fbprophet
# 8. Time series analysis (Optional-Trend,Seasonality Decomp)
# 9. Comparing the rmse
# 10. Tuning best model
# 11. Forecast the values for next 30 days using the best model

This project delves into the realm of artificial 
intelligence to advance stock price prediction 
methodologies by leveraging various neural 
network architectures. Focusing on Long 
Short-Term Memory (LSTM), 
Convolutional Neural Network (CNN), and 
Gated Recurrent Unit (GRU), we aim to 
explore their effectiveness in capturing 
complex patterns and dependencies within 
historical stock price data. The dataset 
comprises essential financial features and 
technical indicators, subjected to thorough 
pre-processing. The methodology involves 
the implementation and training of the 
neural network models, with a focus on 
hyperparameter tuning to optimize their 
performance. The study also conducts 
feature engineering to identify influential 
variables and employs ensemble methods to 
enhance overall forecasting accuracy. The 
findings contribute to the ongoing discourse 
on improving predictive models in financial 
markets.
Keywords: Stock price prediction, Artificial 
intelligence, Neural networks, Long ShortTerm Memory (LSTM), Convolutional 
Neural Network (CNN), Gated Recurrent 
Unit (GRU) , Financial markets

The stock price dataset is collected from the 
YAHOO finance API. It contains open,
close, and volume attributes of various 
stocks available in the stock market. For 
this project, we took the stock price dataset 
of TCS company. This dataset consists of 
the prices from 2002 to 2024. Since the 
profit of the stock per day is calculated by 
the close price we took the close column as 
our target variable.
