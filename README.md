# Predicting-the-future-Stock-Market-price-with-Markov-Chain

A stock market or share market is the aggregation of buyers and sellers of stocks or 
shares, which represent ownership claims on businesses; these may include securities listed 
on a public stock exchange, as well as stock that are only traded privately. 
Stockbrokerages and electronic trading platforms help in Investing in the stock markets. 
Investment is usually made with an investment strategy in mind. It may be either to invest or 
withdraw the shares while the share market rises and falls respectively.
Stock market prediction is the act of trying to determine the future value of a 
company stock or other financial instrument traded on an exchange. The successful 
prediction of a stock's future price helps in designing suitable strategies which in turn yield 
significant profit. The efficient-market hypothesis suggests that stock prices reflect all 
currently available information and any price changes that are not based on newly revealed 
information thus are inherently unpredictable.
Dataset:
For any prediction historical dataset is required. The dataset taken for analysis and 
prediction is the historical data of ACC stocks. The data has 8 variables/features and around 2
4200 rows. The features are Date, Open, High, Low, close, Volume, dividends and stock 
splits.
Markov Chain:
Markov chain is one of the most powerful tools in analytics and is successfully 
deployed by many companies. For example, the famous PageRank algorithm (Brin and Page, 
1998; Hayes, 2013) used by Google for ranking web pages is based on Markov chain model. 
Google’s Page ranking algorithm was one of the reasons why it was successfully able to 
compete with other search engines.
Let {Xn, n = 0, 1, 2,…} be a sequence of random variables observed at time n (= 0, 1, 2, …). 
For example, Xn can be a market share of a company at time n or number of customers 
waiting at a supermarket checkout counter at time n or value of a share at time n. The value 
of Xn at time n is called the state and the set of all possible values is called the state space 
(S).
The process {Xn, n = 0, 1, 2, …} is a first-order Markov process if
Libraries Used:
• tqdm – tqdm uses smart algorithms to predict the remaining time and to skip 
unnecessary iteration displays, which allows for a negligible overhead in most cases.
• matplotlib - Matplotlib is an amazing visualization library in Python for 2D plots of 
arrays. Matplotlib is a multi-platform data visualization library built on NumPy
arrays and designed to work with the broader SciPy stack.
• pandas - pandas is a software library written for the Python programming language 
for data manipulation and analysis. In particular, it offers data structures and 
operations for manipulating numerical tables and time series.3
• numpy - NumPy is a library for the Python programming language, adding support 
for large, multi-dimensional arrays and matrices, along with a large collection of highlevel mathematical functions to operate on these arrays.
• datetime - A date in Python is not a data type of its own, but we can import a module 
named datetime to work with dates as date objects.
• randint - The randint() method returns an integer number selected element from the 
specified range.
• qcut - Quantile-based discretization function.” This basically means that qcut tries to 
divide up the underlying data into equal sized bins. The function defines the bins 
using percentiles based on the distribution of the data, not the actual numeric edges of 
the bins.
