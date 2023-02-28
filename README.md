# Credit_Risk_Analysis

## Overview

The purpose of this analysis was to predit credit risk using the credit card dataset from LendingClub. The data was very unbalanced, as low-risk applications outnumbers high-risk applications 197 to 1. I used RandomOverSampler, SMOTE, ClusterCentroids and SMOTEEN algorighm to balance the data and logistic regression model to predict credit risk. I also used BalancedRandomForestClassifier and EasyEnsembleClassifier models and commpared all six results to find out which model should be used to make predictions. 

## Results

* Oversampling - RandomOverSample: balanced accuracy score 0.62939; the precision: high_risk 0.01 low-risk 1.0;  recall high_risk 0.57 low-risk 0.68
* Oversampling - SMOTE: balanced accuracy score 0.62777; the precision high_risk 0.01 low-risk 1.0;  recall high_risk 0.62 low-risk 0.63
* Undersampling - ClusterCentroids: balanced accuracy score 0.51042; the precision high_risk 0.01 low-risk 1.0;  recall high_risk 0.59 low-risk 0.43
* Over- and undersampling - SMOTEENN: balanced accuracy score; the precision high_risk 0.01 low-risk 1.0;  recall high_risk 0.70 low-risk 0.61
* BalancedRandomForestClassifier: balanced accuracy score 0.78777; the precision high_risk 0.04 low-risk 1.0;  recall high_risk 0.67 low-risk 0.91
* EasyEnsembleClassifier: balanced accuracy score 0.92543; the precision high_risk 0.07 low-risk 1.0;  recall high_risk 0.91 low-risk 0.94

## Summary

Based on the results above, I would recommend using the EasyEnsembleClassifier model to make credit risk predictions. As identified in the results section above, this model has the highest accuracy score. The recall score for both high and low risk applications is also the highest, which means that the model is good at identifying both sets of applications. 

The interesting finding that all models have precision score of 1.0 for low risk applications, which means there were no False Positives for any of the models. 
