# Diwali Sales Analysis

## Overview
Diwali is one of the biggest shopping festivals in India, where people buy gifts, clothes, and electronics. This project analyzes Diwali sales data to extract insights into customer purchasing behavior using Python libraries like Pandas, Matplotlib, and Seaborn.

## Problem Statement
Understanding consumer purchasing behavior during Diwali is crucial for businesses to optimize their marketing strategies and product offerings. This analysis aims to identify key trends in customer demographics, purchasing patterns, and high-performing product categories to help businesses make data-driven decisions.

## Identifying the Data
The dataset includes:
- Customer demographics (Gender, Age Group, Marital Status, Occupation, State)
- Product details (Category, Product_ID)
- Purchase details (Amount spent, Number of orders)

## Data Exploration and Cleaning
1. Imported necessary libraries: numpy, pandas, matplotlib.pyplot, seaborn.
2. Read the dataset and handled encoding issues.
3. Checked for null values and converted the 'Amount' column to integers.
4. Renamed columns for better readability.

## Exploratory Data Analysis (EDA)

### Gender Analysis
- Most buyers are female, and they also contribute the most in total spending.
- **Visualizations:**
  - Countplot of gender distribution.
  - Bar chart of total amount spent by gender.

### Age Group Analysis
- Customers aged 26-35 years have the highest purchasing power.
- **Visualizations:**
  - Countplot of Age Group with hue as Gender.
  - Bar chart of total sales amount by Age Group.

### State-wise Analysis
- Top states with the highest number of orders: Uttar Pradesh, Maharashtra, Karnataka.
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
- Customers from IT, Healthcare, and Aviation sectors tend to spend the most.
- **Visualizations:**
  - Countplot of occupations.
  - Bar chart of sales amount by occupation.

### Product Category Analysis
- Top categories: Food, Clothing, and Electronics.
- Top-selling products: Identified best-selling Product_IDs.
- **Visualizations:**
  - Countplot of product categories.
  - Bar chart of total sales amount by category.
  - Bar chart of most sold products.

## Useful Insights
- Married women aged 26-35 years from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation, are the most likely to make purchases.
- Food, Clothing, and Electronics are the top product categories.
- Businesses should focus on targeted marketing for these demographics to maximize sales.

## Data Presentation and Visualization
The analyzed data is presented through:
1. **Reports** - Summarizing key findings and trends.
2. **Dashboards** - Interactive visuals including:
   - Gender and Age Group spending trends.
   - State-wise order and revenue distribution.
   - Occupation-based spending insights.
   - Top product categories and best-selling items.

By leveraging these insights, businesses can refine their sales strategies and marketing efforts for better customer engagement and revenue growth.

