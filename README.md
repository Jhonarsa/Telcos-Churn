Customer Churn Prediction – Telecom Industry

This project aims to predict customer churn in the telecom sector using data science and machine learning techniques. The analysis provides actionable insights to improve customer experience, reduce churn, and support retention strategies.

📂 Project Structure

├── 01-Project Management/    # Brief Project   
├── 02-Data/                  # Raw datasets   
├── 03-Script/                # Jupyter Notebooks with analysis and modeling
├── 04-Report/                # Final reports and visualizations  
└── README.md                 # Project documentation  

⚙️ Methodology

Exploratory Data Analysis (EDA):

Customer demographics and usage behavior.

Net Promoter Score (NPS) and Contact Index.

Revenue-related variables.

Feature Engineering:

Handling missing values.

WoE encoding for categorical variables.

Balancing target variable using SMOTE.

Modeling:

Supervised models: Logistic Regression, Random Forest, Balanced Random Forest, XGBoost, Decision Tree.

Unsupervised models: Isolation Forest, One-Class SVM.

Model comparison based on precision, recall, F1-score.

Results:

Logistic Regression showed the best recall (74%) for the minority class (churn).

Key drivers: tenure, data usage, NPS, cancellation requests.

Business Strategy:

Proactive segmentation of at-risk customers.

Personalized retention campaigns.

Monitoring and continuous improvement of the model.

📊 Key Insights

Customers with shorter tenure are more likely to churn.

Cancellation-related contacts have the highest churn rate.

NPS and Contact Index show strong relationship with churn.

Predictive modeling helps prioritize customers for retention campaigns.

🛠️ Technologies Used

Python (pandas, numpy, scikit-learn, xgboost, imbalanced-learn)

Jupyter Notebook

Matplotlib / Seaborn (visualizations)

Git & GitHub

📑 Report

A detailed report with methodology, findings, and recommendations is included in the 04-Report/ folder.
