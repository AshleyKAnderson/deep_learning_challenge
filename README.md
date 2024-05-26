# Charity Fund predictor 

## Overview
The objective of this project is to develop an algorithm leveraging machine learning and neural networks to predict the success of applicants who receive funding from the fictional non-profit organization, Alphabet Soup.
## Preprocessing
I preprocessed the data through the following steps:

* Dropped non-beneficial columns.
* Analyzed the number of data points for each unique value in columns with more than 10 unique values, specifically APPLICATION_TYPE and CLASSIFICATION.
* Converted categorical data to numeric using pd.get_dummies().
* Divided the data into a target array (IS_SUCCESSFUL) and feature arrays.
* Applied train_test_split to create training and testing datasets.
* Scaled the training and testing sets using StandardScaler.

## Model Making - compiling, training and testing the model.
The goal was to achieve a predictive accuracy higher than 75%. I made three official attempts using machine learning and neural networks, but all attempts resulted in an accuracy rate of around 72%, falling short of the target accuracy.







