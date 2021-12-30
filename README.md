# Tweeter-Sentiment-Analysis

## Overview

NLP-based Sentiment Analysis technique can predict sentiment for unstructured data.

The objective of this task is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify racist or sexist tweets from other tweets.

Formally, given a training sample of tweets and labels, where label '1' denotes the tweet is racist/sexist and label '0' denotes the tweet is not racist/sexist, our objective is to predict the labels on the test dataset.

For training the model, we provide a labeled dataset of 31,962 tweets. The dataset is provided in the form of a CSV file with each line storing a tweet id, its label, and the tweet.

**Content**

Full tweet texts are provided with their labels for training data.
Mentioned users' username is replaced with @user.

**Acknowledgements**

Dataset is provided by Analytics Vidhya

https://www.kaggle.com/arkhoshghalb/twitter-sentiment-analysis-hatred-speech?select=test.csv
