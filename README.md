# Customer-Churn-Prediction
Customer Churn Prediction using Scikit-learn [Machine-learning Model]

 # Project Overview
Customer churn prediction is a machine learning project that identifies customers who are likely to leave a telecom service.  
The goal of this project is to help businesses take proactive retention actions by predicting churn in advance.

#  Problem Statement
Telecom companies face revenue loss when customers discontinue their services.  
This project aims to build a **classification model** that predicts whether a customer will churn based on historical data.

# Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

# Dataset
- **Dataset**: Telecom Customer Data  
- Contains customer demographics, service usage, and subscription details  
- Target variable: `Churn` (Yes / No)

# Approach
1. Data loading and exploration
2. Train-test split with stratification
3. Feature separation (Numerical & Categorical)
4. Data preprocessing:
   - StandardScaler for numerical features
   - OneHotEncoder for categorical features
5. Model training using **Logistic Regression**
6. Model evaluation using:
   - Accuracy
   - Classification Report
   - Confusion Matrix
7. Model saved using `joblib` for reuse

# Model Performance
- Accuracy: ~79%
- Churn Recall (Class 1): ~54%
- Evaluated model performance beyond accuracy to understand business impact

# Business Impact
- Identifies customers likely to churn
- Helps telecom companies design retention strategies
- Reduces revenue loss by proactive decision-making

# Model Saving
The trained preprocessing pipeline and model were saved as a `.pkl` file using `joblib`, making the solution production-ready.

# Future Improvements
- Try advanced models like Random Forest or XGBoost
- Handle class imbalance using SMOTE
- Deploy model using Flask or Streamlit

# Author
Vikas Kumar

