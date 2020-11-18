# Udacity_Wrangle_and_Analyze_Data_Project
Repo for Udacity's data wrangling project as part of data analyst  Nanodegree

## Introduction
Real-world data rarely comes clean. Using Python and its libraries, you will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. This is called data wrangling. You will document your wrangling efforts in a Jupyter Notebook, plus showcase them through analyses and visualizations using Python (and its libraries) and/or SQL.

## The Data
The dataset that is used is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog.
The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets. Rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo) is extracted from each tweet's text to make this Twitter archive "enhanced." Of the 5000+ tweets, the data is filtered for tweets with ratings only (there are 2356).

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

