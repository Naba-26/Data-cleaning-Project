# Data-cleaning-Project
Data cleaning and preparation project for internship
## Goal
Clean a raw e-commerce order dataset by handling missing values, checking for duplicates, and validating data formats and calculations.

## Steps Performed
- Explored all columns to check for inconsistent text (typos, casing, spacing)
- Identified missing values in the CouponCode column (309 out of 1200 rows) and replaced blanks with "No Coupon"
- Checked for duplicate rows and duplicate OrderIDs — none found
- Verified CustomerID repeats were genuine repeat purchases, not data errors
- Confirmed Date and numeric columns were stored in correct formats
- Validated that Quantity × UnitPrice matches TotalPrice for all rows

## Tools Used
Microsoft Excel (filters, conditional formatting, Find & Replace, formulas)

## File
Project 1 (DATA CLEANING).xlsx — the cleaned dataset
