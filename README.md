# Airbnb_User_Booking_Prediction
Project for Machine Learning course 2020 Fall Semester - AI 511 @ IIIT Bangalore

## Objective
Predict the top 3 destinations a new user is most likely to book

## Problem Type
Multi Class Classification

## Best Model
Ensemble of RandomForestCLassifier, LightGBM and XGBoost made into a Stacking and then using LogisticRegression as the final estimator

## Tools
Scikit-Learn API for StackingClassifier with passthrough=True

## Score
Scoring Metric used is NDCG and the obtained score is 0.92256 on Kaggle's Private Leaderboard of In-Class Competetion.

## Original [Kaggle contest link](https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings/overview)
