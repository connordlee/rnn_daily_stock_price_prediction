# Using an RNN to Predict TD's Stock From Historical Data
This repository focuses on developing an RNN using tensorflow that predicts TD's stock price using historical data from various sources. The goal of this project was to gain experience developing recurrent neural networks (RNN's) by developing an RNN to predict the stock price for the TD Bank stock traded on the Toronto Stock Exchange (TSX) while taking into account the historical relationiship of TD with various factors. The various factors taken into account are discussed further in [rnn_daily_stock_price_prediction.ipynb](https://github.com/connordlee/rnn_daily_stock_price_prediction/blob/master/rnn.ipynb). The links to the various datasets are also provided in [rnn_daily_stock_price_prediction.ipynb](https://github.com/connordlee/rnn_daily_stock_price_prediction/blob/master/rnn.ipynb) however the datafiles used can also be downloaded from the [data](https://github.com/connordlee/rnn_daily_stock_price_prediction/tree/master/data) folder in this repository.

The primary learning objecties from this project were the following:
* Learn how to develop an RNN that uses data from multiple sources
* Learn how to implement cross validation with a neural network

However through development of this project I learned new methods of working with the following packages:
* Tensorflow and Keras
* scikit-learn

A more detailed discussion of the steps taken to optimize the RNN with cross validation, the steps taken to implement the RNN, the results from this project, and potential future work improvements are included in [rnn_daily_stock_price_prediction.ipynb](https://github.com/connordlee/rnn_daily_stock_price_prediction/blob/master/rnn.ipynb) in this repository.
