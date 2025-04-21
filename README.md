# Elevate_Labs_Internship_Task1

# Task 1: 
Data Cleaning and Preprocessing

# Objective: 
Clean and prepare a raw dataset (with nulls, duplicates, inconsistent formats).

# Tools Used: 
Python (Pandas)

# Deliverables: 
Cleaned dataset + short summary of changes

# Task Phases:
step1---Identify and handle missing values using .isnull() in Python or filters in Excel.

step2---Remove duplicate rows using .drop_duplicates() or Excel’s “Remove Duplicates”.

step3---Standardize text values like gender, country names, etc.

step4---Convert date formats to a consistent type (e.g., dd-mm-yyyy).

step5---Rename column headers to be clean and uniform (e.g., lowercase, no spaces).

step6---Check and fix data types (e.g., age should be int, date as datetime).

# Summary:
- The script loads the superstore.csv dataset using pandas.

- It performs initial checks for the number of rows/columns, missing values, and duplicates.

- All rows containing missing values are removed to ensure data completeness.

- Duplicate rows are dropped to eliminate redundancy.

- Column names are standardized by trimming spaces, converting to lowercase, and replacing spaces with underscores.

- Specific columns like order_date and ship_date are converted to datetime format.

- All text fields are cleaned by removing extra spaces and converting values to title case.

- Final diagnostics are run to check for remaining issues after cleaning.

- The cleaned dataset is saved as superstore_cleaned.csv.

- A summary is printed showing changes made to the data during the cleaning process.
