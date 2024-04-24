# Insurance Claim Prediction

## About
For this project, we chose to look into insurance claim predictions due to 2 key problems we identified:
    1. Risk management: Insurance companies face the challenge of effectively managing their risk exposure. They need to accurately identify policyholders who are at a higher risk         of filing a claim, allowing them to adjust premiums accordingly or implement proactive measures to mitigate potential risks.
    2. Financial Planning: One of the key issues for insurance companies is forecasting their financial liabilities accurately. This involves the challenge of predicting claim             filings with precision, enabling insurers to establish suitable reserves and efficient allocation of resources to prevent cases of insufficient liquidity 

## Problem Definition
How can insurance companies increase their prediction accuracy of whether or not a policy holder will file a claim in the next 6 months?

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

## Contributors
- Diong Wei Chong
- Ee Wen Hui, Evlyn

## References
- https://www.kaggle.com/datasets/ifteshanajnin/carinsuranceclaimprediction-classification 
- https://forecastegy.com/posts/feature-importance-in-random-forests/
