# Users transations data analysis
### Project overview

This project provides insights into the transactions data of users on a technology platform. The aim is to identify patterns of criminal activity on the platform. With the help of random forest analysis performed on python, I have been able to identify how mant users are impacted by tagging a user as fraudulent or non-fraudulent. Also, with a K-means clustering, I have been able to come up with potential strategies to manage risks among those cohorts and make dat driven recommendations.

### Data sources

Users transation history - the primary dataset used for this analysis is a transactions dataset which is unique at transaction_id level and has multiple attributes describing the nature of the transaction.

### Tools

- SQL - for data quering.
- Python - for data profiling, data cleaning, EDA, K-means clustering, random forest analysis

### Data cleaning/Preparation

In the initial data preparation, I performed the following tasks:
1. Data loading and inspection.
2. Handling missing values and outliers.
3. Data cleaning and formatting.

### Exploratory Data Analysis

EDA included exploring the transactions data to answer key questions, such as:

- How many cases of self-recipient transfers have occured? This cab be often red flags for layering in money laundering.
- What are the trends across high frequency transfer? Users with repeated transactions with very low time difference between transactions can be involved in potential fraud activities.
- Studying the patterns across high transfers sequences. Identifying users making excessive number of requests. There are chances of bot activities which are suspicious.

### Data analysis




