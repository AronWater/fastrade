Table of Content 
======================
- [Fastrade](#fastrade)
  * [Communication_Join_us](#communication-join-us)
  * [Purpose](#purpose)
  * [functionality](#functionality)
  * [installation](#installation)
  * [Reference](#reference)
  * [To do list](#to-do-list)


Fastrade         
======================

:star: Star us on GitHub 

[Fastrade](https://github.com/AronWater/fastrade/) is a trading system written in python with GUI extension in PYQT. 

從零開始寫起的python證據交易和可視化系統

## Communication_Join_us


| :memo:        |  [Slack](https://join.slack.com/t/fastrade/shared_invite/zt-eldmclmc-Jf~lo2kf~6q6eacR93n2ag)      |
|---------------|:------------------------|


| :point_up:    | Join us!在上方加入slack一起討論吧 |
|---------------|:------------------------|




## Purpose 
- Comparing the functionality and difference between the apis provided by the popular trading exchange.
- Combining those to form a system that could effectively retrieve market information from all of the working apis. 

## functionality 
Proposed accepted API (securities):


| Name | Description |
| --- | --- |
| [yahoo-finance](https://finance.yahoo.com/quotes/API,Documentation/view/v1)   |    You should know already |
| [Interactive Broker](http://interactivebrokers.github.io/tws-api/)  |   The REST API needs a pro subscription|
| [alpha vantage](https://www.alphavantage.co/)    |      providing free but limited usage per day|
| [futu](https://futunnopen.github.io/futu-api-doc/intro/intro.html)     |         pretty comprehensive api but without US market information|
|[td-ameritrade](https://developer.tdameritrade.com/apis)    | the documentation is not very well-written|
|[alpaca](https://alpaca.markets/)      |   simple|

Proposed accepted API (crytocurrency):

| Name | Description |
| --- | --- |
| [bitmex](https://www.bitmex.com/app/apiOverview)   |  placeholder   |
| [binance](https://binance-docs.github.io/apidocs/spot/en/#change-log/)  |   placeholder|
| [huobi](https://huobiapi.github.io/docs/spot/v1/en/#change-log)    |     placeholder|
| [bitstamp](https://www.bitstamp.net/api/)     |    placeholder|


## installation
have python 3.5 or above installed


## Reference
* [freqtrade](https://github.com/freqtrade/freqtrade) 
* [vnpy](https://github.com/vnpy/vnpy)
* [backtrader](https://github.com/mementum/backtrader)
* [backtesting.py](https://github.com/kernc/backtesting.py)
* [High-Frequency-Trading-Model-with-IB](https://github.com/jamesmawm/High-Frequency-Trading-Model-with-IB)

## To do list
* all the above
* with docker support 
* with nice database connection ( either local server or cloud )
* with crytocurrency functionality ( Binance, Huobi, Kraken, etc)

