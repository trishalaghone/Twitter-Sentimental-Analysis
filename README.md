# Twitter-Sentimental-Analysis

Sentiment analysis (or opinion mining) is a natural language processing technique used to determine whether data is positive, negative or neutral. Sentiment analysis is often performed on textual data to help businesses monitor brand and product sentiment in customer feedback, and understand customer needs.

Since customers express their thoughts and feelings more openly than ever before, sentiment analysis is becoming an essential tool to monitor and understand that sentiment. Automatically analyzing customer feedback, such as opinions in survey responses and social media conversations, allows brands to learn what makes customers happy or frustrated, so that they can tailor products and services to meet their customers’ needs.


# Problem Statement

The objective of this task is to extract the features of tweets and analyze the sentiment of the tweets as positive and negative. Formally, given a training sample of tweets and labels, where label ‘1’ denotes the tweet is negative and label ‘0’ denotes the tweet is positive, your objective is to predict the labels on the given test dataset.

Note: The evaluation metric from this practice problem is F1-Score, confusion matrix, accuracy of the different maching learning models used. 

# Dataset Information 
The training dataset is expected to be a csv file of type tweet_id,sentiment,tweet where the tweet_id is a unique integer identifying the tweet, sentiment is either 0 (positive) or 1 (negative), and tweet is the tweet enclosed in "". Similarly, the test dataset is a csv file of type tweet_id,tweet. 


# Data Preprocessing and Cleaning 

The objective of this step is to clean noise those are less relevant to find the sentiment of tweets such as punctuation, special characters, numbers, and terms which don’t carry much weightage in context to the text. 

# Data Visualization

Visualized cleaned tweets for deeper analysis and understanding. Created graphs which answer some questions related to the data such as: 

What are the most common words in the entire dataset? What are the most common words in the dataset for negative and positive tweets, respectively? How many hashtags are there in a tweet? Which trends are associated with my dataset? Which trends are associated with either of the sentiments? Are they compatible with the sentiments?
