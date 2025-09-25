🏦 Banking Customer Churn Prediction

This project predicts customer churn (exit) for a retail bank using machine learning models like Logistic Regression, Random Forest, and XGBoost. The aim is not only to build accurate models but also to generate business insights that can help reduce customer attrition.

📊 Dataset Information

Size: 10,000 customers

Target variable: Exited (1 = Churned, 0 = Retained)

Important features:

Customer demographics (Age, Gender, Geography)

Banking behavior (Credit Score, Balance, Products, Activity)

Financial status (Estimated Salary, Has Credit Card)

⚙️ Approach

Exploratory Data Analysis (EDA)

Churn rate: ~20% customers exited (class imbalance)

Age, Balance, and Activity were highly correlated with churn.

Preprocessing

One-hot encoding for categorical features (Geography, Gender).

StandardScaler for numeric features.

Class imbalance checked.

Modeling

Logistic Regression

Random Forest

XGBoost (best performing)

Cross-validation for model robustness.

Evaluation Metrics

Accuracy: 85%

Precision: 65%

Recall: 49%

F1 Score: 0.56

ROC-AUC: 0.84

📈 Results

XGBoost outperformed other models with higher balance of precision & recall.

Feature importance showed:

Age, Balance, and Active Member status are the top drivers of churn.

Business Insight:

Younger customers with higher balances and lower activity are most likely to churn.

🚀 Business Value

Customer Segmentation: Model identifies high-risk customers (probability > 60%).

Actionable Insight: Banks can target at-risk customers with retention campaigns (loyalty offers, better service, discounts).

Deployment Potential: Model can be integrated into a dashboard or API to give churn probability in real-time for each customer.

🔮 Future Work

Hyperparameter tuning (GridSearchCV).

Try Gradient Boosting / Neural Networks.

Deploy on Streamlit or Flask for interactive use.

Integrate SHAP values for model interpretability.
