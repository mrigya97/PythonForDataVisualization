Telco Customer Churn Visualization
Description
This project provides an in-depth analysis and visualization of the Telco Customer Churn dataset. The dataset includes customer information such as demographics, services, and account details, aimed at understanding customer churn patterns and predicting factors influencing customer attrition.

Dataset
The dataset used in this project is available here:- https://www.kaggle.com/datasets/blastchar/telco-customer-churn

Project Overview
The project involves various steps to explore, analyze, and visualize the dataset to gain insights into customer churn. Below is a summary of the steps performed:

1. Data Exploration
Histograms and Box Plots: Visualized the distribution of numerical features such as age, tenure, and monthly charges using matplotlib and seaborn.

Correlation Heatmap: Created a heatmap to show correlations between numerical features like tenure and monthly charges.

2. Churn Analysis

Churn Rate Overview: Visualized the proportion of churned vs. retained customers using pie charts and bar graphs.

Service Usage Patterns: Compared service usage between churned and retained customers using bar charts.

3. Feature Importance

Feature Impact: Analyzed the importance of features such as contract type, payment method, and tenure on churn using bar plots and models like Random Forest or Logistic Regression.

Tenure vs. Monthly Charges Analysis: Illustrated how average monthly charges vary with customer tenure using line charts.

4. Behavioural Patterns
   
Heatmap of Service Combinations: Visualized patterns in service usage (e.g., phone, internet, and streaming services) between churned and non-churned customers.

Segment Analysis: Applied clustering techniques (e.g., K-means) to segment customers and visualize churn tendencies.

5. Predictive Insights

Decision Tree Visualization: Used a decision tree to show rules predicting customer churn.

Partial Dependency Plots: Illustrated the effect of specific features on churn likelihood.

Steps used Create Tenure and Service Usage Categories

Tenure Groups

Define Tenure Categories:

New Customer: 0–12 months
Mid-term Customer: 13–36 months
Loyal Customer: 37+ months

Service Usage Categories

Identify Relevant Features:

Features like InternetService, OnlineSecurity, TechSupport, OnlineBackup, and DeviceProtection.

Define Categories:

Basic Service: No internet service or limited additional services.

Standard Service: Internet service with limited add-ons.

Premium Service: Comprehensive services including multiple add-ons.
