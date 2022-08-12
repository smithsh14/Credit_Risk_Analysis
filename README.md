# Credit_Risk_Analysis
Supervised Machine Learning Models

## Purpose
We have been asked to analyis credit card risk using the imbalanced-learn amd scikit-learn libraries to build and evaluate models using resampling. We will be using data provided from the credit card company LendingClub. We will be employing various techniques to train and evaluate the models with unbalancd classes:
- Naive Random Oversampling
- SMOTE Oversampling
- Undersampling
- Combination Oversampling and Undersampling
- Balanced Random Forest Classifer
- Easy Ensemble AdaBoost Classifer

### Project Deliverables
This project will consist of four deliverables.
- Deliverable 1: Use Resampling Models to Predict Credit Risk
- Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
- Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
- Deliverable 4: A Written Report on the Credit Risk Analysis

## Results
Below you will find the results of the 6 machine learning models. The results will also show their respective balanced accuracy, precision, and recall scores. For Balanced Random Forest Classifer and Easy Ensemble AdaBoost Classifier, predicted risk will also be included. 

### Naive Random Oversampling
![Naive](https://github.com/smithsh14/Credit_Risk_Analysis/blob/main/Images/NaiveRandomOversampling.png)

1) Logistic Regression: Random State = 1
2) Balanced Accuracy Score: 0.6463970560994359
3) Precision: The precision is low for High Risk loans and high for Low Risk Loans
4) Recall: High/Low Risk = .71/.58

### SMOTE Oversampling
![SMOTE](https://github.com/smithsh14/Credit_Risk_Analysis/blob/main/Images/SMOTEOversampling.png)

1) Logistic Regression: Random State = 1
2) Balanced Accuracy Score: 0.6586230769943224
3) Precision: The precision is low for High Risk loans and high for Low Risk Loans
4) Recall: High/Low Risk = .63/.68

### Undersampling
![Undersampling](https://github.com/smithsh14/Credit_Risk_Analysis/blob/main/Images/Undersampling.png)

1) Logistic Regression: Random State = 78
2) Balanced Accuracy Score: 0.5447339051023905
3) Precision: The precision is low for High Risk loans and high for Low Risk Loans
4) Recall: High/Low Risk = .69/.40

### Combination Oversampling and Undersampling 
![Combination](https://github.com/smithsh14/Credit_Risk_Analysis/blob/main/Images/Combination.png)

1) Logistic Regression: Random State = 1
2) Balanced Accuracy Score: 0.6480442302883235
3) Precision: The precision is low for High Risk loans and high for Low Risk Loans
4) Recall: High/Low Risk = .72/.57

### Balanced Random Forest Classifier
![Forest](https://github.com/smithsh14/Credit_Risk_Analysis/blob/main/Images/BalancedRandomForest.png)

1) Balance Random Forest Classifier: Random State = 1
2) Balanced Accuracy Score: 0.7877672625306695
3) Precision: The precision is low for High Risk loans and high for Low Risk Loans
4) Recall: High/Low Risk = .67/.91

![RISK](https://github.com/smithsh14/Credit_Risk_Analysis/blob/main/Images/BalancedRandomForest_RISK.png)

### Easy Ensemble AdaBoost Classifier
![AdaBoost](https://github.com/smithsh14/Credit_Risk_Analysis/blob/main/Images/AdaBoostClassifer.png)

1) Easy Ensemble Classifier: Random State = 1
2) Balanced Accuracy Score: 0.925427358175101
3) Precision: The precision is low for High Risk loans and high for Low Risk Loans
4) Recall: High/Low Risk = .91/.94

![RISK](https://github.com/smithsh14/Credit_Risk_Analysis/blob/main/Images/AdaBoostClassifer_RISK.png)

## Summary

In working with balanced accuracy, the highest compared accuracy is between 0 and 1 and the accuracy closest to 1 is the better machine learning model.

The results show us that for the credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to choose with its 0.925 balanced accuracy score with Balance Ensemble AdaBoost Classifier being the second best model with a .0787 balanced accuracy score. 

The Easy Ensemble AdaBoost Classifier presented the highest recall score making this the best maching learning model to choose from in further analysis of credit card risk.
