# Udacity_Wrangle_and_Analyze_Data_Project
Repo for Udacity's data wrangling project as part of data analyst  Nanodegree

## Introduction
The goal of this project is to assess and clean at least 8 quality issues and at least 2 tidiness issues in this WeRateDogs tweets datasets.

## The Data
The dataset that is used is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog.
The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets. Rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo) is extracted from each tweet's text to make this Twitter archive "enhanced." Of the 5000+ tweets, the data is filtered for tweets with ratings only (there are 2356).

### Gathering Data for this Project
There are three main pieces of data that need to be gathered for this project:
- The WeRateDogs Twitter archive. This data is provided by Udacity as a csv file: twitter_archive_enhanced.csv
- The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network. This file (image_predictions.tsv) is hosted on Udacity's servers and should be downloaded programmatically using the Requests library and the following URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv
- Each tweet's retweet count and favorite ("like") count at minimum, and any additional data one finds interesting. Using the tweet IDs in the WeRateDogs Twitter archive, the Twitter API is queried for each tweet's JSON data using Python's Tweepy library and each tweet's entire set of JSON data is stored in a file called tweet_json.txt file. Each tweet's JSON data is then written to its own line. This .txt file is read line by line into a pandas DataFrame with (at minimum) tweet ID, retweet count, and favorite count.

### Additional Data via the Twitter API
Retweet count and favorite count are gathered from Twitter's API using the WeRateDogs Twitter archive and specifically the tweet IDs within it.

## Software Requirements

You need to be able to work in a Jupyter Notebook on your computer. 
The following packages (libraries) need to be installed. 
- pandas
- NumPy
- requests
- tweepy
- json

