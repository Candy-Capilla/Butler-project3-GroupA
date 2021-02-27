# Butler-project3-GroupA

# Wall Street Bets
Proposal 

**Did Wall Street Bets Really Influence the Value of GME**

### Topic:
Is there any correlation between the number of times GME or GameStop is mentioned and change in value of the GME stock and could we use machine learning to predict that change.

###  Datasets:

Reddit Wall Street Bets posts:
[Kaggle] (https://www.kaggle.com/gpreda/reddit-wallstreetsbets-posts)

This dataset contains every post on WSB from 28Sep20 to current and a timestamp of the post

Historical Stock values of GME from the time period available in the WSB dataset are available [Here] (https://finance.yahoo.com/quote/GME/history)

Both dataset are available for download in .csv format and are updated daily. 

## ETL:
Using google collab we will create a notebook and use either pandas or pyspark to clean up the data and merge them into one dataset.

## Analysis:
Using SciKit Learn and MatPlotLib we will create an overlay of two line graphs. One being the number of comments mentioning GME or gamestop in a given day, another being the closing stock price of $GME for that day. We will first do a statistical analysis to determine of there is a relationship between the two. From there we will perform a non-linear regression analysis to determine the type of relationship between the two. If time allows, we will plug in any other stocks that are mentioned on a regular basis by WSB, and perform the same analysis.

## Presentation:
We will create a website to present the results of our analysis using html/css/bootstrap and give a detailed explanation of our findings. 