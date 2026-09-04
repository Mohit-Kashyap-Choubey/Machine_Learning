# 💳 Credit Card Fraud Detection

## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning. The objective is to classify transactions as legitimate or fraudulent based on transaction patterns and customer behavior.

The project follows an end-to-end machine learning workflow, from data understanding and exploratory analysis to preprocessing, model training, evaluation, and comparison.

## 🎯 Objectives

* Understand the characteristics of fraudulent transactions.
* Perform exploratory data analysis (EDA).
* Preprocess and transform transaction data.
* Train multiple classification models.
* Evaluate models using appropriate performance metrics.
* Compare model performance and identify the best-performing approach.
* Maintain a reproducible machine learning workflow.

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## 📂 Project Structure

```text
Credit-Card-Fraud-Detection/
│
├── dataset/
├── notebooks/
└── README.md
```

## 🔄 Workflow

1. Data Understanding
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Model Training
5. Model Evaluation
6. Model Comparison
7. Conclusion

## 🤖 Models

The following classification models were trained and evaluated:

* Logistic Regression
* Decision Tree
* Random Forest

## 📊 Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Confusion Matrix
* Precision-Recall Curve
* Threshold Analysis

## 🔍 Key Findings

* Fraudulent transactions showed strong differences in transaction ratio, transaction distance, and online ordering behavior.
* `ratio_to_median_purchase_price` was the most influential feature for the tree-based models.
* Decision Tree and Random Forest significantly outperformed Logistic Regression on this dataset.
* The tree-based models achieved near-perfect performance on the test set.

## ⚠️ Important Note

The near-perfect model performance is specific to this dataset and should not be interpreted as representative of real-world credit card fraud detection. The dataset contains strong patterns separating fraudulent and legitimate transactions, which may not exist in real-world financial data.

## ✅ Project Status

**Complete**

The project covers the complete workflow from data exploration and preprocessing to model training, evaluation, comparison, and final conclusions.
