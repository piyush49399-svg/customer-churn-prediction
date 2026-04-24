# Customer Churn Prediction

## 📌 Overview
This project predicts customer churn using machine learning.

It was completed as part of the BCG Data Science Simulation.

---

## 🎯 Objective
To identify customers likely to churn and provide actionable business insights.

---

## 🔧 Workflow

### 1. Exploratory Data Analysis
- Analyzed customer and pricing data
- Identified patterns and distributions

### 2. Feature Engineering
- Created contract duration feature
- Generated price-based features (difference, ratio, range)
- Extracted date-based features

### 3. Model Building
- Random Forest Classifier
- Train-test split (80/20)

---

## 📊 Results
- Accuracy: ~90%
- Recall (churn): ~6%

---

## ⚠️ Key Insight
High accuracy is misleading due to class imbalance.  
The model fails to identify most churn customers.

---

## 💡 Recommendations
- Use class_weight='balanced'
- Apply SMOTE
- Focus on improving recall

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
