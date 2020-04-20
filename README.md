# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) 

# General Assembly Capstone Project: Credit Risk Modeling

## Context and Problem Statement

### This project aims to use credit modeling to predict a borrower's default risk, which is targeted towards lenders to provide visibility when deciding whether to extend a loan to the borrower or not.

To build a model to predict percentage of loan default. Model performance will be guided by true positive rate sensitivity, and the model should improve upon baseline. Baseline is defined as the performing loan over total loan in the year 2007. This 2007 financial lending csv data set consisted a total of 42,535 loans and is derived from https://www.lendingclub.com/ 

Many Americans will need to borrow money at some point in their lives, whether to pay for school, a car or a home. Unfortunately, not everyone pays back their loans. Defaulting on a loan is detrimental to both borrowers and lenders. In efforts to curtail this activity, I developed a model that aimed to outperform the existing process LendingClub uses to approve loans.

Some of the consequences from defaulting on loans include:

1.Severe damage to credit report

2.Seizure of assets like home, car, or bank accounts

3.Cancellation, revocation or non-renewal of professional licenses

4.Withholding of state and federal tax refunds

5.Lenders will lose some or all of their investments

Therefore, it is important for lenders to decrease this risk as much as possible.
Can we predict whether a borrower will default using loan and borrower statistics?
In this capstone project at General Assembly, I used several classification models to answer this question.

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

-Random Forest Classifier Sensitivity of 0.86708 is the best among the models and managed to marginally outperform the baseline score of 0.86508, therefore this is our recommended model.

-Improvements can be made to the model with a more recent and a larger data set as well as grid-searching hyper-parameters and introducing Recurrent Neural Networks.


### Sources:

- [Data Source](https://www.lendingclub.com/)
- [Machine Learning Project](https://app.dataquest.io/course/machine-learning-project)
- [Predicting loan defaults on LendingClub](https://medium.com/@alex.lau14/predicting-loan-defaults-on-lendingclub-1fed06ac4c61)
