# Zaalima-Development---Data-Analytics-Project
## Project Overview
This project focuses on performing data analysis on a retail sales dataset.
The objective is to clean the data, analyze sales trends, and design a Star Schema
for analytical reporting and decision-making.
## Dataset
- Source: Kaggle (Superstore Sales Dataset)
- Total Records: 9,800
- Total Columns: 18
## Tools & Technologies
- Python (Pandas, Matplotlib)
- VS Code
- Jupyter Notebook
- MySQL Workbench
- Git & GitHub
## Data Cleaning & Preprocessing
- Handled missing values in the Postal Code column.
- Converted Order Date and Ship Date to datetime format.
- Created Order Year and Order Month for time-based analysis.
- Ensured no missing values after preprocessing.
## Data Analysis
- Year-wise sales analysis
- Month-wise sales trend analysis
- Region-wise sales performance
- Category-wise sales distribution
## Schema Design (Star Schema)
A Star Schema was designed based on the analysis.

### Fact Table
- Fact_Sales (Sales, Date Key, Product Key, Customer Key, Geography Key)

### Dimension Tables
- Dim_Date
- Dim_Customer
- Dim_Product
- Dim_Geography
## Project Structure
├── data/
├── notebooks/
├── schema/
├── README.md
## Contributor
Jasima Jasmine – Data Analytics Intern

