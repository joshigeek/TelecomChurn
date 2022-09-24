# Telecom Chrun Group - Case Study

The main goal of the case study is to build ML models to predict churn, generated model/summary will be used for following:

To predict whether a high-value customer will churn or not, in near future.
It will be used to identify important variables that are strong predictors of churn.
These variables may also indicate why customers choose to switch to other networks
Recommend strategies to manage customer churn based on your observations

Steps followed:
* Data Cleaning
* Feature Analysis
* Correlation analysis
* Build models for prediction
* Summary


## Summary

### Model summary

#### PCA + Linear Regression
* Accuracy on Train: 0.8698
* Accuracy on Test: 0.8734
* Accuracy on test.csv (As per Kaggle): 0.90056

#### Random Forest
* Accuracy on Train: 0.9718
* Accuracy on Test:  0.9353
* Accuracy on test.csv (As per Kaggle): 0.94256

#### PCA + Random Forest
* Accuracy on Train: 0.9650
* Accuracy on Test:  0.90

#### XgBoost
* Accuracy on Train: 0.9997
* Accuracy on Test:  0.9603
* Accuracy on Test.csv (As per Kaggle): 0.92486
