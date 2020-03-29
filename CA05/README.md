# BSAN6070
# CA05A: Logistic Regression

## Description
CA05A:
Cardiovascular Disease (CVD) kills more people than cancer globally. A dataset of real heart patients
collected from a 15 year heart study cohort is made available for this assignment. The dataset has 16
patient features. Note that none of the features include any Blood Test information.
* Part 1: Build a binary classifier model to predict the CVD Risk (Yes/No, or 1/0) using a Logistic
Regression Model with the best performance possible.
* Part 2: Display the Feature Importance of all the features sorted in the order of decreasing influence on
the CVD.
* Part 3: Evaluate the performance of your model (including ROC Curve), explain the performance and
draw a meaningful conclusion.
* Data File Name: cvd_data.csv
* File Location: https://github.com/ArinB/CA05-B-Logistic-Regression/raw/master/cvd_data.csv

# CA05B: kNN Recommender

## Description
CA05B:
At scale, this would look like recommending products on Amazon, articles on Medium, movies on
Netflix, or videos on YouTube. Although, we can be certain they all use more efficient means of making
recommendations due to the enormous volume of data they process. However, we could replicate one of
these recommender systems on a smaller scale using what we have learned here in this article. Let us
build the core of a movies recommender system. Given a movies data set, what are the 5 most similar movies to a movie query?
* Data File Name: movies_recommendation_data.csv
* File Location: https://github.com/ArinB/CA05-kNN/raw/master/movies_recommendation_data.csv

## Getting Started
### Dependencies
* Google CoLab environment
* Data downloaded from above links
* Path in Google Drive set to hardcoded link as given in Descriptions
 
### Executing program
Install the following packages:

CA05A:
* import pandas as pd
* import numpy as np
* import matplotlib.pyplot as plt
* from sklearn.metrics import accuracy_score, roc_curve, roc_auc_score
* from sklearn.model_selection import train_test_split, GridSearchCV
* from sklearn.linear_model import LogisticRegression
* from sklearn import preprocessing, metrics

CA05B:
* import pandas as pd
* import numpy as np
* import matplotlib.pyplot as plt
* from sklearn.neighbors import NearestNeighbors

### Authors
Calix Carrington
