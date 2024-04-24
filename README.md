# Insurance Claim Prediction

## About

This is a 

  
## Contributors
- Diong Wei Chong
- Ee Wen Hui, Evlyn

## Problem Definition
How can insurance companies increase their prediction accuracy of whether or not a policy holder will file a claim in the next 6 months??

## Data Cleaning/Preparation
- Checking for unique and null values 

## Exploratory Data Analysis
- Visualizing the class distribution of the response variable (Claim vs No Claim)
- Exploring numeric data types using KDEplot, Histplot
- Exploring categorical data types using countplot, histograms and heatmaps
- Perform downsampling to reduce class imbalance in the response variable. Large class imbalance will result in high accuracy in predicting the majority class, but will neglect prediction of the minority class. 

## Models Used

1. Naive Bayes Classification
2. Random Forest
3. Voting Classifier

## Conclusion
- Key variables in predicting "is_claim" are 
      1. Age of policyholder
      2. Age of car
      3. Duration of policy tenure

## What did we learn from this project?
- Identified Random Forest Model as our preferred model due to high predictive accuracy

## References

- https://forecastegy.com/posts/feature-importance-in-random-forests/
