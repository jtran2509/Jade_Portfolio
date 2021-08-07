# Estimating Car Price based on Various Car's Aspect using KNN

## Quick Intro

## Problem Statement
- The dataset is adopted from [UCI](https://archive.ics.uci.edu/ml/datasets/automobile)

## Approach 
- First, I use **Pandas & Numpy** & other Python packages to clean the dataset by imputing missing values & pick out numeric column and normalize them to apply to machine learning model. Then, I use K-NN to train & test the clean dataset to calculate RMSE in order to decide how many features of a car is important in determining its price


## Result
- Successfully build a pipeline for both univariate & multivariate model to compute RMSE
