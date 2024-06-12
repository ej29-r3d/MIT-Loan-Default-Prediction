# MIT-Loan-Default-Prediction

**Project Overview**

This repository contains my capstone project for the MIT Data Science courses. The project focuses on developing a machine learning model to predict loan defaults using the Home Equity (HMEQ) dataset. The model aims to be accurate, interpretable, and fair, mitigating potential biases in the loan approval process.

**Key Objectives**

*   Identify the primary factors influencing loan defaults.
*   Build and compare multiple classification models (Logistic Regression, Decision Tree, Random Forest).
*   Measure and mitigate biases in the loan approval process.
*   Ensure model interpretability and actionable insights for credit officers.

**Dataset**

The HMEQ dataset contains information on 5,960 recent home equity loans, including applicant information, loan details, and a binary target variable indicating loan default.

**Data Preprocessing**

*   Handled missing values using median imputation for numerical features and mode imputation for categorical features.
*   Addressed outliers and normalized features.
*   Encoded categorical variables using one-hot encoding.

**Models**

The project explored the following classification models:

*   **Logistic Regression**
*   **Decision Tree (with hyperparameter tuning)**
*   **Random Forest (with hyperparameter tuning)**

**Evaluation**

Model performance was evaluated using accuracy, precision, recall, F1-score, and ROC AUC. The Random Forest model performed the best, achieving an accuracy of 91.1% and an ROC AUC of 0.829.

**Bias Mitigation**

The project discusses potential biases in the dataset and strategies to mitigate them in future work.

**Interpretability**

The Logistic Regression model offers the most interpretable results, while the Random Forest model provides feature importance insights.

**Author**

*   Ilia Kolesnikov (i.a.kolesnikov@gmail.com)

**License**

This project is licensed under the MIT License - see the LICENSE file for details.

