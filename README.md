# Predicting-the-Sale-Price-of-Bulldozers-using-Machine-Learning
The goal is this project is predict the sale prize of bulldozers. It is also a big step toward learning data science

# 1. Problem Definition
How well can we predict the future sale price of a bulldozer, given its characteristics and previous examples of how much similar bulldozers have been sold for?

# 2. Data
The data is from Kaggle Bluebook for Bulldozers compettition: https://www.kaggle.com/c/bluebook-for-bulldozers/data.

There are 3 main data sets:

Train.csv is the training set, which contains data through the end of 2011.

Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.

Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.

# 3. Evaluation
RMSLE (root mean squared log error) is the evaluation metric used for this competion, which is between the actual and predicted auction prices

[Keep in mind] : The goal for most regression evaluation is to reduce or minimize the error.

our goal for this project will be to build a machine learning model which minimises RMSLE.

# 4. Features
Kaggle provides a data dictionary detailing all of the features of the dataset. You can view this data dictionary on Google Sheets: https://docs.google.com/spreadsheets/d/18ly-bLR8sbDJLITkWG7ozKm8l3RyieQ2Fpgix-beSYI/edit?usp=sharing
