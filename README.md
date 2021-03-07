# Butler-project3-GroupA

# Wall Street Bets
Proposal 

**Did Wall Street Bets Really Influence the Value of GME**

### Topic:
Is there any correlation between the number of times GME or GameStop is mentioned and change in value of the GME stock and could we use machine learning to predict that change.

###  Datasets:

Reddit Wall Street Bets posts:
**[Kaggle](https://www.kaggle.com/gpreda/reddit-wallstreetsbets-posts)**

This dataset contains every post on WSB from 28Sep20 to current and a timestamp of the post

Historical Stock values of GME from the time period available in the WSB dataset are available **[Here](https://finance.yahoo.com/quote/GME/history)**

Both dataset are available for download in .csv format and are updated daily. 

## ETL:
Using google collab we will create a notebook and use either pandas or pyspark to clean up the data and merge them into one dataset.

## Analysis:
Using SciKit Learn and MatPlotLib we will create an overlay of two line graphs. One being the number of comments mentioning GME or gamestop in a given day, another being the closing stock price of $GME for that day. We will also do a sentiment analysis using the vader library to determine negative or positive sentiment. We will first do a statistical analysis to determine of there is a relationship between the two. From there we will perform a non-linear regression analysis to determine the type of relationship between the two. If time allows, we will plug in any other stocks that are mentioned on a regular basis by WSB, and perform the same analysis.

## Presentation:
We will create a tableau to present the results of our analysis and give a detailed explanation of our findings. 

## Links:
[Google Colab Notebook](https://colab.research.google.com/drive/1NTlPFZTNnNOCxpQVMCVr-4F3Gj0w7QB1#scrollTo=kQVVVG17zSQ9)

[Tableau Visualization](https://public.tableau.com/profile/candy.capilla#!/vizhome/Butler-Project3-GROUPA/WSBandGME)

<html>
<div class='tableauPlaceholder' id='viz1615130851900' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;RS&#47;RSDH8C5SW&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;RSDH8C5SW' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;RS&#47;RSDH8C5SW&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1615130851900');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='1016px';vizElement.style.height='991px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
  </html>
