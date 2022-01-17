# UTweet10

A toy dataset for Tweet summarization. This dataset is used in **'[A survey on different dimensions for graphical keyword extraction techniques](https://link.springer.com/content/pdf/10.1007/s10462-021-10010-6.pdf)'** which is published in_ Artificial Intelligence Review_. We use this dataset to implement different graph-based keyword extraction techniques over Microblogs as compared to other well-formed datasets.

The UTweet10 refers to the Un-balanced set of data for Tweets over 10 topics. UTweet10 dataset is extracted between 02 December 2019 and 04 December 2019 which contains 10 topics having 1000 Tweets for each topic. Out of these 10k Tweets, unique Tweets are extracted for each instance which does not contain any repetitive information. This gives unbalanced dataset which contains diferent number of Tweets for each topic with an average of 246 Tweets. The dataset is extracted using Tweepy API and Python 2.7 version from Twitter. The collection of Tweet IDs and ground truth key-phrases is made available online
