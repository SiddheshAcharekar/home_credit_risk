# HomeCredit Risk Analysis (Originally a Kaggle Problem)
This is my work on the Home Credit risk database. Includes data, exploratory analysis, feature engineering, and model building for predicting repayment risk.

## Problem
Many people struggle to get loans due to insufficient or non-existent credit histories. And, unfortunately, this population is often taken advantage of by untrustworthy lenders. In order to make sure this underserved population has a positive loan experience, Home Credit makes use of a variety of alternative data--including telco and transactional information--to predict their clients' repayment abilities. The task therefore is to predict whether a loan applicant will default on his loan or not.

## Dataset
The data can be found at https://www.kaggle.com/c/home-credit-default-risk/data
Entity relationship diagram of the entire dataset:
<img src="home_credit_data_description.png" align="center" />

## Exploratory Data Analysis
The folder 'Feature Engineering' contains all exploratory data analysis done as multiple jupyter notebooks. To sum it up, all variables were explored, skewness of data and anomalies checked and new features were generated based on whatever domain knowledge I could get.

## Predictive models
I've tried predicting the outcomes for the test dataset using engineered features and many different machine learning algorithms. That can be found in the 'Models' folder.
