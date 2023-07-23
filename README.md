Petrol Price Forecasting using LSTM, ARIMA, and Auto Keras

Overview -
The Petrol Price Forecasting project aims to predict the prices of petrol for upcoming dates using various forecasting models. We will utilize Long Short-Term Memory (LSTM) 
and Autoregressive Integrated Moving Average (ARIMA) models to make predictions. Additionally, we will explore the power of Auto Keras, an AutoML library, to automate the
model building process and find the best model for petrol price forecasting.


Task Description -
The main task of this project is to analyze historical petrol price data and develop forecasting models to predict future petrol prices. The dataset will contain historical 
petrol prices, preferably with timestamp information, for a certain duration.


Steps Involved
1. Data Analysis - In this initial step, we will perform exploratory data analysis on the provided historical petrol price dataset. We will visualize the data, look for
  any trends or patterns, check for seasonality, and identify potential outliers.

2. Model Building and Predictions using ML Techniques - The first forecasting approach will involve using traditional ML techniques, such as LSTM and ARIMA, to build predictive
   models. LSTM is a powerful deep learning model that can capture temporal dependencies in time series data, while ARIMA is a classic time series model well-suited for stationary
   data. We will train these models on historical petrol price data and evaluate their performance using appropriate metrics, such as Mean Squared Error (MSE) or Root Mean Squared
   Error (RMSE).

3. Model Building and Prediction using Auto Keras (Auto ML) - Auto Keras is an AutoML library that automates the process of selecting the best model architecture and hyperparameters
   for a given task. In this step, we will leverage Auto Keras to build an automated petrol price forecasting model. Auto Keras will explore different neural network architectures
   and tune hyperparameters to find the optimal model for our dataset. 


We will then compare the performance of the Auto Keras model with the LSTM and ARIMA models to determine which approach yields the most accurate petrol price predictions.


Evaluation Metrics -
To assess the performance of our forecasting models, we will use metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE). 
These metrics will help us understand how well our models perform in predicting petrol prices for upcoming dates.
