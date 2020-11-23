# Sprint2_CreditCardFraudDetection
EDA Databricks Notebook Files regarding the Credit Card Fraud Detection Project for Eskwelabs' Sprint 2. We were tasked to develop a machine learning algorithm which could detect if a given transaction could be considered a fraudulent transaction or not.

# CreditCardFraud-ProjectDataset_EDA.dbc
This Databricks Notebook contains some of the Exploratory Data Analysis (EDA) our team did during the Credit Card Fraud Detection Project.
We were able to extract and work with information such as various datetime columns, merchant distance, city locations, shopping categories,age groups, etc.

## EDA Plots:
A.) Total Number of Fraud Transactions Per Hr

B.) Average $ Amount of Fraud Transactions per Hr

C.) Average $ Amount of Fraud Transactions per Quarter

D.) # of Fraud Transactions per Age

E.) # of Fraud Transactions per Category

F.) Average $ Amount of Fraud Transactions per Category

G.) # of Fraud Transactions per Merchant

H.) Average $ Amount per Fraud Transaction per Merchant

I.) Distribution of Fraud Incidence based on Merchant Distance

J.) Distribution of Fraud Incidence based on State (Count and $ Amount)

# CreditCardFraud_XGBoostForProject.dbc

This Databricks Notebook contains our team's attempt to predict Credit Card Fraud using the XG Boost Algorithm. We tried using three different random seeds when doing the train-test split of the data. (42,75,99) We were able to get accuracy scores between 92-94% from using the XG Boost Algorithm.
