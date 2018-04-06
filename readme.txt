##  Overview
Predict user ratings of recipes on AllRecipes. Explore variation between recipes. 

##Motivation
Why are there so many recipes for the same thing? How different can all these recipes be? What factors have the most influence on user ratings?

I set out to answer these questions by developing a model to predict user ratings of recipes on AllRecipes.com

Assess whether there are certain characteristics of recipes that cause some to be rated more highly than others.

Final project for General Assembly Data Science Intensive, January 2018

I used the sklearn, pandas, seaborn, keras and numpy libraries. I used statsmodels to fit a logistic regression with 'rating' as the response variable. I used sklearn to run a cluster analysis. Finally, I used keras to implement a neural network, and seaborn to visualize a confusion matrix. 


###API Reference
www.food2fork.com/api


##Installation

###Download the data

1. Clone this repo to your computer

2. Navigate to the data folder: cd recipe_data


###Install the requirements using pip install -r requirements.txt

1. Please use Python 2.7

 
###Process

Scrape AllRecipes if desired

The first two Jupyter notebooks walk you through the process I used to scrape AllRecipes and query the Food2Fork API, as well as to transform the json data from the API into a dataframe and create the reference tables.

The data file I have provided is at the point once you have completed these preliminary steps.

Recipe_3 provides the data cleansing and EDA process