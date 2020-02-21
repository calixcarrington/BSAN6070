# BSAN6070
# CA03: Decision Tree Algorithm

## Description
Given a data of attributes together with its classes, a decision tree
produces a sequence of rules that can be used to classify the data.
The data is provided in a .csv file. Download the data and other files for this
assignment from the following GitHub link. There is a column indicating the rows to be
used as “Training Data” and “Testing Data”. You can split the files based on this column
value.

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
* from sklearn.tree import DecisionTreeClassifier
* from sklearn.externals.six import StringIO  
* from IPython.display import Image  
* from sklearn.tree import export_graphviz
* import pydotplus
* from sklearn.metrics import confusion_matrix
* from sklearn.metrics import accuracy_score 
* from sklearn.metrics import classification_report
* from sklearn import metrics
* import time

### Authors
Calix Carrington
