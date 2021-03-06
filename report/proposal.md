# TITLE: Detect Racist and Sexist Tweets  
## Team Members: Jeffrey Wang  
## Date:  10/22/2020

# Project Description
## Probelm Statement and Motivation
The objective of this task is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify racist or sexist tweets from other tweets.

Formally, given a training sample of tweets and labels, where label '1' denotes the tweet is racist/sexist and label '0' denotes the tweet is not racist/sexist, your objective is to predict the labels on the test dataset.

Then I want to run a collection(maybe 100 or so tweets from a chosen time period) of Trump tweets and see how many are racist/sexist compared to Obama's tweets, maybe some other celebrities as well. and then people will be able to select any twitter handle, maybe their own handle up to past 7 days. (Twitter APIs limit). Then automatically run inference on the past 0-10 tweets and print each tweet with results.

I think it is important for AI to be able to detect hate speech. Social media companies are not doing a good job keeping hate from their sites. I want to explore how well a SOTA NLP model will be able to detect hate speech using just open source projects and a small dataset.

## Introduction and Description of Data
The dataset is 31,962 tweets labeled as racist/sexist or not. Sentiment analysis is a challenging task, should be fun. 

# Plan
Google Colab
Simple Transformers and HuggingFace
Viola

# References:
https://datahack.analyticsvidhya.com/contest/practice-problem-twitter-sentiment-analysis/#ProblemStatement  
https://github.com/ThilinaRajapakse/simpletransformers  
https://colab.research.google.com/notebooks/intro.ipynb#recent=true
https://www.kaggle.com/datacrux/barack-obama-twitterdata-from-20122019
