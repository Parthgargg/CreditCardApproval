# Credit Card Approval Prediction Model

## Problem Statement

Traditional credit card approval processes are manual and resource-intensive, relying on human underwriters to review applicants' financial details. This approach is time-consuming, prompting the need for a streamlined and efficient mechanism. This project aims to develop a machine learning model to automate credit card approval, optimizing accuracy and reducing the manual effort involved.

## Motivation

The motivation behind this model arises from the inefficiencies of existing manual credit card approval processes. The goal is to enhance speed and cost-effectiveness in credit decision-making by leveraging machine learning.

## Objectives

1. **Develop ML Model:** Create a robust machine learning model to classify credit card applicants into approved and declined categories, automating the approval process using historical data.
2. **Optimize Accuracy:** Minimize false positives and false negatives, striving for a precise credit card approval prediction model.

## Contribution

The model contributes by providing an automated mechanism that simplifies and accelerates credit card approval, reducing manual effort, enhancing time efficiency, and offering a scalable solution for evaluating credit risk.

## Proposed Work with Tools and Datasets Used

### Tools Used:
- **Data Inspection:** Evaluate dataset characteristics, ensuring data quality, and identifying patterns, outliers, or biases.
- **Data Imputation:** Fill missing values within the dataset for accurate model training.
- **Encoding Categorical Data:** Transform non-numeric categories into numerical representations.
- **Feature Engineering:** Transform and select input variables to improve model performance.
- **Criteria Analysis:** Evaluate and select appropriate performance metrics and evaluation criteria.

### Dataset:
The dataset used is sourced from Kaggle: [Credit Card Approval] , containing features such as Gender, Age, Debt, Marital Status, Education Level, and more.

### Algorithm:
**Logistic Regression:** Chosen as the foundational algorithm for its efficiency, interpretability, and suitability for binary classification tasks.

## Implementation

### Code Overview:

1. **Library Inclusion:** Import necessary libraries.
2. **Data Uploading and Inspection:** Load and inspect the dataset.
3. **Data Cleaning:** Handle missing values and impute data.
4. **Data Encoding:** Transform categorical data into numerical representations.
5. **Dataset Splitting:** Split the dataset into training and testing sets.
6. **Feature Scaling:** Scale features for uniformity.
7. **Logistic Regression:** Apply Logistic Regression for credit card approval prediction.
8. **Evaluation:** Evaluate model accuracy and create a confusion matrix.

## Result Analysis

### Target Variable:
The target variable is "Approval Status."

### Results:
The final model demonstrated 83.7% accuracy on testing data and 87% on training data.

### Confusion Matrix:
![image](https://github.com/Parthgargg/CreditCardApproval/assets/100117683/fb27e8b0-cd21-446f-8570-9d270596c459)

## Conclusion

This project successfully introduces a Credit Card Approval system using Logistic Regression, showcasing the power of machine learning in automating and optimizing financial decision-making. The model's accuracy and efficiency make it a promising solution for streamlining traditional credit approval procedures. The provided code, tools, and dataset details facilitate transparency and reproducibility for future use.


**Note:** Please ensure that the necessary libraries are installed before running the code.
