# project03
Exploring customer behavior to bank marketing campaigns
 The Problem
Banks face challenges in effectively targeting customers for term deposits.
Inefficient targeting leads to wasted resources and lower campaign ROI.
Objective: Improve customer targeting to increase term deposit subscription rates.
Stakeholders:
Bank marketing teams.
Campaign managers.
Bank executives seeking higher ROI.

The Dataset
Source: UCI Machine Learning Repository.
Dataset Size: 45,211 records, 17 attributes.
Key Features:
Customer demographics (e.g., age, job, marital status).
Campaign information (e.g., contact duration, communication type).
Historical data (e.g., previous campaign outcomes).

Relevance of Data
Why This Data Matters:
Demographic and campaign attributes directly influence customer decisions.
Historical outcomes help predict future campaign success.
Initial Insights:
Imbalanced classes: 88% of customers did not subscribe to a term deposit.
Certain features, like age and job type, show patterns in subscription rates

Data Preparation Process
Steps Taken:
Handled missing values by removing incomplete records.
Encoded categorical features (e.g., job, education).
Normalized numerical data for consistency.
Challenges:
Addressing class imbalance using SMOTE.
Removing irrelevant or redundant features.

Predictive Modeling Process
Baseline Model: Logistic regression for initial insights.
Iterative Improvements:
Tried Random Forest, Gradient Boosting, and Decision Trees.
Evaluated models using precision, recall, and F1 score.
Metrics Focus: Balance between precision (avoiding false positives) and recall (capturing potential subscribers).

Key Findings
Final Model: Gradient Boosting outperformed other models.
Performance Metrics:
Accuracy: 91%
Precision: 84%
Recall: 76%
Insights:
"Contact duration" is the most predictive feature.
Customers with prior campaign success are more likely to subscribe

Actionable Strategies
Targeted Campaigns: Focus on customers with high predictive scores.
Feature Utilization: Prioritize long call durations and prior success.
Optimization: Use model predictions to allocate resources efficiently


