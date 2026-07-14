# Employee Attrition Analysis and Prediction Using Machine Learning

## Introduction

Employee attrition is a major challenge for organizations, as high turnover increases recruitment costs and affects productivity. This project analyzes employee data from the IBM HR Analytics Employee Attrition & Performance Dataset to identify key factors influencing employee attrition and predict whether an employee is likely to leave the organization using machine learning techniques.

## Objectives

- Perform Exploratory Data Analysis (EDA) on employee data.
- Identify factors influencing employee attrition.
- Handle class imbalance using SMOTE.
- Build and compare machine learning models.
- Predict employee attrition using machine learning techniques.
- Support HR decision-making using data-driven insights.

## Dataset

**Dataset:** IBM HR Analytics Employee Attrition & Performance Dataset

- Number of Records: 1470
- Number of Features: 35
- Target Variable: Attrition (Yes/No)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Google Colab

## Exploratory Data Analysis (EDA)

The following analyses were performed:

- Missing value analysis
- Descriptive statistics
- Attrition distribution analysis
- Department-wise attrition analysis
- Job role analysis
- Overtime analysis
- Correlation analysis
- Feature importance analysis

## Machine Learning Models

1. Random Forest
2. XGBoost

## Model Performance

| Model | Accuracy |
|---------|---------|
| Random Forest | 87.07% |
| XGBoost | 82.65% |

Although Random Forest achieved higher overall accuracy, XGBoost demonstrated better capability in identifying employees at risk of attrition and was therefore used for feature importance analysis.

## Key Factors Influencing Employee Attrition

The XGBoost model was used to identify the most influential factors affecting employee attrition. Feature importance scores indicate the relative contribution of each variable in predicting employee turnover.

| Factor | Importance (%) |
|----------|----------|
| OverTime | 9.33 |
| StockOptionLevel | 6.13 |
| MaritalStatus | 5.03 |
| TotalWorkingYears | 4.79 |
| Department | 4.45 |
| JobInvolvement | 4.19 |
| MonthlyIncome | 4.12 |
| JobSatisfaction | 4.10 |
| EnvironmentSatisfaction | 3.76 |
| NumCompaniesWorked | 3.61 |

### Interpretation

- OverTime (9.33%) was the most influential factor affecting employee attrition.
- Employees with lower StockOptionLevel (6.13%) showed a higher likelihood of leaving.
- MaritalStatus (5.03%) and TotalWorkingYears (4.79%) contributed significantly to attrition prediction.
- JobInvolvement (4.19%), MonthlyIncome (4.12%), and JobSatisfaction (4.10%) played important roles in employee retention.
- Workplace-related factors such as EnvironmentSatisfaction (3.76%) were associated with employee turnover.

**Note:** Feature importance values indicate predictive influence within the model and do not necessarily imply causation.

## Results

The analysis revealed that overtime, compensation-related benefits, job satisfaction, and workplace environment were among the most influential factors affecting employee turnover.

The developed machine learning model can help organizations identify employees at risk of leaving and support employee retention strategies.

## Conclusion

This study successfully applied Exploratory Data Analysis and machine learning techniques to analyze employee attrition using the IBM HR Analytics dataset. The findings highlight several important factors influencing employee turnover and demonstrate how predictive analytics can support data-driven HR decision-making and workforce planning.

## Author

**Nafeesathul Misriya V M**
MA Economics, Central University of Punjab
Data Analytics Intern – Softroniics
