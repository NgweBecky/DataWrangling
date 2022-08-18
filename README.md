# Project Overview: Introduction
Real-world data rarely comes clean. Using Python and its libraries, you will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. This is called data wrangling. You will document your wrangling efforts in a Jupyter Notebook, plus showcase them through analyses and visualizations using Python (and its libraries) and/or SQL.

The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively for you to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. More on this soon.

## What Software do I need?
I worked outside of the Udacity classroom, the following software requirements apply:
<ul>
<li>You need to be able to work in a Jupyter Notebook on your computer. Please revisit our Jupyter Notebook and Anaconda tutorials earlier in the Nanodegree program for installation instructions.</li>
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


>I recommend installing [Anaconda](https://www.continuum.io/downloads), which comes with all of the necessary packages, as well as IPython notebook.

## Why this Project?
In this project, I will go through the data analysis process and see how everything fits together.<br />
I'll use the Python libraries NumPy, pandas, and Matplotlib, which make writing data analysis code in Python a lot easier! Not only that, these are sought-after skills by employers!

## What did I Learn?
* Have known all the steps involved in a typical data analysis process
* Comfortable posing questions that can be answered with a given dataset and then answering those questions
* Know how to investigate problems in a dataset and wrangle the data into a format I can use
* Have experience communicating the results of my analysis
* Able to use vectorized operations in NumPy and pandas to speed up my data analysis code
* Familiar with pandas' Series and DataFrame objects, which let me access my data more conveniently
* I know how to use Matplotlib to produce plots showing my findings

# Project Details: How did I Complete this Project?

## Introduction

For the final project, I conducted my own data analysis and created a [jupyter file](https://github.com/beingjainparas/Udacity-Investigate_a_dataset/blob/master/Investigate_a_dataset-TMDb_movie_database.ipynb) and [html file](https://github.com/beingjainparas/Udacity-Investigate_a_dataset/blob/master/Investigate_a_dataset-TMDb_movie_database.html) which can be viewed over [here](https://beingjainparas.github.io/Udacity-Investigate_a_dataset/Investigate_a_dataset-TMDb_movie_database.html) to share my findings. I started by taking a look at the dataset and brainstorming what questions I could answer using it. Then I used pandas and NumPy to answer the questions I was most interested in, and created a report sharing the answers. I did not required to use inferential statistics or machine learning to complete this project, but I made it clear in my communications that my findings are tentative. This project is open-ended.

## Dataset
[TMDb movie data](https://github.com/beingjainparas/Udacity-Investigate_a_dataset/blob/master/Resources/tmdb-movies.csv) (cleaned from original data on [Kaggle](https://www.kaggle.com/tmdb/tmdb-movie-metadata))

## Overview and Notes
This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.
* Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters.
* There are some odd characters in the ‘cast’ column. Don’t worry about cleaning them. You can leave them as is.
* The final two columns ending with “adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.

## Example Questions
* Which genres are most popular from year to year?
* What kinds of properties are associated with movies that have high revenues?

## Review
Use the [Project Rubric](https://review.udacity.com/#!/rubrics/107/view) to review your project. If you are happy with your submission, then you're ready to submit your project. If you see room for improvement, keep working to improve your project!

# Supporting Materials
*[Investigate a Dataset - Template Notebook](https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd0f5a_investigate-a-dataset-template/investigate-a-dataset-template.ipynb)
* https://morphocode.com/pandas-cheat-sheet/
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.duplicated.html
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.drop.html
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.replace.html
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.dropna.html
* https://realpython.com/python-histograms/
* https://www.geeksforgeeks.org/python-pandas-split-strings-into-two-list-columns-using-str-split/
* https://github.com/antra0497/Udacity--Project-Investigate-TMDB-Movies-Dataset/blob/master/investigate-a-dataset-template.ipynb
* https://matplotlib.org/gallery/shapes_and_collections/scatter.html#sphx-glr-gallery-shapes-and-collections-scatter-py