# Netflix Movies Dataset - Data Cleaning

## Dataset:
Netflix Movies Detailed Up To 2025 (Kaggle)~16k rows

## Tools:
Python (Pandas)

## Cleaning Steps:
- Dropped 'duration' column (100% missing).
- Filled missing 'director', 'cast', 'description' with 'Unknown'.
- Filled missing 'genres' and 'country' with 'Not Specified'.
- Standardized 'country' names (e.g., 'united states of america' → 'United States Of America').
- Converted 'date_added' to datetime format.
- Removed duplicate rows.
- Renamed columns to snake_case for consistency.

## Files:
- Cleaned Dataset: cleaned_netflix_data.csv
- Code: netflix_data_cleaning.ipynb
