# Patryk Pietruszka

# [Project 1: Return on Investment from DAO Maker Launches Estimator](https://github.com/patpiet/DaoMaker_ROI_Prediction) 
* Created a model that estimates Return Of Investment of the digital currencies projects that were launched on DAO Maker to help investors with their financial decisions.
* 'Mean Absolute Error' to be ~28x (Range of expected values to be 1x-352x)
* Scraped all publicly launched projects from DAO Maker using Beautiful Soup and Coingecko API.
* Engineered features from the text of each project's description to find its importance when it comes to the success of the project.
* Optimized Lasso, Random Forest, and Support Vector Regressors using GridsearchCV to reach the best model.
* Built a client facing API using Flask

Technology used: python, pandas, numpy, sklearn, matplotlib, seaborn, nltk, BeautifulSoup, flask, json, pickle, pycoingecko, wordcloud


# [Project 2: Book Recommender System](https://github.com/patpiet/Books-Reccommender) 
* Created recommending system using Content-Based and Collaborative Filtering methods.
* Model based on dataset with 68588 ratings, 2000 users and 5007 books.
* Engineered the data for the project needs.
* Built function that prints recommended books to the console.

Technology used: python, pandas, numpy, sklearn, matplotlib, seaborn

<img src ="https://github.com/patpiet/Books-Reccommender/raw/main/images/example3.PNG">


# [Project 3: Polish Matura Exam Numbers Visualized](https://github.com/patpiet/Polish_Matura_Data_Analysis) 
* Created an interactive bar chart displaying exam results using Plotly and Dash, with option to choose exam's level and year.
* Created an interactive Map of Poland with Exam Passing Rate in each region. Also, with option to change year and students' gender.
* Cleaned, Translated and Analyzed datasets from Polish Statistic's Office about 'Matura' results over years.

Technology used: python, pandas, numpy, matplotlib, plotly, Dash, json, itranslate


**Bar Chart Dashboard**

![alt text](Visualizations/BarDash.gif)

**Map Of Poland Graph Dashboard**

![alt text](Visualizations/MapDash.gif)
