# Bank-Churn-Predictions
 📊 Project Overview

This project aims to predict customer churn for a bank using machine learning techniques. By analyzing customer behavior patterns, the model helps identify customers likely to leave, enabling the bank to take proactive measures to improve customer retention.

🧩 Problem Statement

Banking institutions face significant losses due to customer churn. The objective is to build a model that accurately predicts which customers are likely to churn based on their demographics, account activity, and other relevant features.

🛠️ Tools & Technologies Used

1. Programming Language: Python (NumPy, Pandas, Scikit-Learn, Matplotlib, Seaborn)
2. Modeling: Machine Learning (Logistic Regression, Random Forest, XGBoost)
3. Visualization: Matplotlib, Seaborn
4. IDE: Jupyter Notebook / VSCode

📂 Dataset

The dataset contains information such as Customer ID, Gender, Age, Tenure, Balance, Number of Products, Credit Score, IsActiveMember, and Churn status.

🚀 Project Workflow

1. Data Collection: Loaded the dataset into a Pandas DataFrame.

2. Data Cleaning: Handled missing values and removed duplicates.

3. Exploratory Data Analysis (EDA):

 Visualized customer distribution and churn patterns.

 Analyzed correlations between features using heatmaps.

 Feature Engineering: Created new features and performed scaling.

4. Model Building:

 Trained models including Logistic Regression, Random Forest, and XGBoost.

 Evaluated models using accuracy, precision, recall, and F1-score.

5.Model Evaluation: Selected the best-performing model (Random Forest with 85% accuracy).

6.Insights & Conclusion: Identified key factors such as credit score, number of products, and account activity influencing churn.

📊 Key Insights

Customers with fewer products are more likely to churn.

Inactive customers have a higher churn rate.

Medium credit score range customers showed the highest churn.

📝 Results

Best Model: Random Forest with 85% accuracy.

Recommendation: Focus on engaging inactive customers and offer personalized promotions to reduce churn.
