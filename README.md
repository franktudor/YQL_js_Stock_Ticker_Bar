YQL JS Stock Ticker Bar
=======================

This tool uses Javascript to pull data (like price and other stock details) for presentation via a ajax/.json YQL call to Yahoo finance.

The file has examples that are currently calling indexes (indicies) like the Russell 2000, the S&P 500, NASDAQ 100 and some other single ticker symbols.

I am feeding a comma seperated list of stock symbols to return:
The title of the Ticker (name of index)
The current price
The percentage change

There are more stock details in the .json structure that can be used for other things like volume, daily highs and lows, opening price, etc.

The CSS creates a light red/green block behind the data and colors the font black plus dar red/green on the percentage text. 

This code is free to use. Feel free to fork it and make something fun for yourself.
