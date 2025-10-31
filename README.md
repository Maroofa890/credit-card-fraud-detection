# 💳 Credit Card Fraud Detection (R)

Detecting fraudulent credit card transactions using *R* and machine learning.

## 🧠 Overview
This project applies *caret, **DMwR, and **XGBoost* to identify fraudulent transactions in an imbalanced dataset of over 280,000 records from Kaggle. It demonstrates skills in data preprocessing, SMOTE sampling, model training, and performance evaluation using ROC-AUC and recall metrics.

## 🔍 Key Features
- Data analysis and visualization with ggplot2
- SMOTE-based class balancing via DMwR
- Model training and tuning using caret (method = "xgbTree")
- Evaluation metrics: Accuracy, Precision, Recall, F1, and AUC
- Clear comparison of models: Logistic Regression, Random Forest, and XGBoost

## 📊 Model Performance
| Model | Accuracy | Precision | Recall (Fraud) | F1 | AUC |
|--------|-----------|------------|----------------|----|------|
| Logistic Regression | 0.98 | 0.82 | 0.70 | 0.75 | 0.97 |
| Random Forest | 0.99 | 0.90 | 0.78 | 0.84 | 0.99 |
| *XGBoost* | *0.99* | *0.92* | *0.81* | *0.86* | *0.995* |

## 🧩 Tech Stack
R | caret | DMwR | ggplot2 | pROC | XGBoost

## 📁 Dataset
[Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## 🌐 Live Demo
🔗 [View Project on GitHub Pages](https://maroofa890.github.io/credit-card-fraud/Credit-Card-Fraud-Detection.html)

## 📜 License
This project is created for educational and research purposes. Dataset is anonymized.
