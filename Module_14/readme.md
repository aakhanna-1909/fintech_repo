# Module 14 - Machine Learning Trading Bot

## Overview of the Analysis

The purpose of this machine learning exercise is to create an algorithmic trading bot that learns and adapts to new data and evolving markets, and automates the trade decisions.

For this analysis, I created and evaluated a baseline trading model using the Support Vector Machines Classifier algorithm that attempts to predict whether to buy stock long (labeled 1) or to sell stock short (labeled -1). I then created and evaluated another model using the Logistic Regression algorithm to compare its performance with the baseline model's performance.

## Results

* SVM Model 1:
  * Accuracy Score = 0.55
  * Precision for Class -1 (sell stock short) = 0.43
  * Precision for Class 1 (buy stock long) = 0.56
  * Recall for Class -1 (sell stock short) = 0.04
  * Recall for Class 1 (buy stock long) = 0.96
  
* Logistic Regression Model 2:
  * Accuracy Score = 0.52
  * Precision for Class -1 (sell stock short) = 0.44
  * Precision for Class 1 (buy stock long) = 0.56
  * Recall for Class -1 (sell stock short) = 0.33
  * Recall for Class 1 (buy stock long) = 0.66

## Summary

Both models sell to be quite similar in terms of accuracy and performance. Therefore, I would recommend running a few more iterations with different algorithms/hyperparameter tuning before deciding on the final model.