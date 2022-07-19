# Regularized-Regression-for-Predicting-Foootball-Players-Rating-on-FM2020

This portfolio is dedicated for Dibimbing Data Science Bootcamp Batch 13 2022. Here, I try to implement Regularized Regression for predicting football players current ability rating based on their attributes on Football Manager 2020 Dataset.

## About Dataset
I extracted data from https://www.kaggle.com/datasets/ktyptorio/football-manager-2020, which originally consist of 64 columns and 140.000+ rows. This dataset contains a collection of players (real players) and their attributes, such as age, position, club, nationality, value, wage, all player attribute components, etc.

## About Files

* footballmanagerdataset.zip

This contains original dataset which size around 34.596 MB. Upload it in zip file because it is too large for this repository. You need to extract it first to process the dataset.

* Football Manager 2020 Dataset Preparation.ipynb

Because the dataset is so huge, so for this project I go through some preprocessing and adjusment to the real dataset. Then, I save new csv file consist of collection of players from only one football division i.e. English Premier Division 2020.

* englishpremierdivision2020.csv

This is the working csv file that I use for this project. Collections of players data from English Premier Division and their attributes. There are about 66 columns and 1000+ rows.

* Regression for Predicting Football Players Rating.ipynb

This is our working page! There are so many attributes from the players! From age, wage, value, height, weight, mental attributes like composure, decision making, and bravery, technical attributes like passing, dribling, and technique, physical attributes like acceleration, pace, aerial reach, to goalkeeping attributes. With the Ridge regression, we try to predict each players' current ability rating on the game! After regression, we can detect the signifincance of each attributes to the rating. 

Surprisingly, this Ridge regularized regression could predict the rating very well with normalized RMSE score is 5.2%. The training model could also fit the testing data
