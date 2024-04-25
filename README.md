--------------------------------------------------------------------------------
Title: Social Sentiment influence on the Stock Market 
Author: Ben Godfrey
Date: 26-03-2024
--------------------------------------------------------------------------------

## Introduction

This project has the intention to carry out analysis of the effects caused by Social
Sentiments on the financial instruments, in this case specifically Stocks. The aim 
currently is to use large datasets of Twitter and Reddit posts from financial subreddits 
to create sentiment values to compare against the stocks performance, this will be 
expanded upon with further social platforms where able.

...

## Repository overview
The repository is structured like so:

Empirical_Project
├── README.md
├── RedditWSB
├   └── reddit_wsb.csv
├── Social
├   ├── stock_tweets.csv
├   └── stock_yfinance_data.csv
├── Plots
├── requirements.txt
├── blog.txt
└── blog.ipynb

The datasets used are within their respective sub-directories, for the reddit posts 
RedditWSB and for the tweets and stocks, Social. All plots produced will download 
to the Plots sub-directory.

## Running Instructions

Within the directory there is a makefile that will install the required packages via pip
however if this does not install correctly there is a list generated by !pip list that shows
the packages installed on the machine that produced the output.

## References 

- Vader usage information
  └── https://github.com/cjhutto/vaderSentiment/blob/master/README.rst (Accessed 26th March)
  └── https://www.kaggle.com/code/equinxx/stock-prediction-gan-twitter-sentiment-analysis/notebook (Accessed 26th March, used for basic setup info)

- Gradient Boosting information
  └── https://developers.google.com/machine-learning/decision-forests/intro-to-gbdt (Accessed 29th March, for more basic information)
   └── https://towardsdatascience.com/all-you-need-to-know-about-gradient-boosting-algorithm-part-1-regression-2520a34a502 (Accessed 28th March)
   └── https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html (Accessed 28th March)
   
## More resources

Information that was used on the VADER utility can be found here: https://github.com/cjhutto/vaderSentiment/blob/master/README.rst

Information on the Kaggle API can be found here: https://www.kaggle.com/docs/api
