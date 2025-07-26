🏦 SBI Bank Customer Churn Prediction


    Can a machine predict when a customer is about to leave a bank?
    This project is a complete machine learning pipeline built to predict customer churn for SBI Bank — turning customer data into proactive retention strategies.

📌 Project Overview

Customer churn is one of the biggest challenges for banks.
In this project, we use machine learning to analyze customer behavior and predict which clients are most likely to leave SBI Bank.

This notebook includes:

    🧼 Data cleaning & preprocessing

    📊 Exploratory Data Analysis (EDA)

    🧠 Model building: Logistic Regression, Random Forest, etc.

    ⚖️ Handling class imbalance using SMOTE

    📈 Evaluation using F1 Score, Confusion Matrix, and more

📁 Dataset

The dataset includes features such as:

    CreditScore, Age, Balance, Geography, Gender

    Tenure, NumOfProducts, HasCrCard, IsActiveMember

    EstimatedSalary, and the target: Exited

    📌 Target variable: Exited (1 = churned, 0 = retained)

🔧 Technologies Used
Category	Tools & Libraries
Language	Python 3.8+
Analysis & EDA	Pandas, NumPy, Matplotlib, Seaborn
Modeling	scikit-learn, LogisticRegression, RandomForestClassifier, SMOTE
Notebook	Jupyter Notebook
🚀 Workflow

    Data Loading

    Data Cleaning

    Encoding Categorical Features

    Feature Scaling

    Exploratory Data Analysis

    Model Building & Comparison

    Model Evaluation

    Churn Insights

📈 Model Evaluation Metrics

    ✅ Accuracy

    🧠 Precision, Recall, F1-Score

    🔍 Confusion Matrix

    ⚖️ ROC-AUC (if applicable)

    📉 Class imbalance handling with SMOTE

🔍 Sample Visuals


    Distribution of churned vs retained customers


    Feature importance chart from Random Forest

💡 Business Impact

By predicting churn, SBI can:

    🎯 Retain high-value customers

    📉 Reduce marketing costs

    🔁 Improve customer lifetime value

✅ Future Improvements

    Integrate a web dashboard with Streamlit or Dash

    Hyperparameter tuning with GridSearchCV

    Deploy model using Flask + Heroku

📄 License

This project is licensed under the MIT License. Feel free to use, modify, and share it.

