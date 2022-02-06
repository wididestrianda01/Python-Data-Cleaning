# Python - Data Cleaning
The data cleaning process of Telco Customer Churn Data using Python.

The Telco customer churn data contains information about a fictional telco company that provided home phone and Internet services to 7043 customers in California in Q3. 
It indicates which customers have left, stayed, or signed up for their service. 

## Data Content

Each row represents a customer, each column contains customer’s attributes described on the column Metadata.

The data set includes information about:
* Customers who left within the last month – the column is called Churn
* Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
* Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
* Demographic info about customers – gender, age range, and if they have partners and dependents

## Objective
To obtain the clean data that are ready to be used in Machine Learning.

## Scope
The data cleaning process consists of:
1. Converting the data type to its approriate contextual content
2. Handling Missing Values and Duplicated Rows/Columns
3. Outlier Management
4. Feature Transformation
    - Correcting inconsistent data
    - One-Hot Encoding
    - Ordinal Encoding
    - Scaling
    - Converting numerical type data to categorical data, and used Ordinal Encoding to further simplify the analysis and modelling
