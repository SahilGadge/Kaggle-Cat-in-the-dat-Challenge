# Kaggle-Cat-in-the-dat-Challenge
https://www.kaggle.com/c/cat-in-the-dat/overview

Abstract:
The goal of this notebook is to solve classification problems using various algorithms and compare their accuracy. For, this comparison I used various algorithms from Scikit-Learn and H2O autoML. Also, before applying such models I also performed Feature Selection and Engineering on the data. I successfully trained and explained various models to compare their prediction accuracy for classifiaction problem.


• Compared AutoML algorithms including H2O, Light AutoML, and Scikit-Learn Logistic Regression and Random Forest 
algorithms based on how accurately each algorithm performed in classifying target variable


• Trained and tested ML models using Cat-in-dat Kaggle competitions categorical dataset. Conducted data cleaning, feature 
engineering steps such as encoding, mapping. Examined results of encoding data with One Hot encoding and Target encoding


• Improved accuracy of SK-Learn Logistic Regression and Random Forest algorithm by tuning hyperparameters. Scikit-Learns 
Logistic Regression model outperformed both H2O, Light AutoML models

Conclusion:

> Model Comparison

1.  Scikit-Learn and H2O both did pretty good job on predicting the outcome.  
2.  Hyperparameter tuned Logistic Regression Model from Scikit-Learn produced best result in 9 models we compared.
3. From H2O, Best model was Stacked Ensemble model prdicted outcome with 80% accuracy. And after Ensembles in the leaderboard of H2O Generalized Linear Model predicted output with 79.99% Accuracy
4. From this model comparison it is clear that Linear Models worked well for this classification problem i.e. GLM in H2O and Logistic in the Scikit Learn.

> Feature Engineering

1.   For binnary data we mapped data to 0 and 1 acoordingly.
2.   For ordinal data according to the order number was assigned to each category in the variable.
3.   For nominal data in Logistic Model One Hot Encoding worked well than Target Encoding. However, for Random forest Target encoding performed well.



> Feature Importance



1.   For logistic regression SK-Learn model independent features like "nom_9", "ord_5", "ord_2", "ord_4", "ord_1", "ord_3", "nom_8", "nom_7", "nom_5", "nom_6" are the important features for Classificcation.
2.   For Random Forest "ord_5", "nom_9", "nom_8", "nom_7", "ord_4", "nom_6", "nom_5", "ord_3", "ord_2", "ord_1", "ord_0" are the important features for Classification.
