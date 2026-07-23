# AtliQ-Hardware-Insights

## Problem Statement

AtliQ Hardware is a fast-growing consumer electronics company. Previously, the company relied entirely on Excel for reporting, which was inefficient and prone to errors. To improve business analytics and decision-making, the company moved to SQL for more reliable, scalable, and automated reporting.

## Project Overview

This project analyzes AtliQ Hardware's finance data using MySQL. The main goal is to automate recurring and ad hoc business reports by using SQL features such as user-defined functions, views, stored procedures, and window functions.

## Key Highlights

* Used window functions to generate a report showing the top 10 customer by percentage of net sales for FY 2021.
* Created user-defined functions (UDFs) to calculate:
  * Fiscal year
  * Fiscal quarter
* Developed stored procedures to automate:
  * Monthly sales reports
  * Market badge classification (Gold if quantity > 5 million, otherwise Silver)
  * Top markets, customers, and products based on net sales
  * Top Products per Division by Quantity Sold
* Built SQL views for:
  * Pre-invoice deductions
  * Post-invoice deductions
  * Final net sales

## Concepts & Skills Used

* Subqueries
* Common Table Expressions (CTEs)
* Views
* Stored Procedures
* Window Functions (`ROW_NUMBER()`, `RANK()`, `DENSE_RANK()`)
* User-Defined Functions (UDFs)

## Attached Screenshots

### 1. Top 10 customer by percentage of net sales for FY 2021
![Top 10 customer by percentage of net sales for FY 2021](https://github.com/mohinivaidya1501-byte/AtliQ-Hardware-Insights/blob/main/Queries%20Screenshot/Net%20Sales%20Percentage%20by%20Customer.png)

### 2. Fiscal Year Function (Function)
![Fiscal year](https://github.com/mohinivaidya1501-byte/AtliQ-Hardware-Insights/blob/main/Queries%20Screenshot/Fiscal%20Year%20Function.png)

### 3. Fiscal Quarter Function (Function)
![Fiscal quarter](https://github.com/mohinivaidya1501-byte/AtliQ-Hardware-Insights/blob/main/Queries%20Screenshot/Fiscal%20Quarter%20Function.png)

### 4. Monthly sales reports (Stored Procedure)
![Monthly sales reports](https://github.com/mohinivaidya1501-byte/AtliQ-Hardware-Insights/blob/main/Queries%20Screenshot/Montly%20Sales%20Report%20(Procedures).png)

### 5. Market badge classification (Gold if quantity > 5 million, otherwise Silver) (Stored Procedure)
![Market badge](https://github.com/mohinivaidya1501-byte/AtliQ-Hardware-Insights/blob/main/Queries%20Screenshot/Market%20Badge%20(Procedure).png)

### 6. Top markets based on net sales (Stored Procedure)
![Top markets based on net sales](https://github.com/mohinivaidya1501-byte/AtliQ-Hardware-Insights/blob/main/Queries%20Screenshot/Top%20Market%20by%20Net%20Sales%20(Procedure).png)

### 7. Top customers based on net sales (Stored Procedure)
![Top customers based on net sales](https://github.com/mohinivaidya1501-byte/AtliQ-Hardware-Insights/blob/main/Queries%20Screenshot/Top%20Customers%20by%20Net%20Sales%20(Procedure).png)

### 8. Top products based on net sales (Stored Procedure)
![Top products based on net sales](https://github.com/mohinivaidya1501-byte/AtliQ-Hardware-Insights/blob/main/Queries%20Screenshot/Top%20Products%20by%20Net%20Sales%20(Procedure).png)

### 9. Top Products per division by quantity sold (Stored Procedure)
![Top Products per division by quantity sold](https://github.com/mohinivaidya1501-byte/AtliQ-Hardware-Insights/blob/main/Queries%20Screenshot/Top%20Products%20per%20Division%20by%20Quantity%20Sold%20(Procedure).png)

### 10. Pre-invoice deductions (View)
![Pre-invoice deductions](https://github.com/mohinivaidya1501-byte/AtliQ-Hardware-Insights/blob/main/Queries%20Screenshot/Pre-Invoice%20Discount%20(View).png)

### 11. Post-invoice deductions (View)
![Post-invoice deductions](https://github.com/mohinivaidya1501-byte/AtliQ-Hardware-Insights/blob/main/Queries%20Screenshot/Post-Invoice%20Discount%20(View).png)

### 12. Final net sales (View)
![Final net sales](https://github.com/mohinivaidya1501-byte/AtliQ-Hardware-Insights/blob/main/Queries%20Screenshot/Net%20Sales%20(View).png)

