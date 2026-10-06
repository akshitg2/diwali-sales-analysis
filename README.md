# Diwali Sales Analysis

## Project Overview

A Python-based exploratory data analysis project using Diwali sales data to understand customer purchasing patterns, sales performance, and product trends.

The analysis examines customer demographics, geographic distribution, occupations, product categories, and order behavior to identify patterns in purchasing activity.

## Objective

To analyze Diwali sales data and identify customer and product-level patterns that can help understand purchasing behavior and sales performance.

## Dataset

The dataset contains **11,251 records** with customer, geographic, occupation, product, order, and sales information.

Key fields include:

- Customer ID
- Product ID
- Gender
- Age Group
- Age
- Marital Status
- State
- Zone
- Occupation
- Product Category
- Orders
- Amount

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Exploratory Data Analysis (EDA)

## Data Cleaning

The analysis included:

- Removing unnecessary columns
- Checking for missing values
- Removing records with missing sales amounts
- Converting the `Amount` column to integer type
- Verifying the cleaned dataset before analysis

The original dataset contained 12 missing values in the `Amount` column, which were removed during preprocessing.

## Analysis Performed

### Customer Demographics

- Gender-wise customer distribution
- Age-group analysis
- Marital-status analysis
- Gender-wise purchasing behavior

### Geographic Analysis

- State-wise order analysis
- State-wise sales analysis
- Identification of states with the highest order activity

### Occupation Analysis

- Customer distribution by occupation
- Sales contribution by occupation

### Product Analysis

- Product-category distribution
- Sales by product category
- Product-level order analysis

## Key Insights

- Female customers generated higher sales than male customers in the analyzed dataset.
- The **26–35 age group** represented the largest sales contribution.
- **Uttar Pradesh, Maharashtra, and Karnataka** were among the leading states by order activity.
- Customers working in **IT, Healthcare, and Aviation** were among the prominent purchasing groups.
- **Food, Clothing, and Electronics** were among the major product categories identified in the analysis.
- The analysis indicates stronger purchasing activity among certain demographic and occupational groups.

## Visualizations

The analysis uses Seaborn and Matplotlib to visualize:

- Gender distribution
- Age-group distribution
- State-wise orders and sales
- Marital-status distribution
- Occupation-wise sales
- Product-category sales
- Product-level order activity

## Conclusion

The analysis provides an overview of customer purchasing behavior during Diwali sales, highlighting patterns across demographics, geography, occupations, and product categories.
