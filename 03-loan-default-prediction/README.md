# Loan Default Prediction

## Project Overview
This project aims to predict whether a customer is likely to default on a loan using machine learning classification algorithms.

## Dataset
The dataset contains 10,000 customer records with the following features:
- Employment Status
- Bank Balance
- Annual Salary

**Target Variable:** Defaulted (0 = No Default, 1 = Default)

## Project Workflow
1. Data Loading and Exploration
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Handling Class Imbalance
5. Train-Test Split
6. Feature Scaling
7. Model Training
8. Model Evaluation
9. Model Comparison

## Machine Learning Models
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- XGBoost Classifier

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

## Key Results

| Model | Accuracy | F1-Score | ROC-AUC |
|---|---:|---:|---:|
| Logistic Regression | 97.30% | 43.75% | 94.84% |
| Random Forest | 95.90% | 46.05% | 88.39% |
| SVM | 84.10% | 27.40% | 91.52% |
| XGBoost | 84.80% | 27.27% | 94.46% |

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## Conclusion
Random Forest achieved the highest F1-score, while Logistic Regression achieved the highest ROC-AUC and precision. The results highlight the importance of evaluating multiple metrics when working with an imbalanced classification dataset.
