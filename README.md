pinkfish
======

**07-20-2020: Add momentum-pem example - shows how to include indicators in a portfolio**  
**07-20-2020: Add Momentum Indicator**  
**07-16-2020: Add Margin (leverage) cabability**  
**07-16-2020: Add "performance per symbol" and correlation map cababilities**  
**06-23-2020: Add ability to have long and short position in same security simultaneousl**  
**06-22-2020: Add Shorting cabability, i.e. (see short-sell example; portfolio example)**   
**06-13-2020: Add Portfolio cabability, i.e. multiple stocks at the same time**     

A backtester and spreadsheet library for security analysis.

Why another python backtesting library?  How is pinkfish different?
Simple, I couldn't find a python backtesting library that allowed me to backtest intraday strategies with daily data.  Even simple strategies like 'buying on the close' on the SAME day a 'new 20 day high is set' were not allowed.  Additionally, I was put off by the complexity of some of the libraries available, and wanted something simple, that doesn't get in the way, and just allows me to test my trading ideas.  One user commented that Pinkfish is "very lightweight and to the point".  I didn't set out to write a new backtesting library, but I had to.  Daily data is free; minute and tick data are typically not.  Using minute and tick data can require hours to run vs seconds for daily data.

Some of the key features of pinkfish:
 - leverages pandas for dataframe, spreadsheet like features
 - leverages matplotlib for making financial graphs
 - uses ta-lib to easily implement technical indicators
 - uses daily data (vs minute or tick data) for intraday trading
 - uses free daily data from yahoo finance
 - simple to use python API
 - backtest single stock/ETF strategy or a portolio (basket of stocks/ETFs)
 - backtest short selling strategies and simulate trading with margin
 - write optimizers to select the best parameters
 - create spreadsheets within Jupyter Notebook by utilizing pandas dataframes and itable formatting

## Installation
Follow the installation instructions located at:
https://fja05680.github.io/pinkfish/

## Examples
 - [buy-and-hold](https://fja05680.github.io/pinkfish/examples/buy-and-hold.html) - an example illustrating the basic buy and hold strategy
 - [spreadsheet](https://fja05680.github.io/pinkfish/examples/spreadsheet.html) - make a read only spreadsheet within jupyter notebook
 - [golden-cross](http://fja05680.github.io/pinkfish/examples/golden-cross.html) - an example illustrating the classic long term trading algorithm
