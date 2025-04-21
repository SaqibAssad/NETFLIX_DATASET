# NETFLIX_DATASET
Data cleaning and processing of Netflix dataset.

### 1. Missing Values
- Detected using filters in Google Sheets.
- Filled missing director, cast and country field with "Unknown".

### 2. Duplicates
- Removed exact duplicate rows using Data → Data Cleanup → Remove Duplicates.

### 3. Text Standardization
- Cleaned columns like type, country, and rating:
  - Removed extra spaces using TRIM().
  - Applied consistent casing using PROPER().
  - Used Find & Replace for values like "usa" → "United States".

### 4. Date Formatting
- Reformatted date_added to consistent dd-mm-yyyy format using excel
  
### 5. Header Cleanup
- Renamed column headers for consistency: All lowercase
- Replaced spaces with underscores (e.g., Date Added → date_added)

### 6. Data Type Verification
- Ensured release_year is numeric.
- Verified date_added values are valid dates
