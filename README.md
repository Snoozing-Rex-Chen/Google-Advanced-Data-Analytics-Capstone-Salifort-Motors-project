# Google-Advanced-Data-Analytics-Capstone-Salifort-Motors-project
A machine learning project predicting employee turnover using data from Salifort Motors.
This project aims to predict employee turnover (attrition) based on historical data from Salifort Motors' HR department. The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction) and includes various features such as employee satisfaction level, project workload, and salary.

# HR Analytics Employee Turnover Prediction Project

This project focuses on analyzing HR data from Salifort Motors to predict employee turnover (attrition) using machine learning models. The goal is to identify the key factors contributing to employee turnover and to develop data-driven strategies for improving employee retention. The dataset was obtained from [Kaggle HR Analytics](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction) and includes various employee-related features such as satisfaction level, project workload, and salary.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Models Used](#models-used)
- [Evaluation Metrics](#evaluation-metrics)
- [PACE Strategy](#pace-strategy)
- [Acknowledgments](#acknowledgments)

---

## Project Overview

The HR department at Salifort Motors is facing challenges related to employee turnover. To address this issue, they have collected data on various aspects of employee performance, satisfaction, and workload. The primary objective of this project is to analyze this data and build predictive models to identify which employees are likely to leave the company, providing insights into the factors influencing their decision to leave.

This project aims to:
- Identify the most important factors leading to employee attrition.
- Build predictive models to classify whether an employee will leave or stay.
- Generate actionable business insights to improve retention rates.

---

## Dataset

The dataset used for this project contains 14,999 records and the following key features:

- **satisfaction_level**: Employee-reported job satisfaction level (0-1).
- **last_evaluation**: Last performance evaluation score (0-1).
- **number_project**: Number of projects the employee is assigned to.
- **average_monthly_hours**: Average number of hours worked per month.
- **time_spend_company**: Number of years the employee has been with the company.
- **work_accident**: Whether the employee had a work accident (binary).
- **left**: The target variable indicating whether the employee left the company (1 for left, 0 for stayed).
- **promotion_last_5years**: Whether the employee received a promotion in the last 5 years.
- **department**: The department the employee belongs to (e.g., sales, technical).
- **salary**: Salary level (low, medium, high).

The dataset can be found at [Kaggle HR Analytics](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction).

---

## Models Used

The project leverages several machine learning models to predict employee turnover:
1. **Logistic Regression**: A baseline classification model to predict whether employees will leave or stay.
2. **Decision Tree Classifier**: A simple tree-based model for understanding feature importance and decision rules.
3. **Random Forest Classifier**: An ensemble learning method that improves prediction accuracy by averaging multiple decision trees.
4. **XGBoost Classifier**: A powerful gradient-boosting model that optimizes performance and handles overfitting better than other models.
5. **XGBoost Regressor & Random Forest Regressor**: To predict employee performance (`last_evaluation`) based on features.

---

## Evaluation Metrics

The following metrics were used to evaluate model performance:

- **Accuracy**: The proportion of correctly predicted instances.
- **Precision**: The proportion of positive identifications (employees leaving) that were actually correct.
- **Recall**: The proportion of actual positive cases (employees who left) that were identified by the model.
- **F1-Score**: The harmonic mean of precision and recall, useful for imbalanced datasets.
- **ROC AUC**: The area under the receiver operating characteristic curve, measuring the model's ability to distinguish between classes.

## PACE Strategy

The project follows the PACE strategy for effective problem-solving and project management:

-Plan: Understand the business problem, define the goals, and explore the dataset.
-Analyze: Perform exploratory data analysis (EDA), identify trends and relationships between variables.
-Construct: Build and evaluate machine learning models to predict employee turnover.
-Execute: Generate actionable insights for stakeholders and provide business recommendations.

## Acknowledgments
-Dataset: [Kaggle HR Analytics](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction)
-This project was developed as part of the Salifort Motors Lab activity included in the Google Advanced Data Analytics Professional Certificate Course Series
