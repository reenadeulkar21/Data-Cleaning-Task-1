# Data-Cleaning-Task-1
Netflix Movies and TV Shows Cleaned dataset and short summary of changes 
# Task 1: Data Cleaning and Preprocessing

## Dataset Used
Customer Personality Analysis (from Kaggle)

## Tools
Python (Pandas)

## Cleaning Steps Performed:
- Removed 45 null values from `Income` column using median imputation
- Dropped 10 duplicate rows
- Standardized gender values to lowercase (`male`, `female`)
- Converted `Dt_Customer` column to datetime format
- Cleaned column names: no spaces, all lowercase
- Verified and corrected data types

## Output
- `cleaned_dataset.csv` file with clean, consistent data
- Ready for analysis or visualization
