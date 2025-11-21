## Optimized Machine Learning Framework for Heart Disease Prediction 

Cardiovascular diseases remain one of the leading causes of death worldwide. Early and accurate identification of risk factors is essential for effective medical intervention. 
This research introduces an Optimized Machine Learning Framework that combines traditional machine learning models with the Whale Optimization Algorithm (WOA) to enhance the precision of heart disease prediction.

## Overview
This study utilizes two different datasets to assess the framework's robustness and real-world applicability:
1.Healthcare Stroke Dataset
2.Cleveland Heart Disease Dataset
Both datasets target different cardiovascular conditions, allowing us to evaluate the model’s generalizability across related medical domains.

## Dataset Processing and Methodology
# 1. Healthcare Stroke Dataset

-> Addressed class imbalance using SMOTE.
-> Applied SHAP (SHapley Additive Explanations) for feature importance analysis.
-> Identified the top 5 most influential features and used them for model training.
The following machine learning models were trained:
1.Logistic Regression
2.Random Forest
3.XGBoost
4.KNN
5.SVM

XGBoost achieved the highest baseline accuracy of 86%.
After hyperparameter tuning using WOA, accuracy improved significantly to 93%, confirming WOA's effectiveness for optimization.
SHAP was also utilized to provide interpretability and explain how each feature influenced model predictions.

# 2. Cleveland Heart Disease Dataset

A similar workflow was applied:

Used Logistic Regression, Random Forest, XGBoost,KNN and SVM
Employed permutation-based feature importance to identify key predictors
Logistic Regression achieved an accuracy of 86%.
Optimizing with WOA increased accuracy to 87%, demonstrating consistent performance improvements.

## Why Two Datasets?

1.Healthcare Stroke Dataset focuses on identifying stroke risk factors.
2.Cleveland Heart Disease Dataset predicts heart disease presence.
Evaluating performance on both datasets demonstrates the robustness, adaptability, and practical applicability of the proposed framework across distinct but related cardiovascular conditions.

## Technologies Used

1.Python

2.Scikit-learn

3.XGBoost

4.SHAP

5.SMOTE

6.Whale Optimization Algorithm (WOA)

7.Pandas, NumPy, Matplotlib

## CONCLUSION
The proposed framework significantly improves prediction accuracy through advanced optimization and explainability techniques. 
Integrating WOA with traditional machine learning models provides a scalable and interpretable solution for cardiovascular risk prediction, making it suitable for real-world clinical and preventive healthcare applications.
