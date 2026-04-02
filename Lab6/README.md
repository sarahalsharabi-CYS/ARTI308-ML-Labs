# Ecommerce Customers – Linear Regression Lab

## Project Overview

This lab applies **Linear Regression** to analyze customer behavior in an e-commerce company and predict the **Yearly Amount Spent** by customers.

The main objective of this project is to understand which customer features have the strongest impact on spending and to build a predictive model using machine learning techniques in Python.

## Dataset Description

The dataset used in this project is called **Ecommerce Customers**.
It contains information about customer activity and spending behavior on an e-commerce platform.

### Features in the dataset:

* **Email** – Customer email address
* **Address** – Customer address
* **Avg. Session Length** – Average time spent per session
* **Time on App** – Time spent on the mobile application
* **Time on Website** – Time spent on the website
* **Length of Membership** – Number of years the customer has been a member
* **Yearly Amount Spent** – Total yearly spending by the customer (Target variable)

## Lab Steps

The following steps were performed in this lab:

1. Import required Python libraries (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
2. Load and explore the dataset
3. Check for missing values and duplicate records
4. Perform Exploratory Data Analysis (EDA) using visualizations
5. Define feature variables (X) and target variable (y)
6. Split the dataset into training and testing sets
7. Train a Linear Regression model
8. Make predictions using the trained model
9. Evaluate model performance using:

   * Mean Absolute Error (MAE)
   * Mean Squared Error (MSE)
   * Root Mean Squared Error (RMSE)
10. Interpret the model coefficients

## Model Objective

The goal of the model is to predict:

**Yearly Amount Spent**

based on the following features:

* Avg. Session Length
* Time on App
* Time on Website
* Length of Membership

## Key Findings

The analysis showed that:

* **Length of Membership** has the strongest positive impact on customer spending
* Customers who stay longer with the company tend to spend more money
* **Time on App** also has a significant effect on spending
* **Time on Website** has a weaker relationship compared to the mobile application

These findings suggest that improving customer retention and enhancing the mobile app experience may increase revenue.

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

