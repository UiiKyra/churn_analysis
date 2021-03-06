# Churn Analysis
- Analyzed Customer Churn Using Survival Curve and Interpretable Machine Learning Model
- Tools: Python, Scikit-Learn, Random Forest, H2O autoML, LIME

**Code** is available [here](https://github.com/UiiKyra/churn_analysis/blob/master/Churn_Analysis.ipynb). **Slides** are available [here](https://github.com/UiiKyra/churn_analysis/blob/master/Churn%20analysis.pdf).

# Introduction
Customer churn happens when customers stop doing business with the company. It's very important to understand why customers churn and implement incentive promotion plans to those high risk customers. Because getting new customers is way more expensive than earning the trust and loyalty of existing customers.

In this project, I took the sample dataset from a telecommunication company and applied survival analysis and interpretable machine learning models to analyze the churn problem.


# Dataset
The data was downloaded from IBM Sample Data Sets for customer retention programs. Available in [here](https://www.kaggle.com/blastchar/telco-customer-churn).

Each row represents a customer, each column contains customer’s attributes described on the column Metadata.
The data set includes information about:
 - Customers who left within the last month – the column is called Churn
 - Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
 - Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
 - Demographic info about customers – gender, age range, and if they have partners and dependents
