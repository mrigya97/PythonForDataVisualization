Project Summary: N26 KYC Challenge Data Visualization

This project focuses on the analysis and visualization of the N26 KYC Challenge dataset, employing various data preprocessing and analysis techniques to extract meaningful insights. Below is a summary of the key steps undertaken:

1. Data Preprocessing and Cleaning

Data Filtering and KYC Verification: Utilized .loc[] to filter users based on KYC status from specific countries (e.g., GB, FR).

Data Cleanup and Index Reset: Applied reset_index() after filtering for failed transactions to maintain a clean DataFrame structure.

String Manipulation: Cleaned string fields, such as merchant categories and document properties, using lstrip() and rstrip().

Data Type Conversion: Converted the iso_code column in currency.csv to a string format using .astype().

Data Extraction and Column Creation: Employed json_normalize to extract and create individual columns for gender, nationality, document type, issuing country, and date of expiry from nested fields in doc_reports.csv.

2. Data Analysis and Visualization

Facial Similarity Reports: Filtered facial comparison results to analyze trends in non-clear outcomes based on timestamps.

Document Verification: Created bar charts to visualize discrepancies in document verification results.

Transaction Status Analysis: Used go.Bar() to compare completed and declined transactions.

KYC Distribution Visualization: Visualized the pass/fail distribution of KYC users using pie charts.

Currency Exchange and Transaction Summary Tables: Created tables to summarize top exchange rates and failed transaction rates by country.

Histogram Analysis: Analyzed the distribution of successful transaction amounts and user age.

Line Chart Visualization: Tracked transaction volume and exchange rate fluctuations over time.

Scatter Plot Analysis: Illustrated the relationship between transaction amounts and merchant countries, differentiating by transaction status.

3. Advanced Data Exploration

Fraud Detection: Merged fraudsters.csv with user and transaction data to analyze fraudulent patterns.

Simulation of Fraudster Activity: Generated randomized trends over time to simulate fraudster activity.

Conclusion

This project successfully utilized a variety of data manipulation and visualization techniques to analyze KYC processes and transaction behaviors, leading to valuable insights regarding user verification and transaction trends. The interactive visualizations created through plotly enhance the understanding of the dataset, providing stakeholders with crucial information for decision-making.

Dataset Link

Access the N26 KYC Challenge dataset on Kaggle: https://www.kaggle.com/datasets/zywald/n26-kyc-challenge

