# AtliQ-Hardware-Insights

## Problem Statement

AtliQ Hardware is a fast-growing consumer electronics company. Previously, the company relied entirely on Excel for reporting, which was inefficient and prone to errors. To improve business analytics and decision-making, the company moved to SQL for more reliable, scalable, and automated reporting.

## Project Overview

This project analyzes AtliQ Hardware's finance data using MySQL. The main goal is to automate recurring and ad hoc business reports by using SQL features such as user-defined functions, views, stored procedures, and window functions.

## Key Highlights

* Used window functions to generate a report showing the top 10 customer by percentage of net sales for FY 2021.
* Created user-defined functions (UDFs) to calculate the fiscal year and fiscal quarter.
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
