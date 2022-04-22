# 📖 Overview

This Jupyter Notebook uses the python programming language to explore the extraction of tweets using the tweepy API, in order to collect the trending topics of the day and their information, store them in the non-relational MongoDB database, and later use the trending topics to create an image using the WordCloud library, where the size of each word is determined by the tweet_volume.

# 📦 Dependencies

- csv
- datetime
- json
- matplotlib
- pandas
- pymongo 
- tweepy
- wordcloud 

# 💻 Usage
1. To use this project it is necessary to have a Twitter Developer account, student registration can be done for free [here](https://developer.twitter.com/en "here");
2. Obtain the authentication keys for connecting to the official Twitter API;
3. Store the authentication keys in the .csv file twitter_keys.csv;
4.	Install the dependencies;
5.	Run Jupyter Notebook in terminal to see the code in your browser.