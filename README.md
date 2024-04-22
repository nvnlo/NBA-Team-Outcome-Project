# NBA Team Outcome Predictor Machine Learning Project

The final write-up and knitted .rmd file can be viewed [here](https://nvnlo.github.io/TeamProject/Team-Outcome-Predictor.html)

The objective of this project was to build five machine learning models to predict the outcome of an NBA team in a given season. Each team was manually classified into one of seven different outcomes based on a number of various descriptive metrics from that season. The 1,250 observations are individual team seasons from 1980-2024, and were taken from [Kaggle](https://www.kaggle.com/datasets/sumitrodatta/nba-aba-baa-stats).

There is a section for exploratory data analysis to clean the data and remove unnecessary variables, then choose the 19 best predictors of team success and visualize their interaction with the outcome variable before running models.

This project then performed k-fold cross validation for stratified sampling, tuned hyperparameters and built five models: K-Nearest Neighbors, Elastic Net Regression, Gradient Boosted Tree, Random Forest and Neural Network, followed by a utilization the ROC AUC metric to determine model success and find the best result.
