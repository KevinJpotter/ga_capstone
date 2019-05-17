# Introduction to Quantitative Finance

This collections of notebooks outlines my exploration of quantitative finance and the tools associated with it.


## Tools

To use this notebook you will need a quandl api key which can be obtained for free [here](https://www.quandle.com/)

The class in this notebook pings the quandl API for pricing data on a stock. The class can then process the data using the ARIMA and holt winters models in the statsmodels library. The class also contains methods to visually represent the pricing data via individual moving average plots or a summary including four different moving averages and an autocorrelation plot.

Some updates to the code to come will be expanding the number of time series models available and make the plots more interactive.

libraries needed for use:
    - statsmodel
    - Pandas
    - Matplotlib
    - Seaborn
 

## Research

To use the notebooks in the next two folder you will need a quantopian account you can obtain for free [here](https://www.quantopian.com/home)

In these notebooks it shows how to access information on individual securities as well as create a filters to then use a signals to trade using their pipeline feature. Within the pipeline you can combine features and filters to the pool of securities to create a custom signal for trading. 

It provides easy to use illustrations of your test signal including calculations of beta and alpha that can be visually represented through the alphalens tool. tests for alpha and beta over different time period. It allows you too easily manipulate and test your strategies before building out something executable.  


## Algorithms

These notebooks should be specifically ran in the quantopian algorithm environment. There they can be backtested, added to, and manipulated at your discretion. 

These strategies are fully executable through their platform. They provide examples common technical trading signals like momentum factor effect and mean reversion effect. The strategies are rather simple and are meant to showcase how the platform executes trades and passes along information within the environment. Tutorial with step by step walkthrough on how to use the platform can be found [here](https://www.quantopian.com/tutorials)
