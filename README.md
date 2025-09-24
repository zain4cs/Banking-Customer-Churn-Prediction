# 🏦 Banking Customer Churn Prediction

This project analyzes customer data to predict whether a client will exit (churn) from a bank.  
The goal is to help financial institutions retain customers by identifying churn patterns early.

## 📊 Dataset
- **Features:** Credit Score, Geography, Gender, Age, Tenure, Balance, Products, Card Ownership, Active Status, Salary  
- **Target:** Exited (0 = stayed, 1 = churned)  
- **Rows:** 10,000 customers  

## ⚙️ Approach
- Data preprocessing (encoding categorical variables, scaling numeric features with StandardScaler)  
- Applied classification models: Logistic Regression, Random Forest, XGBoost  
- Used **cross-validation** for robust evaluation  

## 📈 Results
- Logistic Regression: Accuracy = **0.81**, Precision = **0.54**, Recall = **0.19**, F1 = **0.28**  
- Random Forest & XGBoost planned for comparison  

## 🔮 Future Work
- Hyperparameter tuning (GridSearchCV)  
- Try ensemble methods (XGBoost, LightGBM)  
- Model deployment (Streamlit/Flask)

