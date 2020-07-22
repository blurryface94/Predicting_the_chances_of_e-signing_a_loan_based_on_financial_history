# Predicting the chances of e-signing a loan based on financial history
 
The goal of the model to predict for "quality" applicants, who reach a key part of the loan application process. This case focuses on onboarding process. This model will help to find the leads procured from the market will complete the e-signing phase. This can be leverage to identify less quality applicants and expirement with giving them different onboarding screens.

## Table of contents
* [Technologies](#technologies)
* [Data](#data)
* [Model Details](#modeldetails)

## Technologies
  The following technologies were used for this part of the project:
  * Python 3
  * Jupyter notebook
  * Pandas: Python package for data analysis
  * Matplotlib and Seaborn: Python 2D plotting library
  * Sklearn: Python package for modeling creation

## Data
Data is received from the marketplace. The data contains personal information like age and time employed along with financial metrics. These points will be used to create risk scores based on many different risk factors. These risk scores are already provided and the marketplace has also provided quality scores. Both scores will be leverage to predict if the user is likely to respond to the current onboarding process.

 ## Model Details
 This case study uses various model and compares them against each model's Accuracy,	Precision,	Recall and	F1 Score.
 The following model were used:
 1. Linear Regression(Lasso)
 2. SVM(Linear)
 3. SVM(rbf)
 4. Random Forest(nx100)
 5. Random Forest (n=100, GSx2 + Gini)
 
 The following image shows various models' Accuracy,	Precision,	Recall and	F1 Score. 
<img width="1001" alt="Screen Shot 2020-07-22 at 2 28 07 pm" src="https://user-images.githubusercontent.com/39994111/88135511-90e76d00-cc2a-11ea-836b-87db30308a7e.png">
 
 Random Forest with n of 100, GSx2 and Gini is the best option by the model's various matrices
