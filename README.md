# Customer Shopping Behavior Analysis

## Overview

Customer Shopping Behavior Analysis explores customer purchasing patterns, product preferences, spending behavior, and shopping trends. The project uses Python for data preparation and exploratory data analysis, SQL Server for business queries, and Power BI for interactive visualization.

## Dataset

- **Dataset:** Customer Shopping Behavior
- **Records:** 3,900
- **Columns:** 19
- **Format:** CSV

The dataset includes customer demographics, purchased items and categories, purchase amounts, review ratings, subscription status, shipping type, discounts, previous purchases, and payment methods.

## Tools & Technologies

- **Python:** Data analysis and preprocessing
- **Pandas:** Data manipulation and cleaning
- **Jupyter Notebook:** Python development and analysis
- **SQL Server:** Database storage and SQL analysis
- **Power BI:** Interactive dashboard and visualization
- **Matplotlib and Seaborn:** Data visualization

## Project Workflow

### 1. Data Loading and Exploration

- Loaded the CSV dataset using Pandas.
- Examined the dataset structure, data types, and summary statistics.
- Used exploratory analysis to understand the available customer and purchase information.

### 2. Data Cleaning and Preprocessing

- Checked for missing values.
- Handled missing review ratings using category-wise median imputation.
- Standardized and renamed column names.
- Created age groups.
- Converted purchase-frequency categories into day values.
- Removed a duplicate promotional-code column.

### 3. SQL Server Analysis

Loaded the prepared data into SQL Server and used SQL queries to investigate:

- Revenue by gender.
- Purchases made with discounts compared with the average purchase amount.
- Top-rated products.
- Average purchase amount by shipping type.
- Customer and revenue comparisons by subscription status.
- Product discount usage.
- Customer segmentation into New, Returning, and Loyal groups.
- Most-purchased products within each category.
- Repeat buyers and subscription status.
- Revenue by customer age group.

### 4. Power BI Dashboard

Created an interactive dashboard to explore customer shopping behavior.

![Dashboard.png.png](https://github.com/Tinku679/Tinku679-Customer-Shopping-Behavior-Analysis-/blob/main/Dashboard-Customer%20Shopping.pbix)

**Dashboard highlights:**

- **Total Customers:** 3,900
- **Total Revenue:** $233,081
- **Average Purchase Amount:** $59.76
- **Average Review Rating:** 3.75
- Customer distribution by subscription status.
- Revenue by gender and product category.
- Revenue by age group.
- Top 10 products by revenue.
- Slicers for subscription status, gender, category, shipping type, and payment method.
- Reset button to clear filters.

## Business Recommendations

The analysis can help businesses:

- Understand customer purchasing patterns and preferences.
- Identify products and categories contributing to revenue.
- Compare purchasing behavior across customer groups.
- Review subscription and repeat-purchase patterns.
- Explore differences in spending across age groups.
- Support data-informed marketing and customer-retention decisions.

These are potential uses of the analysis; no measured business impact is claimed.

## Skills Demonstrated

- Data loading, cleaning, and preprocessing
- Exploratory Data Analysis (EDA)
- Python and Pandas
- SQL Server and SQL querying
- Customer segmentation
- Data visualization
- Power BI dashboard development
- Business analysis and insight communication

## Project Files

- `customer_shopping_behavior (1).csv` — Dataset
- `shoping_project .ipynb` — Python analysis and preprocessing
- `SQL server.sql` — SQL queries and analysis
- `Dashboard-Customer Shopping.pbix` — Power BI dashboard
- `images/dashboard.png` — Dashboard screenshot used in this README

## Author

**Shakthi Sharma**

