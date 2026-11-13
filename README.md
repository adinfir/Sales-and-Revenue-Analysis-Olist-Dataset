# Olist E-Commerce — Sales and Revenue Analysis

## Project Overview

This project analyzes sales and revenue performance using the Olist Brazilian E-Commerce dataset. The analysis focuses on identifying monthly revenue trends, understanding product category contributions, and evaluating freight value relative to product revenue.

The goal is to provide business insights that can help stakeholders understand sales performance and identify areas that require further evaluation.

## Business Objectives

This project is divided into three business cases, each addressing a different aspect of sales and revenue performance.

### Business Case 1: Sales Trend Analysis

**Objective:** Evaluate sales performance over time by analyzing monthly revenue and order trends to identify revenue growth patterns, fluctuations, and peak sales periods.

### Business Case 2: Product Category Revenue Analysis

**Objective:** Identify the product categories that contribute the most to total revenue by evaluating category-level revenue performance and their respective contributions.

### Business Case 3: Freight Value Contribution Analysis

**Objective:** Evaluate freight value relative to product revenue across product categories to identify categories with relatively high freight-to-revenue ratios.

## Dataset

The analysis uses the Olist Brazilian E-Commerce Public Dataset, which contains information about orders, products, payments, customers, and sellers.

**Main Tables Used:**
- `orders_dataset`
- `order_items_dataset`
- `products_dataset`
- `product_category_name_translation`

**Data Scope:**
- Only orders with `order_status = 'delivered'` are included in the sales and revenue analysis.
- Product revenue is calculated using `price`.
- `freight_value` is analyzed separately from product revenue.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Tableau

## Analysis Workflow

1. **Import Libraries** — Import the required Python libraries for data manipulation, analysis, and visualization.
2. **Data Gathering** — Load the datasets required for the analysis.
3. **Data Understanding** — Examine dataset structures, dimensions, column names, and data types to understand the information contained in each dataset.
4. **Data Quality Assessment & Cleaning** — Assess data quality by identifying missing values, duplicates, and inconsistencies, then perform the necessary data cleaning.
5. **Data Preparation** — Prepare the datasets for analysis through data transformation, merging, and creation of derived columns where necessary.
6. **Exploratory Data Analysis (EDA)** — Analyze the data to answer the defined business questions using statistical calculations and visualizations.
7. **Key Insights** — Summarize the main findings from each business case.
8. **Business Implications** — Translate the analytical findings into relevant business considerations and potential areas for further evaluation.

## Key Findings

### Business Case 1: Sales Trend Analysis

- November 2017 recorded the highest monthly revenue in the analyzed period, reaching **R$987,765.37** from **7,289 orders**.
- Revenue increased by **52.37%** compared to the previous month.

### Business Case 2: Product Category Revenue Analysis

- `health_beauty` ranked first, generating **R$1,233,131.72**, contributing **9.33%** of total revenue.
- `watches_gifts` ranked second, generating **R$1,166,176.98**, contributing **8.82%** of total revenue.

### Business Case 3: Freight Value Contribution Analysis

- `home_comfort_2` recorded the highest freight-to-revenue ratio at **53.97%**.
- `flowers` ranked second, with a ratio of **44.04%**.

## Dashboard Preview

The interactive Tableau dashboard provides a visual overview of the sales and revenue analysis, including monthly revenue trends, product category performance, and freight value contribution.

### Interactive Dashboard

**[View Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/adin4572/viz/DashboardSalesandRevenueAnalysis/Dashboard1)**

### Dashboard Screenshot

![Sales & Revenue Dashboard](Dashboard Sales and Revenue Analysis/Dashboard Sales and Revenue Analysis.png)

## Business Implications

Based on the analysis, several business considerations can be identified:

- **Sales Performance Monitoring:** Monitor monthly revenue and order trends to understand changes in sales performance and identify periods of significant growth or decline.
- **Product Category Evaluation:** Assess the revenue contribution of top-performing categories to better understand the company's key revenue sources.
- **Freight Value Evaluation:** Review categories with relatively high freight-to-revenue ratios to identify potential areas for logistics cost evaluation.

These findings provide an overview of sales performance and can serve as a starting point for further business evaluation.

## Repository Structure

```text
Olist-Sales-Revenue/
├── README.md
├── Sales & Revenue.ipynb
└── Dashboard Sales and Revenue Analysis/
    └── Dashboard Sales and Revenue Analysis.png
```

## Conclusion

This analysis provides an overview of Olist's sales and revenue performance through monthly trends, product category contributions, and freight value comparisons.

The findings highlight the importance of monitoring sales performance, understanding product category contributions, and evaluating freight value relative to product revenue.

## Project Category

**Data Analysis | E-Commerce | Sales & Revenue Analysis**

**Dataset:** Olist Brazilian E-Commerce Public Dataset
