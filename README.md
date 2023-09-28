# nse_stockprice_model
The goal of the project was to try and predict the stock prices of a bunch of listed companies in the Indian NSE. The data used in the project was from kaggle.
The apporach taken in modelling was a time series approach in terms of the train test split, but the applied algorithm was CatboostRegressor.
The output of the model clearly indicates that their is model overfitting even after experimentation with various approaches to handling overfitting. The recommended solution to improve model performance is to get more data that informs the model of the macroeconomic conditions that affect share prices.
