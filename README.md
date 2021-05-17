# WeStonks 2.0

## Team Members
* Christian
* Robel
* Felix

## Project description/outline
WeStonks 2.0 - Using Bitcoin valuation data, we will train a Machine Learning model to predict Bitcoin closing prices. We will take a data set of 5 years worth of Bitcoin close prices and benchmark it against our Linear Regression forecasting algorithm. We will backtest our model against Bitcoin price action.


##  Research Question to Answer
1. Is Linear Regression a good model for forecasting Bitcoin closing prices?
2. What is the best strategy, HODL or Linear Regression.


## Programs and Data Sets used
* Bitcoin Price Data
* Gemini
* Google Colab


## Tasks
1. Data gathering
2. Data cleaning
3. Run model
4. Present analysis 


Analysis: Our model predicted the closing prices of Bitcoin correctly 53% of the time. Which in reality, is better performing than many asset managers. our in-sample metrics was better fitted for our linear regression model than the out-of sample but they both indicate a poor predicting model. The best strategy thus was to HODL.

Our In-Sample Metrics:

* The In-sample score is 0.004185014042314528.
* The In-sample r2 is 0.004185014042314528.
* The In-sample mean squared error is 0.0017169056158605532.
* The In-sample root mean squared error is 0.04143555979904885.
* The In-sample standard deviation is 0.04152253709516725.

Our Out-of Sample Metrics: 

* The Out-of-Sample score is 0.0009721325388789559.
* The Out-of-Sample r2 is 0.0009721325388789559.
* The Out-of-Sample mean squared error is 0.0021471867578922543.
* The Out-of-Sample root mean squared error is 0.04633774657762561.
* The Out-of-Sample standard deviation is 0.0463602862282166.

The mean of the correct predictions is Abs Return    0.035205

The mean of the false predictions is Abs Return    0.031311
