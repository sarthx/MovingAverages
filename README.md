# MovingAverages
**INTRODUCTION**

In this project, I did technical analysis of stock prices using Python code using the Open, High, Low, Close, and Volume (OHLCV) stock data. I integrated the yahoo finance library to gather the required close prices of a company. For development I used a Technical Analysis library named ta which uses the financial time series datasets (open, close, high, low, volume) and is built on the Python Pandas library.

```pip install talib```

TA-Lib is an open-source python library that is used in analyzing the stock market's historical data like share price, volume, etc. in order to predict the future price.

```pip install yfinance```

Yfinance is a python package that enables us to fetch historical market data from Yahoo Finance API.

```pip install matplotlib.pyplot```

Matplotlib.pyplot library is used in mathematical expression such as plotting, histogram, scatter etc

First we download all the data of tesla share in a given range of time.

Secondly, we plot the ochl(opening, closing, high, low)  data of tesla share in a graph.

After that we plot the line of exponential moving average and simple moving average of tesla share in a graph.

finally we compare the ema vs sma if ema is cut the sma with upward direction then it means the stock is in uptrend and if ema is cut the sma in downward direction then it means the stock is in downtrend.
