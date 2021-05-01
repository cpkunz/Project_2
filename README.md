# Project_2
## CRF ETF, The Disaster's ETF

## Overview

Create an ETF with a basket of equities that are impacted by the weather disasters. 

Working theory is that weather events such as hurricanes impact certain sectors of the stock market. That said
we want to predict future price movements using Machine Learning and create a trading algorithm.

## Method
Using news article data we will use NLP to create a dataframe to analyze sentiment and compare that to 
weekly pct.change() in the price movement of our basket of stocks. Using a weather disaster dataframe we will
compare the severity of the event and its impact to the valuation of the equities.

Compare our strategy against a rolling 50/100 day module and create Entry/Exit signals for the ETF based
on the weather and sentiment analysis.

## Data
Dates: 1999-2019, 20 years of weather disaster data, namely tropical storms.
Region: North and Central America including the Caribbean
Stock market data:

 - S&P 500
 - Individual equities
 - Sector data

Build a basket of stocks trading on US exchanges:
- Energy
- Consumer Staples
- Home Improvement
- Construction/Engineering
- Industrials

Analyze weekly stock data vs weather event data to look at the pct.change

Look at sentiment over time; look at the ratio of positive and negative sentiment over time

## Technology:

- Google Colab
- Alpha Vantage API
- NewsAPI
- NWS API
- EM-DAT Public
- Tensorflow/keras
- nltk


## Team Members:
- Christian Kunz
- Felix Llamas
- Robel Argea
