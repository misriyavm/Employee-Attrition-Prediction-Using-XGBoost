# Employee-Attrition-Prediction-Using-XGBoost
Employee Attrition Analysis and Prediction Using Machine Learning on the IBM HR Analytics Dataset. 

# Employee Attrition Analysis and Prediction Using Machine Learning

## Introduction
Employee attrition is a major challenge for organizations, as high turnover increases recruitment costs and affects productivity. This project analyzes employee data from the IBM HR Analytics Employee Attrition & Performance Dataset to identify key factors influencing employee attrition and predict whether an employee is likely to leave the company.

## Objectives
- Perform Exploratory Data Analysis (EDA) on employee data.
- Identify factors influencing employee attrition.
- Handle class imbalance using SMOTE.
- Build and compare machine learning models.
- Predict employee attrition using XGBoost.

## Dataset
Dataset: IBM HR Analytics Employee Attrition & Performance Dataset

Number of Records: 1470

Target Variable: Attrition (Yes/No)

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Google Colab

## Exploratory Data Analysis (EDA)
The following analyses were performed:
- Missing value analysis
- Descriptive statistics
- Attrition distribution
- Department-wise attrition
- Job role analysis
- Overtime analysis
- Correlation analysis
- Feature importance analysis

## Machine Learning Models
1. Random Forest
2. XGBoost

## Model Performance

### Random Forest
Accuracy: 87.07%

### XGBoost
Accuracy: 82.65%

XGBoost provided better identification of attrition cases and better recall for employees likely to leave the organization.

## Key Factors Influencing Attrition
- OverTime
- StockOptionLevel
- MaritalStatus
- TotalWorkingYears
- Department
- JobInvolvement
- MonthlyIncome
- JobSatisfaction
- EnvironmentSatisfaction
- NumCompaniesWorked

## Conclusion
The study identified several important factors influencing employee attrition. XGBoost was used to predict employee turnover and provided useful insights that can help organizations improve employee retention and workforce planning.

## Author
Nafeesathul Misriya V M
MA Economics
Central University of Punjab
Data Analytics Intern - Softroniics
