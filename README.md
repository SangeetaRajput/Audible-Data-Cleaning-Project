# Audible-Data-Cleaning-Project

# Project Overview
This project focuses on cleaning and preparing an Audible dataset to make it analysis-ready. The dataset contains audiobook and podcast-related data from Audible, an American online audiobook and podcast service. The goal of this project was to identify inconsistencies, transform data for uniformity, and ensure the dataset could support further analysis and visualization.

Dataset Link:https://drive.google.com/file/d/1yjyozaSrwShoaROq-TDuSgC5HNLLmrTE/view?usp=sharing

# Data Cleaning Tasks and Applied Steps
1. Name Standardization

&#8226; Step Applied: Capitalized each word in the "Name" column to ensure uniform title casing.

&#8226; Explanation: This ensures that the product titles follow a consistent format, improving readability and data presentation.

2. Author Name Separation

&#8226; Step Applied: Split the "Author" column by delimiter or character transitions to separate first and last names.

&#8226; Explanation: When authors’ full names were combined, the column was split into separate fields for better data organization.

3. Release Date Standardization

&#8226; Step Applied: Converted the "ReleaseDate" column to a date format (DD-MM-YYYY).

&#8226; Explanation: Ensuring consistent date formats across the dataset allows for accurate analysis based on release dates.

4. Duration Conversion

&#8226; Step Applied:Extracted hours from the "Time" column.
Converted hours to minutes using a multiplication formula.

&#8226; Explanation: The time values were transformed into a recognized Excel duration format, allowing for proper time calculations and analysis.

5. Price Column Cleanup

&#8226; Step Applied:Replaced non-numeric values (e.g., "Free") with "0."
Changed the data type of the "Price" column to currency.
Applied formatting to ensure all values have two decimal places.

&#8226; Explanation: This ensures all price entries are numeric and uniformly formatted, allowing for meaningful pricing analysis.

6. Star Rating Conversion

&#8226; Step Applied: Replaced text-based star ratings with numeric values.

&#8226; Explanation: This step facilitates easier analysis and calculations of product ratings.

7. Narrator Separation

&#8226; Step Applied:Split the "NarratedBy" column by delimiters (e.g., commas) to separate multiple narrators.
Merged split narrator columns for clarity.

&#8226; Explanation: This helps identify individual narrators when multiple are listed for a single audiobook, improving the clarity of the dataset.

8. Merging Columns for Release Info

&#8226; Step Applied: Merged the "ReleaseDate" and "Language" columns into a new column "ReleaseInfo" with the format "DD-MM-YYYY, Language."

&#8226; Explanation: Combining these columns provides a comprehensive view of release information and simplifies the dataset.

9. Null Value Replacement

&#8226; Step Applied: Replaced null values in various columns with appropriate placeholders (e.g., "Not Applicable" or "0").

&#8226; Explanation: This ensures there are no gaps in the dataset, improving data integrity for further analysis.

# Key Excel Features Used

&#8226; Power Query Editor: For column formatting, data splitting, and transformation tasks.

&#8226; Text to Columns: To separate combined names and narrators.

&#8226; Data Type Conversion: Converted text data types to appropriate formats like numeric and date.

&#8226; Merge Columns: Combined "ReleaseDate" and "Language" into a single column using custom formatting.

&#8226; Conditional Formatting: Applied for visual consistency checks.

# Conclusion
The project effectively cleaned and standardized the Audible dataset, ensuring uniformity in column formats and preparing it for deeper analysis. Power Query Editor's transformation capabilities were pivotal in streamlining this process.
