# HR Analytics Attrition Prediction Project

This project aims to predict employee attrition in a company using HR analytics. It involves analyzing various factors that may contribute to employee attrition and building a predictive model to identify employees at risk of leaving the organization.

## Introduction

Employee attrition can have significant impacts on a company's productivity, morale, and bottom line. By understanding the factors that contribute to attrition, organizations can implement strategies to retain valuable employees and mitigate the negative effects of turnover.

## Dataset

The dataset used in this project contains information about employees, including demographic data, job-related factors, and attrition status. It includes features such as age, job role, education level, job satisfaction, and more.

## Data Analysis

The project involves thorough data analysis to identify patterns and trends related to employee attrition. Exploratory data analysis techniques are used to visualize the relationship between different variables and attrition status.

### Key Insights:

- **Age vs Attrition:** Employees in their late 20s to early 30s and younger employees (18-20) have higher attrition rates. Older employees tend to have lower attrition rates.
- **DailyRate vs Attrition:** Employees with daily rates between $300-600 exhibit higher attrition rates.
- **DistanceFromHome vs Attrition:** Longer commute distances are associated with higher attrition rates.
- **MonthlyIncome vs Attrition:** Employees with lower monthly incomes have higher attrition rates, indicating dissatisfaction with compensation.
- **StockOptionLevel vs Attrition:** Employees without stock options have higher attrition rates compared to those with stock options.
- **WorkLifeBalance vs Attrition:** Poor work-life balance is correlated with higher attrition rates.
- and so on

## Model Performance

### Logistic Regression:

- **Accuracy:** 90.89%
- **F1-score (Class 1):** 90.57%
- **Precision (Class 1):** 93.91%
- **Recall (Class 1):** 87.45%
- **AUC (Class 1):** 96.12%

## Feature Importance

- **OverTime_Yes:** Employees who work overtime are more likely to leave the company.
- **YearsAtCompany:** Longer tenure at the company does not guarantee retention, and employees with more years at the company are also more likely to leave.
- **NumCompaniesWorked:** Employees who have worked for more companies in the past are more likely to leave, indicating a potential pattern of job hopping.
- **DistanceFromHome:** Employees who live farther away from the workplace are more likely to leave, possibly due to commuting issues or a desire for a better work-life balance.
- **YearsSinceLastPromotion:** Employees who have not received a promotion in a long time are more likely to leave, indicating a potential dissatisfaction with career advancement opportunities.

## Conclusion

Based on the analysis, several factors are identified as significant contributors to employee attrition. These insights can inform HR policies and strategies to improve employee retention and organizational performance.

## Usage

1. Clone the repository.
2. Install the required dependencies.
3. Run the Jupyter notebooks to execute the analysis and build predictive models.

