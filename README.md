#🧠 Breast Cancer Detection Using Machine Learning


This repository contains the research paper, code, and resources for Breast Cancer Detection Using Machine Learning, where we propose and evaluate a machine learning framework for accurate breast cancer classification.

📄 Abstract
Breast cancer is one of the leading causes of death among women globally. Early and accurate diagnosis plays a vital role in improving survival rates.
In this research, we implemented and compared multiple machine learning models on the Wisconsin Breast Cancer Diagnostic (WBCD) dataset to classify tumors as benign or malignant.
Our experiments demonstrate that the proposed models achieve high accuracy and can assist healthcare professionals in making better clinical decisions.

#📊 Dataset
Dataset: Wisconsin Breast Cancer Diagnostic Dataset

Source: Kaggle

Features: 30 numerical features (15 selected for modeling)

Target: Diagnosis → M (malignant), B (benign)

#🤖 Machine Learning Models Used
The following models were implemented and evaluated as described in the research paper:

Logistic Regression

K-Nearest Neighbors (KNN)

Naïve Bayes (NB)

Support Vector Machine (SVM)

Random Forest (RF)

XGBoost (XGB)

Voting Classifier (RF + XGB)

Stacking (RF + XGB + Logistic Regression)

We applied data preprocessing, feature scaling, hyperparameter tuning, and cross-validation for robust model evaluation.

#🏆 Key Results

| Model                               | Accuracy (%) | Precision (%) | Recall (%) | F1-Score (%) |
| ----------------------------------- | ------------ | ------------- | ---------- | ------------ |
| Logistic Regression                 | 92.5         | 91.8          | 90.2       | 91.0         |
| K-Nearest Neighbors (KNN)           | 93.2         | 92.5          | 91.0       | 91.7         |
| Naïve Bayes (NB)                    | 90.8         | 89.5          | 88.0       | 88.7         |
| Support Vector Machine (SVM)        | 94.0         | 93.2          | 92.1       | 92.6         |
| Random Forest (RF)                  | 96.5         | 95.8          | 96.0       | 95.9         |
| XGBoost (XGB)                       | 97.1         | 96.5          | 96.8       | 96.6         |
| Voting Classifier (RF + XGB)        | 97.3         | 96.7          | 97.0       | 96.8         |
| Stacking (RF + XGB + Logistic Reg.) | 98.2         | 97.8          | 98.0       | 97.0         |

