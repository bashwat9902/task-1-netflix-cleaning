 Task 1: Data Cleaning and Preprocessing

 Dataset:
Netflix Movies and TV Shows

 Steps Performed:
- Removed duplicate rows
- Filled missing `country` and `rating` with 'Unknown'
- Dropped rows with missing `director` or `cast` (important for content analysis)
- Standardized column names (lowercase, no spaces)
- Converted `date_added` to proper datetime format
- Cleaned string fields (stripped extra spaces)

 Output:
- Cleaned dataset saved as `cleaned_netflix_titles.csv`
