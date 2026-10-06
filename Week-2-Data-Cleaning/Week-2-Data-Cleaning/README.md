# Week 2 – Data Cleaning and Pre-Processing

## Objective

The objective of Week 2 is to identify, investigate, and resolve
data-quality issues in the Online Retail dataset and prepare a
clean, analysis-ready dataset for further analytics and modeling.

## Dataset

The Online Retail dataset used in Week 1 is continued for this task.

The dataset contains transaction-level information including:

- Invoice Number
- Stock Code
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

## Data Cleaning Activities

The following data-quality issues are being investigated and handled:

- Missing values
- Duplicate records
- Cancelled transactions
- Invalid quantities
- Invalid unit prices
- Missing customer identifiers
- Inconsistent product descriptions
- Potential numerical outliers

## Pre-Processing

The following transformations are being applied:

- Conversion of InvoiceDate to datetime format
- Standardization of product descriptions
- Creation of Revenue
- Creation of Year, Month and MonthName
- Creation of Day and DayOfWeek
- Creation of Hour
- Creation of IsWeekend
- Preparation of a customer-analysis dataset

## Outlier Treatment

Potential quantity outliers are identified using the
Interquartile Range (IQR) method.

Extreme values are not automatically removed because unusually
large quantities may represent legitimate bulk purchases.

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Status

🚧 In Progress

The notebook, cleaned dataset, visualizations and final report
will be added after completion of the Week 2 analysis.

## Author

Gupteswara Sahu

B.Tech CSE (AI & ML)

Marwadi University
