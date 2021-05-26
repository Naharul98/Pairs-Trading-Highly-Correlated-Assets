# Pairs-Trading-Highly-Correlated-Assets
Developing and backtesting performance of a market neutral trading strategy which aims to exploit temporary anomalies in correlation between 2 pair of assets.

![Example Comparision ScreenShot](https://github.com/Naharul98/Pairs-Trading-Highly-Correlated-Assets/blob/main/Screenshot/screenshot.jpg?raw=true)

## Project Demo



## About the project

More often than not, asset prices in the stock market follow each other. When the index goes up, it is highly likely other stocks (even the ones not in the index) will follow as well. The strategy aims to exploit this pattern by betting on *mean reversion.*

## Strategy Description
* Observe price correlation of different assets in the market and pick a pair which has a high positive correlation with each other.
* When the correlation breaks, make a bet that eventually things will get back to the usual state. i.e: revert back to the mean
* Example backtest of the strategy is demonstrated in the Jypyter Notebook Demo

## Libraries used
+ Yfinance
+ Pandas
+ Talib
+ Numpy
+ Plotly
+ Scipy
+ Backtesting.py
+ Seaborn
