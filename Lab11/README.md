# Lab11 - Credit Card Customer Segmentation

This project is a machine learning lab that uses **K-Means Clustering** to segment credit card customers based on their financial behavior.

## Project Overview

The goal of this lab is to group customers into different segments using unsupervised learning.  
The dataset contains credit card customer information such as balance, purchases, payments, credit limit, and cash advance usage.

## Dataset

The dataset used in this project is:

- `CC_GENERAL.csv`

## What the Notebook Includes

- Loading and exploring the credit card customer dataset
- Checking dataset shape, information, and statistics
- Removing the `CUST_ID` column
- Handling missing values
- Visualizing the data
- Scaling the features using `StandardScaler`
- Applying K-Means clustering
- Using the Elbow Method to choose a suitable number of clusters
- Using Silhouette Score to evaluate clustering performance
- Visualizing clusters using PCA
- Analyzing customer segments
