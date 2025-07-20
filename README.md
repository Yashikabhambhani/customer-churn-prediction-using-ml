# 📊 Customer Churn Prediction using Machine Learning

This project focuses on predicting customer churn for a telecom company using machine learning models. The dataset includes customer demographics, service usage patterns, and billing data. The goal is to identify customers who are likely to stop using the service, enabling proactive retention strategies.

## 🔧 Tools & Technologies
- Python, Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn
- SMOTE (for handling class imbalance)
- Jupyter Notebook
- Pickle (model serialization)

## 🗂️ Dataset
- Source: IBM Sample Dataset – `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- Features include customer demographics, service details, charges, and churn status.

## 📈 Workflow
1. **Data Cleaning** – Handled missing values and dropped irrelevant features.
2. **Exploratory Data Analysis (EDA)** – Visualized trends and correlations.
3. **Feature Engineering** – Label encoding of categorical variables.
4. **Class Balancing** – Used SMOTE to address class imbalance in churn labels.
5. **Model Building** – Trained multiple models:
   - Decision Tree
   - Random Forest
   - XGBoost
6. **Evaluation** – Assessed models using:
   - Accuracy
   - Confusion Matrix
   - Classification Report
7. **Deployment Ready** – Saved the final model using `pickle`.

## 📌 Key Takeaways
- Learned to work with imbalanced data using SMOTE.
- Compared performance across multiple classification algorithms.
- Built a deployable machine learning pipeline for business insights.

## 📁 Project Structure
