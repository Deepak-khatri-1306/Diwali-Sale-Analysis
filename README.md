# Diwali Sales Analysis

## Overview
Diwali is one of the biggest shopping festivals in India, where people buy gifts, clothes, and electronics. This project analyzes Diwali sales data to extract insights into customer purchasing behavior using Python libraries like Pandas, Matplotlib, and Seaborn.

## Data Processing
- Imported necessary libraries: `numpy`, `pandas`, `matplotlib.pyplot`, `seaborn`.
- Read the dataset and handled encoding issues.
- Checked for null values and converted the 'Amount' column to integers.
- Renamed columns for better readability.

## Exploratory Data Analysis (EDA)
### Gender Analysis
- Most buyers are **female**, and they also contribute the most in total spending.
- **Visualizations:**
  - Countplot of gender distribution.
  - Bar chart of total amount spent by gender.

### Age Group Analysis
- Customers aged **26-35 years** have the highest purchasing power.
- **Visualizations:**
  - Countplot of Age Group with hue as Gender.
  - Bar chart of total sales amount by Age Group.

### State-wise Analysis
- Top states with the highest number of orders: **Uttar Pradesh, Maharashtra, Karnataka**.
- **Visualizations:**
  - Bar chart of orders by state (top 10).
  - Bar chart of sales amount by state (top 10).

### Marital Status Analysis
- Married customers contribute higher sales.
- Married women have the highest purchasing power.
- **Visualizations:**
  - Countplot of marital status.
  - Bar chart of sales amount by marital status with gender differentiation.

### Occupation Analysis
- Customers from **IT, Healthcare, and Aviation sectors** tend to spend the most.
- **Visualizations:**
  - Countplot of occupations.
  - Bar chart of sales amount by occupation.

### Product Category Analysis
- **Top categories:** Food, Clothing, and Electronics.
- **Top-selling products:** Identified best-selling Product_IDs.
- **Visualizations:**
  - Countplot of product categories.
  - Bar chart of total sales amount by category.
  - Bar chart of most sold products.

## Conclusion
- **Married women** aged **26-35 years** from **Uttar Pradesh, Maharashtra, and Karnataka**, working in **IT, Healthcare, and Aviation**, are the most likely to make purchases.
- **Food, Clothing, and Electronics** are the top product categories.
