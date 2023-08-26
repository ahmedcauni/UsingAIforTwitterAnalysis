# Overview
This repository contains Python code to perform sentiment analysis on tweets. It reads data from multiple CSV files containing tweets, preprocesses the text, and then applies sentiment analysis. The analysis results are visualized using bar charts and pie charts.

#Text Cleaning
-Remove URLs
-Remove emojis
-Remove mentions, hashtags, and special characters
-Tokenize the text
-Remove punctuation and stopwords

#Sentiment Analysis
I used the VADER sentiment analyzer from the NLTK library to perform sentiment analysis. Each tweet is assigned a sentiment score, and based on that score, a sentiment label ('positive', 'neutral', 'negative') is given.
