# Supervised Machine Learning Homework - Predicting Credit Risk

This task will be building a machine learning model that attempts to predict whether a loan from LendingClub will become high risk or not. 


![Credit_Risk](Resources/credit_risk.webp)


## Background

LendingClub is a peer-to-peer lending services company that allows individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. LendingClub offers their previous data through an API.

This data will be used to create machine learning models to classify the risk level of given loans. This task will compare the Logistic Regression model and Random Forest Classifier.

## Preprocessing: Convert categorical data to numeric

First a training set has been created from the 2019 loans using `pd.get_dummies()` to convert the categorical data to numeric columns. The same will be done for 2020 loans, also using `pd.get_dummies(). Missing categories will also need to be added into the testing set.

## Consider the models

Two models will be created and compared on this data: a logistic regression, and a random forests classifier. 


## Revisit the Preprocessing: Scale the data

`StandardScaler` has been used to scale the training and testing sets. 
The LogisticRegression and RandomForestClassifier models have been fitted and scored on the scaled data. 

### References

LendingClub (2019-2020) _Loan Stats_. Retrieved from: [https://resources.lendingclub.com/](https://resources.lendingclub.com/)


