# Walmart_data_cleaning
This project contains the step-wise data cleaning of Walmart sales data using python 
## Data Cleaning Project using Python

This repository contains a data cleaning project completed using Python. The goal of this project is to preprocess raw data into a clean, structured format that is ready for analysis and modeling.

## Project Overview

# Raw data often contains inconsistencies, missing values, and formatting issues. This project demonstrates how to:
- Load and explore a dataset
- Identify and handle missing or duplicate data
- Correct inconsistent formatting
- Convert data types
- Standardize column names and values
- Save the cleaned dataset for future use

## Technologies Used
- Python
- Pandas for data manipulation
- NumPy for numerical operations
- Jupyter Notebook or `.py` script for implementation

## Files in This Repository

- `walmart_data_cleaning.ipynb` – Main notebook with data cleaning steps
- `Walmart.csv` – Input raw dataset *(you may include a sample or anonymized version)*
- `cleaned_data.csv` – Output cleaned dataset
- `README.md` – Project documentation

## Cleaning Steps Performed

- Loaded data using `pandas.read_csv()`
- Checked for null values and handled them using imputation or deletion
- Removed duplicate rows
- Fixed inconsistent casing and spacing in text columns
- Converted data types (e.g., strings to dates or integers)
- Renamed columns for clarity
- Exported cleaned data to a new CSV file
