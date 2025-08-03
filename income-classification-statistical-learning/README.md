# 💼 Income Classification Using Statistical Learning

This project explores predicting whether individuals earn more than $50K annually using demographic and occupational attributes from the 1994 U.S. Census dataset. It compares the effectiveness of multiple models including linear regression, logistic regression, and decision trees.

## 📊 Objective

Classify individuals into:
- `<=50K`
- `>50K`

## 📁 Dataset

The [Adult dataset](https://archive.ics.uci.edu/ml/datasets/adult) from the UCI Machine Learning Repository contains attributes such as age, education, occupation, hours worked per week, and more.

## 🔍 Key Steps

- Handled missing values (`?`) with mode imputation
- Dropped non-predictive or redundant columns
- Detected and removed outliers (age)
- Grouped low-frequency countries into “Other”
- Encoded categorical features (label encoding and one-hot encoding)
- Standardized numeric features

## 🧠 Models Used

| Model              | Accuracy | Notes |
|-------------------|----------|-------|
| Linear Regression | ~84%     | Weak recall on high-income class |
| Logistic Regression | ~85%   | Better class separation, clearer probabilities |
| Decision Tree (depth=9) | ~87% | Best performance after tuning |

## 🧪 Evaluation Metrics

- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix
- ROC Curve and AUC

## 📈 Visuals

- Confusion matrices
- Residual plots
- Predicted probability distributions
- ROC curves for all models

## ⚙️ Libraries Used

- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn` for modeling and evaluation

## 📄 Report

You can view the full project write-up here:  
📎 [`income_classification_report.pdf`](income_classification_report.pdf)
