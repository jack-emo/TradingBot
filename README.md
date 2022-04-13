# Welcome to my Interactive Brokers Trading Bot

### Abstract
Ever wanted to beat the market without actually putting in effort??? Thanks to this trading bot, you can now become the wolf of wall street without moving a finger. By using this bot all you need to have is a bank account with money in it and this bot will turn that money into more money.
(Note: This bot was created to enhance my understanding of Python3 libraries, as well as to gain some context as to how APIs work, this should not be used as a method of income and should be taken with a grain of salt).

### Built with
* ibapi
* numpy
* pandas as pd
* pytz

### Features
* Note: Must have a working Interactive Brokers account in order to use this Bot
* Interactive Brokers must be running in the background in order for this bot to work
* Trades a given security (i.e. Stock, Option, ETF) against a 5-day simple moving average to generate the most alpha
* Executes stop-loss orders when profit falls below 1%, and executes a sell order when the equity value reaches > 1%

### Usage
~/tradingBot python3 Trading.py
