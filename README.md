# StockCryptoPrediction_UsingML

Python notebook to predict the prices of stock/crypto for the next day.

Does the following:
1. Downloads the last 6-years daily data using yfinance 
2. Adds technical indicators like RSI, MACD, moving average, Bollinger Bands etc based on the data
3. Uses this data to train ML models like random forest, gradient boost, XGB, prophet, minirocket etc.
4. Runs the trained ML model on last 5-days data for back testing

