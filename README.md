# Feature Engineering for Machine Learning

## Overview
Feature engineering is one of the most critical steps in building high-performing machine learning models.  
This repository showcases **end-to-end Exploratory Data Analysis (EDA) and Feature Engineering (FE)** workflows using real-world datasets.  

The notebooks demonstrate **practical preprocessing workflows**, focusing on data quality, statistical correctness, and model readiness.

---

## 📂 Repository Structure

| Notebook Name | Description |
|---------------|-------------|
| Handling missing values.ipynb | Techniques for identifying and imputing missing data |
| Handling imbalanced dataset.ipynb | Upsampling and downsampling methods |
| smote (oversampling tech).ipynb | Synthetic Minority Oversampling Technique (SMOTE) |
| Handling Outliers.ipynb | Outlier detection and treatment techniques |
| Nominal, OHE, Label & Ordinal Encoding.ipynb | Categorical feature encoding methods |
| Target Guided Ordinal Encoding.ipynb | Encoding categories based on target variable |

---

## Feature Engineering Techniques Covered

### 1️⃣ Missing Value Handling
- Mean, Median, Mode Imputation
- Forward Fill & Backward Fill
- Handling missing values based on data distribution
- Identifying missingness patterns

---

### 2️⃣ Handling Imbalanced Datasets
- **Upsampling** minority class
- **Downsampling** majority class
- Understanding bias introduced by imbalance
- Choosing techniques based on business context

---

### 3️⃣ SMOTE (Oversampling Technique)
- Synthetic sample generation
- Handling class imbalance without duplicating data
- When to use SMOTE vs traditional resampling

---

### 4️⃣ Outlier Detection & Treatment
- Detection Techniques:
  - IQR Method
  - Z-Score Method
- Treatment Techniques:
  - Capping
  - Removal
  - Transformation
- Impact of outliers on model performance

---

### 5️⃣ Categorical Feature Encoding
- Label Encoding
- One-Hot Encoding (Nominal Encoding)
- Ordinal Encoding
- Choosing encoding based on feature nature

---

### 6️⃣ Target Guided Ordinal Encoding
- Encoding categories using target statistics
- Mean target encoding
- Reducing high-cardinality categorical features
- Preventing data leakage

---

### 🔹 Case Studies

#### 📈 Flight Price Prediction
- Data Cleaning & Preprocessing
- Feature Encoding & Transformation
- Outlier Treatment
- Feature Engineering for price prediction
- Visualization & trend analysis
- Insights influencing airfare pricing

#### 📱 Google Play Store – EDA & Feature Engineering
- Data Cleaning & Missing Value Handling
- Category-wise and rating-based analysis
- Encoding categorical variables
- Feature scaling and transformation
- Visualization of installs, reviews, ratings
- Business insights for app performance

---

## 📊 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

---

## 🎯 Why This Repository Matters
- Demonstrates **real-world feature engineering workflows**
- Shows understanding beyond basic preprocessing
- Highlights decision-making based on data behavior
- Prepares datasets for **machine learning modeling**

---

## 🚀 Use Cases
- Classification problems with class imbalance
- Regression & predictive modeling
- Data preprocessing pipelines
