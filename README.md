# Internship-task-14---ETL-Mini-Pipeline-Python-Extract-Transform-Load

## Objective
Build an end-to-end ETL pipeline using Python and pandas to simulate real-world analytics workflows.

## ETL Process Overview
## Extract
- Loaded raw retail dataset from Kaggle CSV.
- Stored raw file inside raw/ directory.

## Transform
- Removed duplicate rows.
- Handled missing values.
- Standardized column names (lowercase + underscores).
- Converted datatypes (dates, numeric).
  
Created derived columns:
- margin
- profit_margin_pct
- high_value_flag
  
Split dataset into:
- Customers table
- Products table
- Orders table

## Load
- Exported cleaned CSV files.
- Loaded data into SQLite database (database.sqlite).

## Folder Structure
project/
│
├── raw/
│   └── retail_sales.csv
│
├── processed/
│   ├── customers.csv
│   ├── products.csv
│   ├── orders.csv
│   └── processed_data.csv
│
├── output/
│   └── database.sqlite
│
└── task14_etl.ipynb

## Tools Used
- Python
- pandas
- SQLite
- Google Colab

## Final Outcome
- Built complete ETL workflow
- Practiced data cleaning & transformation
- Created relational tables
- Loaded data into SQLite
- Simulated real analytics engineering task
