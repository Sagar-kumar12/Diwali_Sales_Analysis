# Customer-Churn-Analysis-Using-Python

**Project Overview**
This project focuses on analyzing customer behavior and building a predictive model to identify customers who are likely to churn. By using exploratory data analysis (EDA), feature engineering, and machine learning, the goal is to help businesses take proactive steps in customer retention.

**Objectives**

Perform exploratory data analysis (EDA) to uncover churn patterns.
Engineer relevant features for better model performance.
Build and evaluate classification models to predict customer churn.
Visualize important churn indicators and actionable insights.

**Tools & Technologies**

Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
Jupyter Notebook
Machine Learning Models: Logistic Regression, Random Forest, Decision Tree

**Key Features**

Data Cleaning & Preprocessing: Handled missing values, encoded categorical variables, and normalized data.
EDA: Visualized relationships between churn and key variables like contract type, tenure, and monthly charges.
Model Building: Trained and compared multiple ML models using accuracy, precision, recall, F1-score, and ROC-AUC.
Feature Importance: Identified top factors influencing churn using model-based and permutation importance.
Confusion Matrix & ROC Curve: Evaluated model performance visually.

**Dataset**
Source: Telco Customer Churn Dataset (Kaggle)
Size: ~7,000 customer records

**Fields Used:**

Customer ID, Gender, Senior Citizen, Partner, Dependents
Tenure, Contract Type, Payment Method, Monthly Charges
Internet Service, Online Security, Tech Support, Churn

**Insights Gained**

Customers with month-to-month contracts and high monthly charges are more likely to churn.
Lack of services like online security and tech support correlate with higher churn rates.
Long-tenured customers show higher retention and satisfaction.

**How to Run the Project**

Clone this repository.
Install the required libraries:
pip install pandas numpy scikit-learn seaborn matplotlib
Open Customer_Churn_Analysis.ipynb in Jupyter Notebook.
Run each cell step-by-step to explore the data and model output.

**Future Enhancements**

Implement XGBoost or LightGBM for improved accuracy.
Deploy the model using Flask or Streamlit for business use.
Integrate with real-time customer data APIs for live churn scoring.

