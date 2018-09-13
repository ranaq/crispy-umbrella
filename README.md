##  Overview
Have you ever wondered why there are so many recipes for the same thing? Take chocolate chip cookies, for example - why are there thousand of recipes for chocolate chip cookies? How different can all these recipes be? 

I set out to answer a couple questions. First, however different are all these recipes for the same thing (e.g., chocolate cookies)? Secondly, are there attributes that cause certain recipes to be rated more favorably than others? For example, do sweeter chocolate chip cookies receive higher ratings? Or cookies with more chocolate chips? What types of attributes cause one blueberry muffin recipe to average 5 stars and another to average only 2?

Using data from AllRecipes.com on recipes and user reviews, I developed regression and neural network models to try and answer these questions. My anaysis was done in Python using the sklearn, pandas, seaborn, keras and numpy libraries, as well as statsmodels. 

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

The 'Summary' notebook gives a high-level overview of the various stages of the project. Notebooks 1 & 2 walk you through the process I used to scrape AllRecipes, query the Food2Fork API, and transform the json data from the API into a dataframe. The data provided was generated at this point.

Notebook 3 includes the data cleansing process, and the notebook 4 details the EDA and modeling.
