# Sales Data Cleaning Project With MS.Excel

### Overview
This project focuses on cleaning and standardizing a raw Sales Dataset to ensure it is accurate, consistent, and ready for analysis. The cleaning process involves addressing blank spaces, inconsistent formatting, and other common data issues.


<BR>

### Objectives
1. Ensure the dataset is free of errors and inconsistencies.
2. Standardize formatting for better readability and compatibility with analytical tools.
3. Prepare the dataset for further analysis and reporting.

<BR>

### Dataset
- Source: [Sales Original Dataset](https://docs.google.com/spreadsheets/d/1jlYjkwRHpL8zJczUbdOjCNUt5g9zm1yU/edit?usp=sharing&ouid=100554781607807743501&rtpof=true&sd=true) contains uncleaned Sales data.
- No of Columns: 15 columns.
- No of Rows: 706 rows.
- [Sales Cleaned Dataset](https://docs.google.com/spreadsheets/d/1P9zRt9LLe4Y3VI6MFKi15dmEKO4mzV8F/edit?usp=sharing&ouid=100554781607807743501&rtpof=true&sd=true) contains the cleaned Sales data.

<BR>

### Steps in Data Cleaning
#### 1. Handling Blank Spaces
- Used Ctrl + G to navigate to blank cells.
- Selected blank rows under the Special option.
- Deleted blank rows using the Delete function in the Home ribbon.

#### 2. Removing Cell Formatting
- Cleared all unnecessary formatting applied to cells for consistency and ease of data handling, using the Clear Function in the Home ribbon.

#### 3. Converting Text Cells to Numbers
- Addressed text-formatted numeric values in the Manufacturing Price column:
  - Typed 1 in a blank cell outside the dataset.
  - Copied the cell with 1
  - Go to Manufacturing Price column, highlight all the cells below the header and used Paste Special > Multiply on the column.
  - Ensured all values were correctly converted to numeric format.

#### 4. Applying Number Formatting
- Converted all price or amount-related columns to Accounting format for clarity.

#### 5. Standardizing Date Format
- Ensured all date columns followed a consistent date format across the dataset.

#### 6. Text Standardization
- Removed unnecessary spaces and inconsistencies in text using the TRIM(PROPER(cell)) function:
  - TRIM removed spaces before or after text.
  - PROPER capitalized the first letter of each word.
  - In the Country Column, change Usa to USA using Find and Replace Function (CTR +F)

#### 7. Spell Check
- Ran the spell checker under the Review tab to correct any spelling errors in textual data.

#### 8. Structuring Data into a Table
- Converted the cleaned dataset into a structured Excel table for easier filtering, sorting, and referencing.

<BR>

### Tools Used
- Microsoft Excel: For cleaning, formatting, and organizing the data.
- Documentation and Collaboration: GitHub.
