# Employee Attrition Prediction Using Machine Learning

## Project Overview

This project aims to predict whether an employee is likely to leave the company based on various employee-related factors. The goal is to help organizations identify employees at risk of attrition and take proactive retention measures.

## Dataset

Dataset: IBM HR Analytics Employee Attrition Dataset

Features include:

* Age
* Monthly Income
* Job Role
* Education
* Years at Company
* Job Satisfaction
* Work-Life Balance
* Overtime
* And other employee-related attributes

Target Variable:

* Attrition (Yes/No)

## Project Workflow

### 1. Data Preprocessing

* Checked for missing values
* Removed unnecessary columns
* Encoded categorical variables
* Prepared data for model training

### 2. Exploratory Data Analysis (EDA)

* Analyzed employee demographics
* Studied attrition trends
* Examined feature distributions
* Identified important factors affecting attrition

### 3. Model Building

The following machine learning algorithms were trained and evaluated:

* Logistic Regression
* Decision Tree
* K-Nearest Neighbors (KNN)
* Random Forest
* Support Vector Machine (SVM)
* Naive Bayes
* XGBoost

### 4. Model Evaluation

Evaluation metrics:

* Accuracy
* Precision
* Recall
* F1-Score

### Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 0.86     |
| Decision Tree       | 0.77     |
| KNN                 | 0.85     |
| Random Forest       | 0.87     |
| SVM                 | 0.87     |
| Naive Bayes         | 0.79     |
| XGBoost             | 0.88     |

### Hyperparameter Tuning

GridSearchCV was applied to optimize the XGBoost model.

Best Parameters:

* learning_rate = 0.2
* max_depth = 3
* n_estimators = 50

Final Model Performance:

* Training Accuracy: 94.98%
* Testing Accuracy: 88.78%

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost

## Conclusion

XGBoost achieved the best performance with a testing accuracy of 88.78% after hyperparameter tuning and was selected as the final model for employee attrition prediction.
