# E-Commerce Sales Analysis with SQL

**Author:** Aryam Khaled  
**Date:** November 2026  
**Repository:** [Your GitHub Link]

---

## Project Overview

SQL-based analysis of the UCI Online Retail Dataset, using SQLite and Python to uncover sales trends and customer behavior.

---

## Tech Stack

- **Python**
- **Pandas** (Data manipulation)
- **SQLite** (Database)
- **SQL** (Analysis)

---

## Database Structure

| Table | Description |
|-------|-------------|
| **Products** | Unique products (StockCode, Description, UnitPrice) |
| **Invoices** | Unique invoices (InvoiceNo, Date, CustomerID, Country) |
| **Invoice_Details** | Transactions (InvoiceNo, StockCode, Quantity) |
| **Clean_Sales** (View) | Cleaned view excluding administrative items |

---

## Key Analyses

1. **Top 5 Products by Quantity:** Identified the most sold products.
2. **Top 5 Products by Revenue:** Calculated total revenue (Quantity × UnitPrice).
3. **Top 5 Customers:** Found the highest-spending customers.
4. **Sales by Country:** Analyzed geographic distribution of sales (UK dominates).

---

## How to Run

1. Install requirements: `pip install pandas sqlite3 openpyxl`
2. Open the notebook: `sql_analysis.ipynb`
3. Run all cells.

---

## Dataset

- **Source:** UCI Online Retail Dataset
- **Size:** 541,909 transactions
- **Period:** December 2010 – December 2011