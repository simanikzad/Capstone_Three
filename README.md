# Capstone Three Project

# ⏳  Time Series Stock Price Prediction

This repository contains analysis, visualization, transform and forecasting models that are often used to predict time series data. I am using 3 tech company's stock price data, which includes, Apple, Google, Microsoft from 'Yahoo Finance'. My goal is to showcase how to model time series from scratch. This repository consists of 5 different notebooks (aside from the ReadME);
  - Presentation Slide PDF file 
  - Three notebooks, showcase LSTM model for each three stocks
  - Main notebook, consists of data analysis, ARIMA model for all three stocks, and summary of my final findings



# 📂 Dataset
The historical dataset that was used from ‘Yahoo Finance’ consists of few features like high, low, open, close, adj close value of stock prices, volume of shares traded, etc. I have picked 3 different stocks, in the same industry to compare the performance of them closely and to see if our models work well with all of our data. There were few features that were missing from our data, which I added to our analysis section.


# 📊 Data Analysis and Data Visualization
In this section I tried visualizing the 5 year performance of 3 stocks next to each other, since our data that was collected from 'Yahoo Finance' was limited, some additional features were created for our analysis section, which are; 'Daily Percent Change', 'Daily Total Traded Amount', '50-day Moving average', 'Daily Returns', 'Cumulative Return'.



# 📚 Preprocessing & Transforming Our Data
 
 **Time Series Decomposition**
 
  - Seasonality (does our data have seasonality pattern) - ARIMA
  - Trend (can our data be defined by a trend) - ARIMA
  - Scale our data - LSTM
  - Split our data into train and test - LSTM & ARIMA

**Stationarity**

Methods we use to determine if our data is stationary - ARIMA
  - Dickey Fuller Test
  - ACF Plot

**Making our Data Stationary**

In order to create ARIMA model, our data must be stationary;
  - Find returns on our timeseries
  - Find Order of differencing



# 📉 Model Creation
  - ARIMA Model
  - LSTM Model 
  
  
# 🔎 Model Evaluation
  - Picking different parameters (parameter tuning) to find the best LSTM model
  - Picking different parameters to create our best ARIMA model
  - Using plot predict to visualize and compare our actual data and the prediction for both models
  - calculate the RMSE for both of our models
  
# 📑 Conclusion
  - We can see from our plots from both ARIMA and LSTM model that, our prediction perfectly fits to the actual data
  - I used the RMSE metric to evaluate and compare both models, we can see that the ARIMA model gave us better score compare to LSTM model, as a result, I picked ARIMA model as our best model for our forcasting
 
# ↗️ Future Improvements
  For future work, deep learning models could be developed by collecting more data, such as; financial news articles, along with financial parameters such as profit and loss statements, etc for possibly better results.
 
   
  
