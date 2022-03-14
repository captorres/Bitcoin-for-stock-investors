# Bitcoin for stock investors

## Project motivation

We have seen in the last couple of years a growing interest in cryptocurrency shown particularly by equity investors. This is probably related not only to the fact that both asset classes share common features as high volatility and, therefore,  potentially great returns, but also for the possibility of having cryptos, specially Bitcoin, as a hedge for stock markets.

The purpose of this analysis is to explore these issues. More precisely, to search for evidences that can help answering the following questions:

1. How does Bitcoin’s price behavior compares to stocks’?
2. Can Bitcoin be considered a hedge for stocks?
3. How does the correlation between Bitcoin and stock returns behave on stress periods?

Especial attention is given to the hedge hypothesis. This matter concerns not only equity investors, it’s extremely important for understanding Bitcoin expected price behaviors.


## Data

Bitcoin is the oldest and still a highly negotiated cryptocurrency. In other words, it has the longest historical data and a high liquidity, and that’s why it is the currency chosen for this study. To represent stock market’s behavior the ACWI and the S&P500 indexes are used. The former is a global index, and the latter is recognized as the most important local stock index in the world, representing the American equity market.

So the data used in this analysis are time series of Bitcoin's daily prices and of the stock markets' indices S&P500 and ACWI. These information were downloaded from the following sources:

* S&P: https://www.spglobal.com/spdji/en/indices/equity/sp-500/#overview
* Bitcoin: https://fred.stlouisfed.org/series/CBBTCUSD
* ACWI: https://www.nasdaq.com/market-activity/funds-and-etfs/acwi/historical

They are stored in files that can be accessed in this repository: CBBTCUSD_fred.csv (Bitcoin), SP500.xlsx (S&P) and ACWI_Nasdaq.csv.

After data treatment, the time horizon considered in the study was from February 3, 2015 to January 31, 2022.


## Methodology and packages

As the purpose of the study is to simply analyze behavior of historical data, only exploratory data analysis were accomplished and simple statistics such as mean, standard deviation and correlation coeficient were calculated. Visual representation of the results are important part of the project. Application of machine learning algorithms was not necesary.
Python 3 was the software used, more precisely the packages:
* Pandas and Numpy for data manipulation and calculations
* Matplotlib, Seaborn and Plotly for visualization

All the process of importing packages, reading and treating data, generating insights and their visual representations can be explored in details on the notebook present in this repository


## Results

The results generated from this study were part of a blog post that can be accessed [here](https://medium.com/@cadtorres22/bitcoin-for-stock-investors-9d267f835b5d).
