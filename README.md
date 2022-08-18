# Project Overview: Introduction
Real-world data rarely comes clean. Using Python and its libraries, you will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. This is called data wrangling. You will document your wrangling efforts in a Jupyter Notebook, plus showcase them through analyses and visualizations using Python (and its libraries) and/or SQL.

The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively for you to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. More on this soon.

## What Software do I need?
I worked outside of the Udacity classroom, the following software requirements apply:
<ul>
<li>Need to be able to work in a Jupyter Notebook on your computer. Please revisit our Jupyter Notebook and Anaconda tutorials earlier in the Nanodegree program for installation instructions.</li>
<li>
The following packages (libraries) need to be installed. You can install these packages via conda or pip. Please revisit our Anaconda tutorial earlier in the Nanodegree program for package installation instructions.

* pandas
* NumPy
* Matplotlib
* seaborn
* csv
</li>
<li>Need to be able to create written documents that contain images and you need to be able to export these documents as PDF files. This task can be done in a Jupyter Notebook, but you might prefer to use a word processor like Google Docs, which is free, or Microsoft Word.</li>
</ul>

# Project Details: How did I Complete this Project?
The tasks in this project are as follows:
## Step 1: Gathering data
In this section, three pieces of data was gathered.

The WeRateDogs Twitter archive - This file (archive.csv) was downloaded manually and consists of basic tweet data for 2300+ tweets from WeRateDogs.

The tweet image predictions - This file (image_predictions.tsv) is present in each tweet according to a neural network. It is hosted on Udacity's servers and was downloaded programmatically.

Additional data from the Twitter API - Gather each tweet's retweet count and favorite ("like") count at the minimum. Using the tweet IDs in the WeRateDogs Twitter archive, query the Twitter API for each tweet's JSON data using Python's Tweepy library and store each tweet's entire set of JSON data in a file called tweet_json.txt file.

## Step 2: Assessing data
All three pieces of data obtained from the gathering phase was loaded into individual pandas data frame and assessed visually and programmatically for quality and tidiness issues.

## Step 3: Cleaning data
Clean all of the issues you documented while assessing programmatically. This includes:

><ul><li>Dropping unnecessary columns from the tables.</li></ul>
><ul><li>Removing rows that consisted of retweets.</li></ul>
><ul><li>Removal of rows with duplicate information.</li></ul>
><ul><li>Deleted rows that did not have any dog predictions at all.</li></ul>
><ul><li>Combining all three data frames into a single data frame.</li></ul>
## Step 4: Storing data

## Step 5: Analyzing and Visualizing data

## Step 6: Reporting
<ul>
<li>Your data wrangling efforts</li>
<li>Your data analysis and visualizations</li>
</ul>
