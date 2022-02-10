# Deeplearning-Homework

#### Background

Due to the volatility of cryptocurrency speculation, investors often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the Crypto Fear and Greed Index (FNG) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency. 

This assignment requires building and evaluation of deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data.

In this assignment, deep learning recurrent neural networks has been used to model bitcoin closing prices. One model will use the FNG indicators to predict the closing price while the second model will use a window of closing prices to predict the nth closing price.

#### Steps

- Prepare the data for training and testing
- Build and train custom LSTM RNNs
- Evaluate the performance of each model

#### Prepare the data for training and testing

#### Build and train custom LSTM RNNs

#### Evaluate the performance of each model

Finally, used the testing data to evaluate each model and compare the performance.

- Which model has a lower loss?
- Which model tracks the actual values better over time?
- Which window size works best for the model?

###### Using Closing Price

| Sample/Window Size | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |10|
|:------------|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|-:|
|Training Loss|0.1143|0.0858|0.0594|0.0509|0.0466|0.0463|0.0395|0.0398|0.0335|0.0331|   
|Test Loss    |0.0982|0.0683|0.0482|0.0329|0.0321|0.0314|0.0267|0.0279|0.0263|0.0243|

###### FNG

| Sample/Window Size | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |10|
|:------------|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|-:|
|Training Loss|||||||||||  
|Test Loss    |||||||||||
