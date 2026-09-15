# Task 8 – Sales Tracker in Google Sheets

## Objective

The objective of this task is to create a simple and automated Sales Tracker using Google Sheets. The tracker calculates daily, weekly, and monthly sales totals using SUMIFS and date-based conditions.

## Dataset

The project uses a retail Superstore sales dataset containing order dates, order IDs, products, categories, regions, quantities, and sales values.

## Tools Used

- Google Sheets
- SUMIFS
- Date functions
- Data Validation

## Data Structure

The Raw Data sheet contains:

- Order Date
- Order ID
- Product
- Category
- Region
- Quantity
- Sales

## Sales Analysis

The Summary sheet provides:

### Daily Sales
Daily sales totals are calculated using SUMIFS based on the Order Date.

### Weekly Sales
Weekly sales are calculated for a Monday-to-Sunday period using date range conditions.

### Monthly Sales
Monthly sales are calculated using the first day of the month and the following month as the date boundaries.

## Data Validation

Data validation was applied to reduce incorrect data entry.

- Category: Furniture, Office Supplies, Technology
- Quantity: Greater than 0
- Sales: Greater than or equal to 0

## Verification

The calculated Daily, Weekly, and Monthly sales totals were manually checked against the Raw Data to verify that the formulas were producing the correct results.

## Key Outcome

A functional sales tracker was created that automatically summarizes sales at daily, weekly, and monthly levels. The use of SUMIFS and date-based conditions makes the tracker easy to update when new sales records are added.

## Conclusion

This project demonstrates the use of Google Sheets for basic sales analysis, automated date-based calculations, data validation, and manual result verification.
