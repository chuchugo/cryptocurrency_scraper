# Web scraper for bitcoin websites

## I. Major Features
### 1. current coin market price board
this is to get coin name, price, percentage change from cointelegraph.com

### 2. yahoo finance news collector for cryptocurrencies
this can be used to get the latest news about most cryptocurrencies, about 5 to 170 for each type of currency.
this program can be assigned with the number of top currencies the user want to learn about. 3 top types of currency would take about 20 seconds to get, with about 700 news articles.

## II. Toolkit
- Python (pandas)
- Jupyter Notebook
- Selenium for web cralwing

## III. How to run this program 
There are two main functions for each website. One is for structured data. One for unstructured data.

prices:
get_coin_prices()

news:
get_coin_news(top_N_coins)

Top_N_coins will take the number of top types of coins to retreive the news. The largest coverage is 200 types of coins.


--------
References:

https://selenium-python.readthedocs.io/navigating.html

https://www.scrapingbee.com/blog/selenium-python/

https://cointelegraph.com/price-indexes