# Telecom-Customer-Churn-Prediction
End-to-end machine learning project to predict customer churn using real-world IBM telecom data.
# Telecom Customer Churn Prediction

📌 Project Overview
Customer churn is a critical challenge in the telecom industry, directly impacting revenue and customer retention.  
This project builds an end-to-end machine learning pipeline to predict whether a customer is likely to churn based on demographic, service usage, and billing information.

The focus of this project is not just accuracy, but **early churn detection using explainable models**.

---

📊 Dataset
- Source: IBM Telecom Customer Churn Dataset
- Type: Real-world industry dataset released by IBM
- Records: 7,043 customers
- Target Variable: `Churn` (Yes / No)

---
⚙️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

🧠 Machine Learning Workflow
1. Problem Definition  
2. Data Understanding & Exploratory Data Analysis  
3. Data Cleaning & Preprocessing  
4. Feature Encoding  
5. Train-Test Split  
6. Baseline Model: Logistic Regression  
7. Advanced Model: Random Forest  
8. Hyperparameter Tuning  
9. Model Evaluation  
10. Feature Importance Analysis  
11. New Customer Prediction  

---

📈 Models Used

Logistic Regression (Baseline)
- Simple and interpretable model
- Provides probability-based churn prediction
- Used as a benchmark for comparison

 Random Forest (Final Model)
- Captures non-linear feature interactions
- Improved recall for churn customers
- Feature importance improves explainability

---

🎯 Key Evaluation Metric
- **Recall is prioritized over accuracy**
- Missing a churn customer is more costly than a false positive

---

🔍 Results
- Logistic Regression Accuracy: ~81%
- Tuned Random Forest improves churn recall
- Model predicts churn probability for new customers

---

📌 Business Impact
- Identifies high-risk customers early
- Enables targeted retention strategies
- Supports data-driven business decisions

---

🚀 Future Improvements
- Deploy using Flask or Streamlit
- Experiment with XGBoost or LightGBM
- Cost-sensitive learning

---

👤 Author
**Aiswarya**  
