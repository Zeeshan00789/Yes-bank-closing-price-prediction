# Yes Bank Stock Price Closing Prediction

## Problem Statement

Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations.This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock’s closing price of the month.

## Features in Dataset

Date: It specifies the month and year of a particular price.

Open: it specifies the opening price of the stock in that month. (Numeric)

High: it specifies the highest price of a stock in that month. (Numeric)

Low: it specifies the lowest price of a stock in that month. (Numeric)

Close: it specifies the close price of a stock in that month. (Numeric)

### Summary

The term stock price refers to the current price that a share of stock is trading for on the market. The price of a stock will go up and down in relation to a number of different factors, including changes within the economy as a whole, changes within industries, political events, war, and environmental changes. In this project, we are predicting yes bank stock closing price with the help of the regression models.  The given dataset consists of features such as the open, close, low, and high prices of the stock of yes bank on a monthly basis.
We followed step-by-step processes for the project like data collection, data cleaning, EDA, Visualization, Model Training and Testing, Hyperparameter Tuning, and Evaluation. In EDA we divided the analysis into several parts to get a better idea of the data. We checked the data distribution with the help of distplot, and normalize the data with the help of log transformation. The dependent variable was the closing price, we plotted a scatter plot of ‘open’, ‘low’, and ’high’  against ‘close’. we found that the relation between them was linear. 
We split the dataset into two parts a training dataset (80%) and a testing dataset (20%). The model gets trained from the training data, after training we use regression models such as linear regression, lasso regression, ridge regression, cross-validation and elastic net one by one and evaluated the results.
The test results of all the regression models are evaluated and compared. We checked performance metrics such as R2, adj R2, MSE, and RMSE etc. Unfortunately, the results were not up to the mark with linear regression, ridge and lasso regression.
Further, we tried other models such as random forest and Xgboost. With the help of this model, we got better R2 scores and metrics.


Here is the presentation link:

https://github.com/Zeeshan00789/Yes-bank-closing-price-prediction/blob/main/Presentation%20YES%20Bank%20Stock.pdf
