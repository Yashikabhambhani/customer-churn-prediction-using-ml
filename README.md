# 📊 Customer Churn Prediction using Machine Learning

This project uses machine learning to predict customer churn based on demographics, service usage patterns, and billing data. The goal is to help businesses identify at-risk customers and take proactive retention measures.

---

## 🗂️ Dataset

- **Source:** Kaggle – Telco Customer Churn Dataset  
- **Features Include:**  
  - Customer demographics (gender, senior citizen, etc.)  
  - Service details (internet service, contract type, etc.)  
  - Billing information (monthly and total charges)  
  - Target variable: **Churn** (Yes/No)

---

## 🔧 Tools & Technologies

- **Languages & Libraries:** Python, Pandas, NumPy  
- **Machine Learning:** Scikit-learn, XGBoost  
- **Visualization:** Matplotlib, Seaborn  
- **Data Balancing:** SMOTE  
- **Model Deployment:** Pickle  
- **Environment:** Jupyter Notebook

---

## 📈 Workflow

1. **Data Cleaning**
   - Handled missing values
   - Removed irrelevant features (e.g., customer ID)

2. **Exploratory Data Analysis (EDA)**
   - Visualized trends, patterns, and feature relationships with churn

3. **Feature Engineering**
   - Encoded categorical variables using `LabelEncoder`

4. **Class Imbalance Handling**
   - Used SMOTE to balance churn vs non-churn instances

5. **Model Building**
   - Trained and evaluated:
     - Decision Tree
     - Random Forest
     - XGBoost

6. **Model Evaluation**
   - Evaluated using Accuracy Score, Confusion Matrix, and Classification Report

7. **Model Deployment**
   - Serialized final model and encoders using `pickle` for future predictions

---

## ✅ Key Takeaways

- Developed a full ML pipeline from preprocessing to deployment
- Gained hands-on experience with imbalanced data using SMOTE
- Compared multiple classification algorithms for performance
- Built a deployable solution for a real-world business use case

---

## 📁 Files Included

- `customer_churn_model.pkl` – Serialized ML model
- `encoders.pkl` – Saved encoders for consistent preprocessing
- `Customer_Churn_Prediction.ipynb` – Full Jupyter notebook with code and output

---

## 📬 Contact

**Yashika Bhambhani**  
[LinkedIn](https://www.linkedin.com/in/yashikabhambhani)  
📧 yashikabhambhani.tech@gmail.com



