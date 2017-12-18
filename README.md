# ethereum-cryptocurrency-analysis

Predicting Fluctuation in Ethereum Cryptocurrency Using Twitter Sentiment Analysis

Abstract:

With our study we intended to prove that it is possible to predict changes in the price of Ethereum cryptocurrency (also known as Ether, denoted by ETH) by analyzing Twitter sentiment. We first attempted to establish a linear relationship between Twitter sentiment and the change in the price of Ethereum. Having failed to do so, we used three labels for the change in price of Ethereum, increase (if price change is greater than zero), decrease (if price change is lesser than zero), same (if price change is exactly zero) and attempted to classify the trend according to these labels.

We use supervised machine learning algorithms such as Naïve Bayes Classification, k-Nearest Neighbors Classification and Neural Networks and used 4-fold cross validation on our models. While the other classifiers produced an accuracy of around 53%, our Naïve Bayes classifier gave us an accuracy of around 57%. Given that the majority class in the labels had a percentage of is around 52%, we cannot say that we have a robust model and are forced to conclude that with the data in hand, and the resources at our disposal, it is not possible to establish a relationship between Twitter sentiment and the change in Ethereum price. But the score for the Naïve Bayes classifier does indicate that we cannot eliminate the possibility of finding a relationship in the future.
