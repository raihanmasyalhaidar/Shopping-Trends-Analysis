<div align="center">

# Shopping Trends Analysis and Exploratory Data Analysis

</div>

<div align="justify">

![image](https://github.com/user-attachments/assets/ad98e0da-dbe7-464c-8c93-9f84e7a11fda)


## Overview
As online shopping continues to evolve, understanding shopping patterns and consumer preferences has become crucial for e-commerce businesses. This project aims to uncover insights from a dataset that captures various aspects of consumer behavior, product preferences, and sales trends. By conducting Exploratory Data Analysis (EDA), we aim to provide actionable insights that can help businesses optimize their strategies and improve overall performance.

This project is implemented in Python, using Jupyter Notebook as the primary environment for coding, visualization, and documentation. The analysis focuses on identifying shopping trends, consumer preferences, and the impact of various factors such as promotions, payment methods, and discounts.

## Objectives
#### 1. Understanding Customer Demographics and Preferences:
* Analyze how customer gender, location, and subscription status influence shopping behavior.
#### 2. Identifying Product and Category Trends:
* Determine the most popular items and categories across seasons, sizes, and colors.
#### 3. Evaluating the Impact of Discounts and Promotions:
* Assess how discounts and promo codes influence purchase behavior and sales performance.
#### 4. Analyzing Payment and Shipping Trends:
* Identify customer preferences for payment methods and shipping types, and their effect on overall sales.
#### 5. Customer Retention Insights:
* Investigate the relationship between subscription status, purchase frequency, and customer loyalty.

</div>

<div align="justify">

## Dataset
The data used is sourced from: 

<div align="center">

https://www.kaggle.com/datasets/bhadramohit/customer-shopping-latest-trends-dataset/data?select=shopping_trends.csv

</div>

The dataset offers a comprehensive view of consumer shopping trends, aiming to uncover patterns and behaviors in retail purchasing. It contains detailed transactional data across various product categories, customer demographics, and purchase channels.

## Methodology

#### 1. Data Import and Cleaning
* Load the dataset into a Pandas DataFrame.
* Clean and preprocess the data by handling missing values, outliers, and inconsistent formatting.

#### 2. Exploratory Data Analysis (EDA)
* Demographics Analysis: Analyze customer demographics such as gender, location, and subscription status.
* Product Insights: Visualize trends in items purchased, categories, sizes, and colors.
* Seasonal Trends: Identify how seasons impact product demand and sales.
* Payment & Shipping Analysis: Investigate customer preferences for payment methods and shipping types.
* Promotions & Discounts: Explore the role of discounts and promo codes in driving sales

#### 3. Visualization and Insights
* Use visualizations such as bar charts, pie charts, line plots, heatmaps, and scatter plots to highlight key findings.

#### 4. Machine Learning Modelling
* Build a good model based on the accuracy obtained from the modeling, so it can be used to predict shopping trends based on subscription status in the future
* The modeling algorithms used are: Random Forest, Logistic Regression, SVM (Support Vector Machine), KNN (K-Nearest Neighbors)

#### 5. Recommendations
* Provide actionable suggestions based on the analysis, such as: optimizing inventory based on seasonal demand, offering targeted promotions to customer segments, and improving shipping and payment options to align with customer preferences

#### 6. Tools Used
* Programming Language : Python
* Libraries : Pandas, Numpy, Matplotlib, Seaborn, Sklearn

#### 7. Summary 
Based on the data analysis, the prediction of Subscription Status (Yes/No) was performed using four models, with Logistic Regression showing the highest accuracy (86.41%), followed by Random Forest (84.10%). The most influential features on customers' decision to subscribe are Discount Applied and Promo Code Used, followed by Purchase Amount and Previous Purchases. Promotional factors and purchasing patterns proved to be more significant than other features such as product category or season. For the business strategy, focusing on incentives like discounts and promo codes, as well as targeting customers with previous purchase history or high transaction values, can increase subscription rates. Logistic Regression is recommended for practical prediction, while Random Forest is suitable for in-depth analysis of feature importance. This strategy is expected to effectively drive customer subscription decisions.

#### 8. Strategic Recomendation
Based on the analysis, the business steps that can be taken include optimizing promotions by offering attractive discounts and promo codes to encourage customers to subscribe, and focusing on customers who have made previous purchases as they have a higher potential for subscription. Additionally, target high transaction value customers, as they have a higher likelihood of subscribing, while ignoring less significant features such as category, size, and season. The optimal strategy involves using Machine Learning, with Logistic Regression for practical prediction and Random Forest for interpreting feature importance. Customer segmentation based on purchase history and discount usage can help design specific campaigns offering immediate benefits to boost subscriptions.
