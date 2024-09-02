# Walmart Customer Purchase Behavior Analysis

## Project Overview

This project focuses on analyzing customer purchase behavior at Walmart to provide actionable insights that can inform business decisions and marketing strategies. The analysis delves into various aspects such as spending patterns based on gender, age, occupation, city category, and more.

## Problem Statement

Walmart Inc. seeks to analyze customer purchase behavior with a focus on spending patterns influenced by factors such as gender, age, occupation, and city category. The insights derived from this analysis will help Walmart make informed business decisions and tailor marketing strategies to different customer segments.

## Tools

- **Jupyter Notebook** (for Python)
- **Python Libraries**

## Steps Involved

### 1. Data Collection
- **Dataset:** The analysis uses a dataset containing 550,068 rows and 10 columns, including information on User ID, Product ID, Gender, Age, Occupation, City Category, Stay in Current City Years, Marital Status, Product Category, and Purchase amounts.

### 2. Data Preprocessing
- **Handling Missing Values:** Checked and confirmed that there are no missing values in the dataset.
- **Data Type Conversion:** Ensured that all columns have the appropriate data types, such as integers for User ID and Purchase, and objects (strings) for categorical variables like Product ID and Gender.
- **Data Cleaning:** Verified data integrity and ensured that categorical values are properly encoded.

### 3. Exploratory Data Analysis (EDA)
- **Data Summary:** Generated summaries of data, including the distribution of customers by gender, age, occupation, and city category.
- **Non-Graphical Analysis:** Computed value counts and percentages for categorical variables like Marital Status and Product Category.
- **Visual Analysis:** Created various plots including count plots, box plots, and histograms to visualize distributions and relationships between variables.

### 4. Data Transformation
- **Categorical Analysis:** Analyzed categorical data such as city categories, gender, and marital status in relation to purchase behavior.
- **Statistical Properties:** Calculated means, standard deviations, and confidence intervals for different customer segments to understand purchasing behavior.

### 5. Visualization
- **Count Plots:** Created count plots for categorical variables such as Gender, Age, Occupation, and City Category to visualize customer demographics.
- **Box Plots:** Used box plots to identify outliers and understand the distribution of purchase amounts across different categories.
- **Histograms:** Generated histograms to analyze the distribution of purchase amounts and identify patterns in spending behavior.

### 6. Business Insights
- **Customer Demographics:** Identified that 59% of customers are single and 75% are male, with 80% of users aged between 18-50.
- **Product Popularity:** Found that categories 1, 5, and 8 are the top-performing product categories.
- **City Analysis:** Customers from City B (42%) are the most active shoppers, followed by those from City C (31%) and City A (27%).
- **Spending Patterns:** Observed that males spend more than females and that customers aged 26-35 are the most significant contributors to Walmart's sales.

### 7. Recommendations
- **Target Married Customers:** Since unmarried customers spend more, consider offering discounts to married customers to boost their spending.
- **Focus on Female Customers:** Implement strategies to increase sales among female customers, such as targeted advertising or discounts.
- **Retain Younger Customers:** Retain customers aged 18-25 by offering incentives, while also finding ways to engage other age groups.
- **City-Specific Strategies:** Focus on retaining customers in City C while developing new strategies to increase sales in City B and City A, possibly through targeted online advertising.
- **Diversify Product Focus:** While categories 1, 5, and 8 are popular, consider promoting other product categories to balance sales across the board.

## Conclusion

The insights derived from this analysis provide Walmart with valuable recommendations to optimize marketing strategies, enhance customer engagement, and increase sales across different customer segments.
