# BSAN6070
# CA04: Ensemble Methods

## Description
For Ensemble Models, one of the key hyper-parameter is number of “estimators”.
Using Notebook, and the same data source from CA03, train a Random Forest Model.
Using similar approach of Section 2 above, plot a graph of Accuracy vs. n_estimator.
Use n_estimator values as [50,100,150,200,250,300,350,400,450,500].
Repeat the process for AdaBoost, Gradient Boost, XGB Models.

https://github.com/ArinB/MSBA-CA-03-Decision-Trees

The dataset is obtained from the Census Bureau and represents salaries of people
along with seven demographic variables. The following is a description of our dataset:
* Number of target classes: 2 ('>50K' and '<=50K') [ Labels: 1, 0 ]
* Number of attributes (Columns): 7
* Number of instances (Rows): 48,842

## Getting Started
### Dependencies
* Google CoLab environment
* Data downloaded from https://github.com/ArinB/MSBA-CA-03-Decision-Trees
* Path in Google Drive set to hardcoded link - https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true
 
### Executing program
Install the following packages:
* import pandas as pd
* import numpy as np
* import matplotlib.pyplot as plt
* from sklearn.metrics import accuracy_score 
* from sklearn.metrics import roc_auc_score
* from sklearn.ensemble import RandomForestClassifier, AdaBoostClassifier, GradientBoostingClassifier
* from xgboost import XGBClassifier
* import re

### Authors
Calix Carrington
