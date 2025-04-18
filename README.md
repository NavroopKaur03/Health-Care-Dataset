# 🩺 Diabetes Dataset - Multi-Class Classification Project
---

## 📌 Project Overview

This project involves building a machine learning model to classify individuals into three health categories: **Yes (Diabetic)**, **No (Non-Diabetic)**, and **P (Prediabetic)** based on medical attributes. The dataset includes several preprocessing challenges, such as class imbalance and inconsistent labeling, which are addressed in the notebook.

---

## 🧪 Dataset Summary

- **Classes**:
  - `Y`: Diabetic
  - `N`: Non-Diabetic
  - `P`: Prediabetic
- **Note**: Initial labels included extra spaces (e.g., `' Y'`, `' N'`) which were cleaned during preprocessing.
- **Issue Identified**: Expected 3 classes, but raw data included 5 due to label inconsistencies.

---

## ⚙️ What This Notebook Covers

- Data loading and initial inspection  
- Cleaning whitespace and inconsistent class labels  
- Exploratory Data Analysis (EDA)  
- Class distribution analysis  
- Feature selection and normalization  
- Model building using classification algorithms  
- Evaluation using accuracy, precision, recall, and F1-score  

---

## 🔧 Tools & Libraries Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## 🚀 Results & Findings

- Class imbalance was addressed to ensure fair prediction across all three classes.  
- The model was able to identify prediabetic and diabetic patients with reasonable performance after label correction.  
- Highlights the importance of proper label formatting in classification tasks.  

---
