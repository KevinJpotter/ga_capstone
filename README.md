# Stock Algorithm Using Zipline (unfinished)



Create a few basic trading algorithms using zipline. While exploring 


## Project Outline

1. Use Zipline to creat 3-4 base models using base statistics
    a. Algorythm that rebalences weekly (long / short)
    b. Algorythm that rebalences daily  (long /short)
    c. Algorythm that buuys based on moving averges (long)
    d. TBD


2. Ideas to imporve efficency of model by creating a model that masks the bucket of equitites to chose from when rebalencing
    - Nueral Networks (RNN)
    - Try to involve an ARIMA model (not sure yet)
    - Linear Regression
    - Unsupervised clustering base on fundamentals
    - NLP of news articles 



## Data Details

Suggested backtesting rules of thumb models daily trading 1 year for every feature used in model, as much as you can for monthly trading

As much as you can for monthly trading models

Technical - Open, close, volume, high, low and price for each day for 3,000 stocks Date Ranges (1/1/1992 - 1/1/2018)

Fundamental - SEC earnigns reports from there website on the list of 3,000

Sentiment - create a sentiment funciton that further infuences statistics (Sentdex)


#### Workflow

1. Get hardcopy of data from Quandl API and list of SID's in file (tonight)
2. Build the simple models with (deadline Tuesday 5/7)
3. Look into getting fundamentals from either (deadline Thursday 5/9):
    - Robin Hood API
    - SEC website scrape per RNN lecture
4. Explore Models and improvements via screeeners listed above (deadline Monday 5/13)
5. Work on visualizations / conclusions / presentation  (deadline in class Thursday 5/15)