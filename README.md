# Use of Machine Learning Models to predict the type and quality of Wine


This repository contains two datasets of wine, one for red wine and another for white wine. The goal of this project is to predict the type and quality of wines using machine learning models.

To achieve this goal, we have experimented with seven different machine learning models: Logistic Regression, Decision Tree, Random Forest, Naive Bayes, Support Vector Machine (SVM), Adaboostclassifier, and Neural Network. We have trained each of these models on the wine datasets and evaluated their performance using cross-validation.

After evaluating the models, we have selected the best model for each type of wine and each prediction task. Specifically, we have found that Random Forest is the best model for predicting the type of wine (red or white), and the quality of red and white wines.

Moreover, we have improved the performance of the selected models by tuning their hyperparameters. We have used grid search to explore the hyperparameter space and find the best combination of hyperparameters for each model.

To assess the performance of the tuned models, we have used learning curves to visualize how their accuracy and error vary as a function of the number of training samples. We have observed that the tuned models achieve high accuracy and low error with a reasonable amount of training data.

In conclusion, this project demonstrates how machine learning models can be used to predict the type and quality of wines. The selected models and their hyperparameters can be used as a baseline for further experiments or as a starting point for deploying the models in real-world applications.
