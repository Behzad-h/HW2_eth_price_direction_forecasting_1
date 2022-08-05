# Ethereum Price Change Direction Forecasting: Simple Logistic Regression Model


In this project, we aim at forecasting the direction of the price change of Ethereum. We extract the historical data (daily values) of ETH prices from the Yahoo Finance repository, preprocess the data, and fit a simple logistic regression model over the data. In the preprocessing stage, we extract the direction of the ETH price change (increase, decrease, or fixed) on each day. So, we are dealing with a classification problem. We also implement a window generation function to be able to forecast the next day's price change direction based on the previously recorded data.


-----------------------------------------------------
This project is adapted from the following webpage:

https://blog.faradars.org/%D9%BE%DB%8C%D8%B4-%D8%A8%DB%8C%D9%86%DB%8C-%D8%AC%D9%87%D8%AA-%D9%82%DB%8C%D9%85%D8%AA-%D8%AF%D8%B1-%D9%BE%D8%A7%DB%8C%D8%AA%D9%88%D9%86/