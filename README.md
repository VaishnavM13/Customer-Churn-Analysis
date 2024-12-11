# Customer-Churn-Analysis
This repository contains a project on Customer Churn Prediction, aimed at identifying customers who are likely to stop using a company's products or services. By leveraging a Decision Tree algorithm, the model achieves an impressive 88% accuracy, enabling businesses to take proactive measures to retain customers and enhance profitability.

Key Objectives:
Understand customer behavior: Analyze patterns and factors contributing to churn.
Predict churn probability: Build a machine learning model to predict churn.
Support decision-making: Provide actionable insights to reduce churn rates.
Tools & Technologies Used
Programming Language: Python
Libraries:
pandas and numpy for data manipulation
matplotlib and seaborn for data visualization
scikit-learn for building and evaluating the machine learning model
Machine Learning Algorithm: Decision Tree Classifier
Dataset
The dataset used in this project includes the following features:

Demographics: Customer ID, age, gender, etc.
Account Information: Subscription type, tenure, monthly charges, total charges, etc.
Behavioral Metrics: Usage patterns, contract type, payment method, and more.
Churn Label: Indicates whether the customer has churned or not (binary classification).
If using a public dataset, include a link (e.g., Telco Customer Churn Dataset).

Methodology
Data Preprocessing:

Cleaned missing or invalid entries.
Performed encoding for categorical variables using one-hot encoding.
Normalized numerical features for better model performance.

Exploratory Data Analysis (EDA):
Visualized the distribution of churn and its correlation with features.
Identified significant predictors such as contract type, monthly charges, and tenure.
Model Building:

Split the dataset into training (80%) and testing (20%) sets.
Built a Decision Tree Classifier to predict churn.
Evaluation:

Used metrics such as Accuracy, Precision, Recall, and F1-score.
Achieved 88% accuracy on the test dataset.
Key Insights
Customers with short tenure and high monthly charges are more likely to churn.
Contract type and payment method play a significant role in determining churn.
Customers on monthly contracts with electronic check payments are at higher risk of churn.
Visualizations
Correlation Heatmap: Showcased relationships between features.
Feature Importance Plot: Highlighted key factors contributing to churn.
Churn Distribution Charts: Provided an overview of churned vs. non-churned customers.
Results
Accuracy: 88%
