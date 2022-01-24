# Credit Risk Analysis

## The purpose of this analysis was to use sampling algorithms and machine learning models to reduce bias and predict credit risk to help a Credit Card Lending company provide a more reliable loan experience and more accurate identification for loan candidates. 

## Project Overview:
1. Use Resampling Models to Predict Credit Risk
    - Naive Random Oversampling
    - SMOTE Oversampling
    - Undersampling
    - SMOTEEN (Over and Under Sampling)
2. Use Ensemble Models to Predict Credit Risk
    - Balanced Random Forest Classifier
    - Easy Ensemble AdaBoost Classifier
3. Interpret results and determine which supervised learning algorithm is best used for this dataset

## Resources
- Source of data: [LoanStats_2019Q1.csv](https://github.com/mthalken/Credit_Risk_Analysis/blob/main/resources/LoanStats_2019Q1.csv)
- Software: imbalanced-learn, skikit-learn, Python 3.7.10, Conda 4.10.3, Jupyter Notebook 6.3.0, Visual Studio Code 1.60.2
- Please see the refactored code here: 
    - [credit_risk_resampling.ipynb](https://github.com/mthalken/Credit_Risk_Analysis/blob/main/notebooks/credit_risk_resampling.ipynb)
    - [credit_risk_ensemble.ipynb](https://github.com/mthalken/Credit_Risk_Analysis/blob/main/notebooks/credit_risk_ensemble.ipynb)

## Results 

From our 6 different machine learning tests that when looking at balanced accuracy score, precision, and recall the Easy Ensemble Adaboost Classifier would be the best to choose at the following:
    - 93% Balanced Accuracy Score
    - 7% Precision
    - 91% Recall

![png](https://github.com/mthalken/Credit_Risk_Analysis/blob/main/images/resampling_results_table.png)

![png](https://github.com/mthalken/Credit_Risk_Analysis/blob/main/images/ensemble_results_table.png)

Even though the Easy Ensemble Adaboost Classifier does not have a very reliable precision score out of the 6 machine learning models used the Easy Ensemble Adaboost Classifier would be the best model for credit card analysis within this dataset. 
