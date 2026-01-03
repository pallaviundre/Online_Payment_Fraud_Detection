# Fraud Detection Using Machine Learning

## Overview
This project focuses on detecting fraudulent online payment transactions using machine learning techniques. Fraud detection is a challenging problem due to the highly imbalanced nature of transaction data, where fraudulent cases are rare but costly.

The goal of this project is to build and evaluate machine learning models that can effectively identify fraudulent transactions while minimizing false negatives.

---

## Dataset
- Historical online payment transaction data
- Target variable: `isFraud`
- Includes both numerical and categorical features
- Highly imbalanced dataset

---

## Approach
The project follows an end-to-end machine learning workflow:

1. Exploratory Data Analysis (EDA) to understand transaction patterns and class imbalance  
2. Data preprocessing and feature engineering  
3. Encoding categorical variables and removing irrelevant identifiers  
4. Train–test split for model evaluation  
5. Training multiple classification models  
6. Model evaluation using ROC-AUC and confusion matrix  

---

## Models Used
- Logistic Regression  
- Random Forest Classifier  
- XGBoost Classifier  

ROC-AUC was used as the primary evaluation metric due to the imbalanced nature of the dataset.

---

## Results
- XGBoost achieved the best performance based on validation ROC-AUC
- The confusion matrix shows strong performance in identifying non-fraudulent transactions
- Fraud detection remains challenging due to class imbalance, highlighting the importance of recall-focused evaluation

---

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

---

## Conclusion
This project demonstrates how machine learning can be applied to real-world financial fraud detection problems. The results highlight the importance of selecting appropriate models and evaluation metrics when working with highly imbalanced datasets.

