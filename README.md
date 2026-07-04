# Decodelabs-Project-1-Data-Cleaning

**Sales Data — Data Cleaning Report**

**Tool Used:** Microsoft Excel
Dataset: Sales Transaction Dataset
Total Records: 1,200 rows

**Project Overview**
This project involved cleaning a raw sales dataset to ensure data accuracy, consistency and readiness for analysis. The goal was to eliminate errors and standardize the data before any analytical work could begin.

**Data Cleaning Steps Performed**
1. Handled Missing Values
The Coupon Code column contained several empty cells. Each missing entry was filled with "No Coupon" to maintain data completeness and ensure no rows were lost during analysis.
2. Fixed Currency Formatting
The Unit Price and Total Unit Price columns were formatted as plain numbers without currency symbols. These were standardized to a proper currency format for consistency and readability.
3. Standardized Date Format
The Date column was originally in short date format which made entries difficult to read. This was converted to long date format to ensure clarity and consistency across all records.
4. Adjusted Column Widths
All columns were resized to properly accommodate their entries. This included the Date column and all other fields where data was being cut off or hidden due to narrow column widths.
5. Relocated Primary Key Column
The primary key column (Customer ID) was not in the first position. It was moved to Column A following standard database structuring conventions where the primary key should always be the first column.
6. Applied Conditional Formatting
Color-coded conditional formatting was applied to the Order Status column to allow quick visual identification of each order's status — making it easy to distinguish between Delivered, Pending, Cancelled, Returned and Shipped orders at a glance.
Outcome

All 1,200 records were retained after cleaning. The dataset was fully standardized and ready for further analysis.

## Screenshots
### Before Cleaning
![Messy Data](Messy%20Data.jpg)

### After Cleaning
![Cleaned Data](Cleaned%20Data.jpg)


###Dataset

The Full Cleaned Dataset can be downloaded here: 
[Download Dataset](Dataset%20for%20Data%20Analytics.xlsx)


