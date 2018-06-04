##  Overview
Have you ever wondered why there are so many recipes for the same thing? Take chocolate cookies, for example - how many different recipes for chocolate chip cookies do you think there are? Thousands. As someone who does a lot of baking, sometimes I get tired of seeing yet another new recipe for the 'ultimate' chocolate chip cookies. How different can all these recipes be? 

I set out to answer a couple questions. First, however different are all these recipes for the same thing (e.g., chocolate cookies)? Secondly, are there attributes that cause certain chocolate chip cookie recipes to be rated more favorably than others? For example, do sweeter cookies receive higher ratings? Or cookies with more chocolate chips? What types of things would lead one blueberry muffin recipe to average 5 stars, and another to average only 2?

I set out to answer these questions by examining recipes and user reviews on AllRecipes.com. My anaysis was done in python. 
I used the sklearn, pandas, seaborn, keras and numpy libraries. I also used statsmodels to fit a logistic regression. 

Final project for General Assembly Data Science Intensive, January 2018


#### API Reference
www.food2fork.com/api


## Installation

### Download the data

1. Clone this repo to your computer

2. Navigate to the data folder: cd recipe_data


### Install the requirements using pip install -r requirements.txt

1. Please use Python 2.7

 
### Process

The first two Jupyter notebooks walk you through the process I used to scrape AllRecipes and query the Food2Fork API, as well as to transform the json data from the API into a dataframe and create the reference tables. The data file I have provided is at the point having completed these steps.

The third notebook provides the data cleansing and EDA process
