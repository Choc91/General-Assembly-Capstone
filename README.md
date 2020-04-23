# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) 

# General Assembly Capstone Project: Credit Risk Modeling

## Context and Problem Statement

### This project aims to use credit modeling to predict a borrower's default risk, which is targeted towards lenders to provide visibility when deciding whether to extend a loan to the borrower or not.
This capstone project aims to use credit modeling to predict a borrower's default risk, which is targeted towards lenders to provide better visibility when deciding whether to extend a loan to the borrower or not.

Model performance will be guided by F1 score. This 2007 financial lending csv data set consisted a total of 42,535 loans. It is important for lenders to decrease credit default risk as much as possible. Can we predict if a borrower will default by using loan and borrower statistics? Logistic Regression, Cross Validation and Random Forest Classifier were depolyed to answer this issue.

Some of the consequences from defaulting on loans include:

Many Americans will need to borrow money at some point in their lives, whether to pay for school, a car or a home. Unfortunately, not everyone pays back their loans. Defaulting on a loan is detrimental to both borrowers and lenders. In efforts to curtail this activity, I developed a model that aimed to outperform the existing process LendingClub uses to approve loans. Some of the consequences from defaulting on loans include:

1.Severe damage to credit report
2.Seizure of assets like home, car, or bank accounts
3.Cancellation, revocation or non-renewal of professional licenses
4.Withholding of state and federal tax refunds
5.Lenders will lose some or all of their investments

## Executive Summary


### Contents:

- [Import Libraries and Load data](#Import-Libraries-and-Load-Data)
- [Data Cleaning and Exploratory Data Analysis](#Data-Cleaning-and-Exploratory-Data-Analysis)
- [Modeling](#Modeling)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)
- [Sources](#Sources)

---

### Import Libraries and Data

After importing libraries, data was acquired.

### Data Cleaning and Exploratory Data Analysis

Data cleaning was performed with overview of summary statistics shown.

### Modeling

Logistic Regression, Cross Validation and Random Forest Classifier were depolyed.

### Conclusions and Recommendations

-LogisticRegression class weight balanced f1 score(0.99933) is the best among the models, therefore this is our recommended model

-Improvements can be made to the model with a more recent and larger data set

-Introduce grid-searching hyper-parameters and Recurrent Neural Networks to optimize performance

### Sources:

- [Data Source](https://www.lendingclub.com/)
- [Machine Learning Project](https://app.dataquest.io/course/machine-learning-project)
- [Predicting loan defaults on LendingClub](https://medium.com/@alex.lau14/predicting-loan-defaults-on-lendingclub-1fed06ac4c61)
