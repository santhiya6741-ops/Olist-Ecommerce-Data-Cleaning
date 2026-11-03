
# Olist E-commerce Data Cleaning and Preprocessing

## Project Overview

This project focuses on cleaning and preprocessing the Olist E-commerce dataset using Python and Pandas.

The objective is to identify data quality issues, investigate inconsistencies, create data quality flags, and prepare datasets for further analysis.

## Tools and Technologies

- Python
- Pandas
- Jupyter Notebook
- VS Code
- CSV

## Datasets

This project covers nine datasets:

1. Customers
2. Orders
3. Order Items
4. Products
5. Reviews
6. Sellers
7. Order Payments
8. Product Category Translation
9. Geolocation

## Data Cleaning Activities

- Missing value analysis
- Duplicate record identification
- Data type and consistency checks
- Date sequence anomaly detection
- Price and freight anomaly detection
- Customer and seller location variation analysis
- Geographical coordinate validation
- Data quality flag creation
- Exporting cleaned datasets to CSV

## Key Findings

| Dataset | Records | Columns |
|---|---:|---:|
| Customers | 99,441 | 8 |
| Orders | 99,441 | 17 |
| Order Items | 112,650 | 10 |
| Products | 32,951 | 12 |
| Reviews | 99,224 | 8 |
| Sellers | 3,095 | 5 |
| Payments | 103,886 | 8 |
| Category Translation | 71 | 3 |
| Geolocation | 1,000,163 | 8 |

## Project Structure

```text
Olist-Ecommerce-Data-Cleaning/
│
├── README.md
├── notebook/
│   └── data_cleaning.ipynb
├── cleaned_data/
│   └── Cleaned CSV files
└── reports/
    └── SWYNEX_Task_1_Data_Cleaning_Report.pdf
```

## Validation

All nine cleaned CSV files were successfully exported and loaded using Pandas.

The original records were preserved, and data quality flags were added to identify potential anomalies.

## Project Outcome

The cleaned datasets are prepared for the next stage: Exploratory Data Analysis (EDA) and business insights generation.

## Internship

This project was completed as part of Task 1 of my Data Analyst internship at SWYNEX.
