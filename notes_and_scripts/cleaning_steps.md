# Maple Mart Excel Project

## Data Cleaning Steps

This file documents the full data preparation process applied to the original Raw Data.csv before analysis and dashboard creation.

1. Import raw data

   - The Raw Data.csv file was imported into a new Excel workbook and converted into an Excel Table using Ctrl T. Table formatting was applied for structured referencing.

2. Standardize Item Fat Content

   - The `Item Fat Content` column originally contained mixed lables like `Low Fat`, `Regular`, `LF`, and `reg`.
   - The values `LF` and `reg` were standardized using Find and Replace. `LF` was converted to `Low Fat`, and `reg` was converted to `Regular`. This created a clean two category field.

3. Add `Sr. no` column

   - A new column named Sr no was created to provide a simple row counter for item level counts by outlet. This was used in pivot tables requiring counts.

4. Validate numeric columns

   - The following fields were checked for missing values or formatting inconsistencies:
     - Item Visibility
     - Item Weight
     - Total Sales
     - Rating
   - Missing values were retained but acknowledged in the caveats.

5. No column deletions
   - All original columns were retained to preserve information about outlet characteristics and product attributes.

This cleaned dataset was then used to create all pivot tables on the Sheets Design sheet and the final dashboard.
