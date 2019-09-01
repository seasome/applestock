# apple stock ai
Stocks Analysis with Pandas and Scikit-Learn
Analyse, Visualize and Predict stocks prices quickly with Python

<img width="1440" alt="Screen Shot 2019-09-01 at 11 21 21 AM" src="https://user-images.githubusercontent.com/47608960/64082307-c3f6da00-ccc1-11e9-917f-2b3b392394db.png">


##Pandas web data reader is an extension of pandas library to communicate with most updated financial data. This will include sources as: Yahoo Finance, Google Finance, Enigma, etc.
We will extract Apple Stocks Price using the following codes:

'''
import pandas as pd
import datetime
import pandas_datareader.data as web
from pandas import Series, DataFrame


start = datetime.datetime(2010, 1, 1)
end = datetime.datetime(2017, 1, 11)

df = web.DataReader("AAPL", 'yahoo', start, end)
df.tail()
'''



# Liscense
https://towardsdatascience.com/in-12-minutes-stocks-analysis-with-pandas-and-scikit-learn-a8d8a7b50ee7
