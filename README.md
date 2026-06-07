# HR Employee Attrition Prediction

## Overview
Predicting which employees are likely to leave the company
using IBM HR Analytics dataset. Helps HR teams intervene 
early and reduce attrition costs.

## Dataset
- Source: IBM HR Analytics (Kaggle)
- Records: 1470 employees, 35 features

## Approach
- Exploratory data analysis
- Handled class imbalance (84% stayed, 16% left)
- Tested Logistic Regression, Random Forest, XGBoost
- Chose Logistic Regression - best recall for minority class
- Power BI dashboard for HR insights

## Results
- Model Accuracy: 77%
- Recall for attrition class: 66%
- Attrition Rate in dataset: 16%
- Key finding: Frequent travel and job role are 
  strongest attrition drivers

## Top Attrition Drivers
1. BusinessTravel_Frequently - frequent travelers leave most
2. JobRole_Laboratory Technician
3. JobRole_Research Director
4. JobRole_Sales Representative
5. OverTime - overtime workers at higher risk

## Tools Used
- Python, Pandas, NumPy, Scikit-learn, XGBoost
- Jupyter Notebook
- Microsoft Power BI

## Dashboard
![Dashboard](dashboard.png)
