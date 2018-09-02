# Predicting Loan Default Risk (using Python)

Goal
--------------------
Predict the probability an applicant will default on a loan using information from the application, previous credit, cash and installment loan payments, and monthly credit card balances. 

Data
--------------------
Data is available from Kaggle: https://www.kaggle.com/c/home-credit-default-risk

Process
--------------------
This complex dataset involved aligning the grain of additional sources to grain of current application. We did a lot of feature engineering and experimented with automatic feature selection. To reduce dimensions we first we used Principal Component Analysis but had better AUC when using Linear Discriminent Analysis. Our final model was a LightGBM Classifier with crossfold validation. 

I entered this competition with my high school son. This was our first Kaggle competition. We are very pleased to finish in top half out of 7198 teams. Our final rank was 47%, our highest rank was 32%. 
