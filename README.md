# OptimalCart Clustering System

> An intelligent customer segmentation system using unsupervised machine learning to discover meaningful customer groups based on purchasing behaviour, engagement, and loyalty indicators.

## 📌 Project Overview

**OptimalCart** is an AI/ML-based customer segmentation project designed for an e-commerce platform serving customers across multiple countries.

The dataset contains **2,240 customer records** and **22 attributes** covering demographics, purchase behaviour, website activity, and customer response.

The objective is to identify meaningful customer segments using **clustering algorithms** and support data-driven marketing, customer engagement, and retention strategies.

## 🎯 Problem Statement

The platform currently uses generic marketing and engagement strategies without clearly understanding different customer behaviour patterns.

This can result in:

- Inefficient marketing
- Missed opportunities to retain high-value customers
- Delayed identification of churn-prone users
- Limited understanding of customer purchasing patterns

OptimalCart addresses this problem using **unsupervised machine learning** to group customers based on similarities in their behaviour.

## 🚀 Objectives

- Analyse historical customer data
- Identify hidden patterns in customer behaviour
- Segment customers into meaningful clusters
- Analyse purchasing behaviour and engagement
- Identify high-value customer groups
- Support personalised marketing strategies
- Support customer retention decisions
- Enable data-driven decision-making

## 📊 Dataset

The dataset contains **2,240 customer records** and **22 attributes**.

Each row represents a customer with information related to demographics, spending, purchase frequency, website activity, recency, and complaints.

### Customer Demographics

| Feature | Description |
|---|---|
| `ID` | Unique customer identifier |
| `Year_Birth` | Year of birth |
| `Education` | Highest education level achieved |
| `Marital_Status` | Marital status |
| `Income` | Yearly household income |
| `Kidhome` | Number of small children |
| `Teenhome` | Number of teenagers |
| `Dt_Customer` | Date when customer enrolled |

### Purchase Behaviour — Amount Spent

| Feature | Description |
|---|---|
| `MntWines` | Amount spent on wine products |
| `MntFruits` | Amount spent on fruits |
| `MntMeatProducts` | Amount spent on meat products |
| `MntFishProducts` | Amount spent on fish products |
| `MntSweetProducts` | Amount spent on sweet products |
| `MntGoldProds` | Amount spent on gold products |

### Purchase Behaviour — Frequency

| Feature | Description |
|---|---|
| `NumDealsPurchases` | Purchases made using discounts |
| `NumWebPurchases` | Purchases made through website |
| `NumCatalogPurchases` | Purchases made through catalog |
| `NumStorePurchases` | Purchases made in physical stores |
| `NumWebVisitsMonth` | Website visits per month |

### Customer Feedback

| Feature | Description |
|---|---|
| `Recency` | Number of days since last purchase |
| `Complain` | Complaint in last 2 years (`1 = Yes`, `0 = No`) |

## 🧠 Machine Learning Approach

OptimalCart uses **unsupervised machine learning** for customer segmentation.


Customer Dataset
       ↓
Data Preprocessing
       ↓
Feature Selection
       ↓
Feature Transformation / Scaling
       ↓
Clustering Algorithm
       ↓
Cluster Evaluation
       ↓
Customer Segmentation
       ↓
Cluster Analysis
       ↓
Business Insights

# 🛠️ Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Jupyter Notebook


# 👨‍💻 Created By

# Abhishek Singh

# ⭐ OptimalCart — Turning customer data into meaningful customer segments.