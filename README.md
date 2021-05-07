# Predicting-the-future-Stock-Market-price-with-Markov-Chain

  A **stock market** or share market is the aggregation of buyers and sellers of stocks or 
  shares, which represent ownership claims on businesses; these may include securities listed 
  on a public stock exchange, as well as stock that are only traded privately. 
  Stockbrokerages and electronic trading platforms help in Investing in the stock markets. 
  Investment is usually made with an investment strategy in mind. It may be either to invest or 
  withdraw the shares while the share market rises and falls respectively.

  **Stock market prediction** is the act of trying to determine the future value of a 
company stock or other financial instrument traded on an exchange. The successful 
prediction of a stock's future price helps in designing suitable strategies which in turn yield 
significant profit. The efficient-market hypothesis suggests that stock prices reflect all 
currently available information and any price changes that are not based on newly revealed 
information thus are inherently unpredictable.

# **Dataset:**

  For any prediction historical dataset is required. The dataset taken for analysis and 
prediction is the historical data of ACC stocks. The data has 8 variables/features and around 2
4200 rows. The features are Date, Open, High, Low, close, Volume, dividends and stock 
splits.

# **Markov Chain:**

**Markov chain** is one of the most powerful tools in analytics and is successfully 
deployed by many companies. For example, the famous PageRank algorithm (Brin and Page, 
1998; Hayes, 2013) used by Google for ranking web pages is based on Markov chain model. 
Google’s Page ranking algorithm was one of the reasons why it was successfully able to 
compete with other search engines.

Let {Xn, n = 0, 1, 2,…} be a sequence of random variables observed at time n (= 0, 1, 2, …). 
For example, Xn can be a market share of a company at time n or number of customers 
waiting at a supermarket checkout counter at time n or value of a share at time n. The value 
of Xn at time n is called the state and the set of all possible values is called the state space 
(S).

# Output:
27 events
Accuracy: 51.24 %
![confusion matrix](https://user-images.githubusercontent.com/47297271/117461924-bbad7280-af6b-11eb-866b-bc5abc463f64.png)

# Conclusion:

This code consist of forming transition matrix of order 27(27 unique patterns) for both 
win situation and lose situation.

Then the dataset is splitted into training dataset (compressed_set) and validation 
dataset (compressed_set_validation) after implementing Markov chain provided an accuracy 
of 51% which is quite good for a real life dataset.






