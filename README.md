# credit-risk-classification-challenge

Sean Guzman

Rutgers Data Sciences Bootcamp, Module 20 Challenge (18 July 2023)

## Overview
In this challenge, we use Python (Jupyter Notebook) and supervised learning to train and evaluate a model based on loan risk, using a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Data is loaded into our Jupyter notebook from the supplied csv file. The data is then split into training and testing sets to create a logistic regression model.

## Results
- Model with Original Data / Balanced Accuracy Score: 95.2%
    - Healthy Loan:
        - Precision: 100%
        - Recall: 99%
        -  F1 Score: 100%
    - High-Risk Loan:
        - Precision: 85%
        - Recall: 91%
        -  F1 Score: 88%

- Model with Resampled Data / Balanced Accuracy Score: 99.4%
    - Healthy Loan:
        - Precision: 100%
        - Recall: 99%
        -  F1 Score: 100%
    - High-Risk Loan:
        - Precision: 84%
        - Recall: 99%
        -  F1 Score: 91%
        
## Summary
After having resampled the data, the second model improved its balanced accuracy score as well as on recall for high-risk loans, which indicates a lower number of false negatives.  As a result, the second model is recommended to be used.

