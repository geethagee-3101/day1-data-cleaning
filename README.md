# Day 1: Data Cleaning and Preprocessing

## Objective
To identify and fix data quality issues in a raw dataset using Python and Pandas.

## Dataset
Titanic Dataset containing 891 rows and 12 columns.

## Tools Used
- Python
- Pandas
- Microsoft Excel

## Data Quality Issues and Solutions
- **Missing Age values (177):** Filled using the median.
- **Missing Cabin values (687):** Filled with "Unknown".
- **Missing Embarked values (2):** Filled using the most frequent value.
- **Duplicate rows:** No duplicates were found.

## Files Included
- `cleaned_titanic.csv` – Cleaned dataset in CSV format.
- `cleaned_titanic.xlsx` – Cleaned dataset in Excel format.
- `change_log.csv` – Record of identified issues and
