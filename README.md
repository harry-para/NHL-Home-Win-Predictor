# NHL Home Win Predictor

This project used NHL (National Hockey League) regular season data that was sourced Hockey Reference (https://www.hockey-reference.com/leagues/).
Regular season data was scraped from 2014-2015 regular season to the 2019-2020 regular season.
The purpose of this project was to use the data to predict if a home team can win their game based on specified factor.
This analysis used feature enginneering to produce more insights based on the data such as home and vistor team win streak, if the home team or visitor team won their last game and if the home team won against a specific team the last team they played.
Team names were also encoded to ensure they could be used as variables for prediction.
This analysis did a 70% training data and 30$ testing data split using the 2018-2019 season and used various classification algorithms to determine which algorithm performed the best regarding home win prediction.
The algorithms used included Decision Trees, Random Forests, Naive Bayes, K-Nearest Neighbors, Support Vector Machine and Adaptive Boosting algorithms.
The F1 score, which conveys the balance between the precision and the recall, was used as the metric to compare the performances of the classification algorithms.
The best performing algorithm was then used to predict to conduct out-of-sample forecasting on other NHL regular seasons.

This analysis used Google Sheets to store the NHL regular season data and pandas dataframes online that were later used to produce data visualizations on Tableau.
The Tableau workbook gives a more visual representation by comparing the chosen classification algorithm's performance to the actual results of the games.
The link to the Tableau workbook is: 

The python script and output using Jupyter Notebooks via the Visual Studio Code editor is attached above as "TO_Crime_Analysis.ipynb".
