# project_1 - Food for Thought
Food accessibility, health, and food choices were the overarching themes of the Food for Thought project. We analyzed how food accessibility and health may play into the choices an indiviual may make regarding food to fit their personal goals. 

The presentation deck is a compilation of a series of datasets that look into each aspect of these themes and explore any caveats that can be used to further explain and understand the variety of ways in which this can can be used. 

In the folder labeled "Resources & Notebooks" you will find the respective folders of resources used by each individual along with the respective notebook noted under their names. Combined_work is a compilation of Susmitha, Esther and Kasy's final analysis, code and respective charts, data and notebook in the respective folder. 

Priya's Notebook and Priya's Resources highlight her final analysis, code and charts. 

Yash's Notebooks folder contains his notebook, resources, analysis, code and charts. 

## Technologies
All data cleaning, exploration and analysis occurred in jupyter notebooks. Utilizing pandas and matplotlib, the csv files were able to help generate a variety of data points and visualizations that aided in the construction of the presentation.

The presentation was put together in PowerPoint and later converted to a PDF for purposes of uploading. 


## Data
All respective data sets were pulled from kaggle.com or data.gov. The data.gov dataset was in regards to food consumption while all kaggle datasets were compilations of various USDA, food.com, McDonalds and other datasets for ease of access. The presentation highlights the original sources of the data used for each portion of the project.

The recipes and user intreaction datasets were too large so we had to put in a drive and save it locally to run the scripts. Please find the links for the respectve datasets below prior to running the notebooks.

[Reviews & Interactions Link](https://drive.google.com/file/d/1mUidiQSvwrK3rDyoc94vM7owyUphSJ7K/view?usp=sharing "Reviews & Interactions Link") & [Recipes Link](https://drive.google.com/file/d/1X-ql9B4xjRIPa3Sa7kJTzEXekW6pBand/view?usp=sharing "Recipes Link")


## Notebooks 
There are a total of three notebooks, a Combined_Work, Priya's Notebook, & Yash's Notebook. 

Combined_work.ipynb is under the Combined_work folder and is a compilation of Susmitha's, Esther's and Kasy's notebooks. Combined, these notebooks sort through a variety of nutritional and recipe-related datasets and when certain values are entered into the input prompt, generate a series of lists and graphs that show nutritional value of various McDonal's food items or recipes. An example is given using Breakfast Foods under 600 calories in the data set and detailed results in the presentation file.

The categories are highlighted in the notebook and detail the process in which the notebook is utilized and using which datasets. 

Priya's Notebook sorts through food desert data and farmer's market data collected by the Census and USDA. Through a process of cleaning and extrapolating various variables, this notebook highlights the relationship between said variables and generates the respective scatter plots. Additional analysis regarding the dataset is detailed in the notebook as well. 

The farmer's market data also takes a look at the accessibility of food assistance programs by state and the relationship to the food assistance program noted in the food desert data set. 

Yash's Notebook dives deeper into the food deserts data to understand how this data plays into a particular state, in relation to the median income. His notebook also looks into the number of Starbucks and Fast Food restaurants vs farmers markets ratio by population of the state to get an idea the accessbility of ingredients that allow you to cook at home.  


## Data Clean Up & Exploration 

The data clean up and explorations were as follows:

All datasets were fairly large and required the removal of null and duplicate values for accurate results. In combining related datasets, additional cleaning was required to remove irrevlant items, correct misspelled items or understand where the join may have resulted in inaccuracies. 

Additionally, there were some difficulties in the conversions of various variables. For example, certain nutritional information or numerical data was categorized as an object rather than an integer/float. This required conversions to a string along with removal of extra characters to utilize the data appropriately in pandas. 

Graph formatting required color adjustment and xtick adjustments to achieve readability and usability for the PowerPoint presentation. 

Please see each respective notebook for further detail regarding data cleaning and exploration based on the datasets used. 


## Final Analysis
Upon a final look at the data collected, we have been able to address the follow questions: 
1. What does it mean for food to be accessible? 

Food accessibility can be a result of a variety of factors: location, cost, transportation, convenience, etc. and often at the shortcomings of other factors as well. Understanding that around 37% of the population currently lives in a food desert, highlights the broadness of the issue of food inaccessibility and may be overlooking a variety of geographical and demographic factors that could further contribute to these numbers which vary by state. Just looking at farmer's markets, we can see that food accessibility can also be out of reach for a given population in each state where over half of farmer's markets do not have any food assistance programs.

2. How does ”healthy” shape the way we categorize food? 

"Health" can often be a broad term, where each category of food can be broken down to each of its individual nutritonal components and reflective of people's personal health goals. Defining healthier options can be quite difficult, especially when looking at it from solely a caloric perspective. However, understanding this highlights the difference in options available to someone who is able to cook at home where for the same 600 calories are looking at pork chops, guinness burgers and shrimp scampi compared to varitations of a chicken sandwich at a McDonald's. Where for an individual the difference may be in the ease of cooking and affordability of said food items. 

3. How are our choices shaped by accessibility & health?

Understaning the accessibility of food and the health concerns of an individual, we can begin to understand how an individual may begin to choose what they eat. Where fresher ingredients may be further away or require a recipe to cook, a McDonald's chicken sandwich may serve the same nutritional purpose. In also understanding how food accessibility can be limited by an income level, as noted in food assistance programs in relation to farmers markets, something like the caloric values of certain foods may not come into play as heavily as does the price and affordability of each of the ingredients. Where on average a recipe may require 10 ingredients, a McDonald's sandwich requires very little outside of money. 

In internalizing this understanding, we can understand the patterns in which health may be affected in a country looking to address overall health issues that may be a result of poor eating habits, but also a result of inaccessibility to healthier options. 

