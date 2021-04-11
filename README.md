# Kaggle_HRAnalytics
Supervised Learning Competition in Kaggle: https://www.kaggle.com/c/datamexpt2020/overview 

## Description 

A company dedicated to Big Data and Data Science wants to hire data scientists among people who successfully have passed some courses which have been conduct by the company.

The competition aims at predicting if a candidate will work for the company based on the current credentials, demographics and experience. 

## Evaluation

Submissions will be evaluated based on their AUC score.

## Submission Format

For every candidate in the test dataset, submission files should contain two columns: enrollee_id and target. Remember that the target value is whether the candidate is looking for a job change(1), or isn't looking for a job change(0)
The file should contain a header and have the following format:

enrollee_id,target
00000,1
00001,0
00002,0

## Methodology

The repository includes supervised learning modelling for this binary classification problem (Feature Engineering & XGBoost) and the evaluation of the model (AUC).
