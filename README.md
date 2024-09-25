# CSE 351: Data Science Final Project
Final project done alongside my partner, ShaoYang Li

## Source
https://www.kaggle.com/competitions/titanic/data on the titanic disaster's passengers.

## Overview
First, we turned the raw training data into something more compatible with machine learning algorithms.
We created a pairwise correlation matrix to see which statistics were useful for predicting survival and which weren't, as well as to test different transformations to make the data's outliers more in line with the rest of the data and more friendly to learning. Outliers that couldn't be resolved and statistics that bore no significant correlation to survival were removed, and missing data was marked as missing.
Then, we used Logistic Regression, KNN, and Decision Tree models to attempt to accurately predict a passenger's survival based on the remaining significant statistics, peformed cross-validation on the results, and compared the results.
