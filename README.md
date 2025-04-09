# 🧠 Adult Salary Prediction - Machine Learning Project

## 📌 Project Overview

This project aims to predict whether an individual earns more than **$50K annually** based on various features such as age, education, occupation, and more. It's based on the popular **Adult Income dataset** and demonstrates the end-to-end workflow of a real-world machine learning classification problem.

---

## 📊 Dataset Summary

- **Source:** UCI Machine Learning Repository  
- **Target:** `Salary` (<=50K or >50K)  
- **Features:** Age, Workclass, Education, Marital Status, Occupation, Race, Gender, Capital Gain, Hours/Week, etc.

---

## 🛠️ Technologies Used

- Python (Pandas, Numpy)
- Scikit-learn
- Matplotlib & Seaborn
- SMOTE (for imbalanced class handling)
- Jupyter Notebook

---

## 🔍 Project Steps

### 1. Exploratory Data Analysis (EDA)
- Visualized distributions and relationships
- Checked for missing values and duplicates

### 2. Data Preprocessing
- Handled missing values
- Removed **outliers** in numerical features
- Converted categorical variables using **Label Encoding**

### 3. Feature Engineering
- Balanced dataset using **SMOTE**

### 4. Model Building
- Used **Logistic Regression** and **Random Forest**
- Performed **Hyperparameter Tuning** using GridSearchCV

### 5. Evaluation
- Evaluated using Accuracy, Precision, Recall, F1-Score
- Visualized Confusion Matrix

---

## 📈 Results

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | 81.41%    |
| Random Forest       | 84.97%    |

✅ Best performance achieved with **Random Forest + SMOTE**



