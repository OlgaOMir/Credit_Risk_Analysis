# Credit_Risk_Analysis

## Overview

The purpose of this analysis was to predit credit risk using the credit card dataset from LendingClub. The data was very unbalanced, as low-risk applications outnumbers high-risk applications 197 to 1. I used RandomOverSampler, SMOTE, ClusterCentroids and SMOTEEN algorighm to balance the data and logistic regression model to predict credit risk. I also used BalancedRandomForestClassifier and EasyEnsembleClassifier models and commpared all six results to find out which model should be used to make predictions. 

## Results

* Oversampling - RandomOverSample: balanced accuracy score 0.62939; the precision: high_risk 0.01 low-risk 1.0;  recall high_risk 0.57 low-risk 0.68
* Oversampling - SMOTE: balanced accuracy score 0.62777; the precision high_risk 0.01 low-risk 1.0;  recall high_risk 0.62 low-risk 0.63
* Undersampling - ClusterCentroids: balanced accuracy score; the precision high_risk 0.01 low-risk 1.0;  recall high_risk 0.01 low-risk 1.0
* Over- and undersampling - SMOTEENN: balanced accuracy score; the precision high_risk 0.01 low-risk 1.0;  recall high_risk 0.01 low-risk 1.0
* BalancedRandomForestClassifier: balanced accuracy score; the precision high_risk 0.01 low-risk 1.0;  recall high_risk 0.01 low-risk 1.0
* EasyEnsembleClassifier: balanced accuracy score; the precision high_risk 0.01 low-risk 1.0;  recall high_risk 0.01 low-risk 1.0

## Summary
