# Superstore-Profit-Prediction-Model
An end-to-end data science project analyzing retail sales data to uncover trends and build a machine learning model (Random Forest) for predicting profitability. Features comprehensive EDA, feature engineering, and actionable business insights.

# Superstore Sales Analytics & Profit Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Library](https://img.shields.io/badge/Library-Scikit--learn-orange)
![ML](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-red)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📖 Overview
This project performs an in-depth analysis of a retail superstore's sales data (2014-2018) to identify key business trends and build a predictive model for profit. The goal was to move beyond descriptive analytics and create a data-driven tool for optimizing pricing, inventory, and regional strategies.

**Key Achievements:**
- Achieved an **R² score of 0.82** using a tuned Random Forest model.
- Identified that discounts over **15%** often lead to losses, especially in the Furniture category.
- Discovered that the **Technology** category drives over **35%** of all profits despite having less than 33% of sales.

## 📊 Dataset
**Source:** [Kaggle Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Records:** ~10,000 sales transactions
- **Timeframe:** 2014 - 2018
- **Features:** `Order Date`, `Ship Date`, `Category`, `Sub-Category`, `Sales`, `Quantity`, `Discount`, `Profit`, `Region`, `Customer Name`, etc.

## 🏗️ Project Architecture
```mermaid
graph LR
A[Raw Data] --> B[Data Preprocessing];
B --> C[Exploratory Data Analysis];
C --> D[Feature Engineering];
D --> E[Model Building & Training];
E --> F[Evaluation & Insights];
F --> G[Business Recommendations];
