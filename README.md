# Responsible_AI_Credit_Card_Default_Prediction

White bank has approached us for a solution to their decreasing profitability and increasing customer defaults despite the increase in the number of customers in the credit division.

## Dataset
We have a csv with the information of 30000 customers.
There are 23 features
Target variable: Default

## Requirement
Perform prediction while maintaining fairness in the modelling and testing keeping in mind AI should be ethical ,responsible and good for society.

## Approach
We performed exploratory data analysis on the dataset.
We did a lot of domain research.
We check for similarity between the features.
We performed pre-processing steps - dropping columns, adding noise, imputation, feature engineering, and creating composite features.
Create multiple models - raw, differential privacy in linear based and tree based models.
We have added ACF (Additive counter factual fairness) and compared results
We have use data explainability techniques for our model
