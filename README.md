# 🏡 Nashville Housing Data Cleaning with SQL

**Project Type:** SQL Data Cleaning  
**Tools Used:** SQL Server Management Studio (SSMS)  
**Dataset:** Nashville Housing Dataset

## 🔍 Overview

This project involved cleaning and transforming a raw housing dataset using SQL. It simulates the data wrangling stage of a real estate analytics workflow, preparing the data for further analysis or reporting.

## 🧹 Key Tasks Completed

- Standardized `SaleDate` format and created a cleaned date column  
- Populated missing `PropertyAddress` values using `JOIN` logic  
- Split `PropertyAddress` into `PropertySplitAddress` and `PropertyCity`  
- Parsed `OwnerAddress` into `OwnerSplitAddress`, `OwnerSplitCity`, and `OwnerSplitState` using `PARSENAME()`  
- Cleaned and standardized `SoldAsVacant` field to consistent 'YES'/'NO' labels  
- Removed duplicate records using `ROW_NUMBER()` in a CTE  
- Dropped unnecessary columns (`OwnerAddress`, `TaxDistrict`, `SaleDate`, etc.)

## 📁 Files Included

- `nashville_cleaning_script.sql` – Full SQL script from raw to clean  
- `README.md` – Project summary  
- `/screenshots/` – Optional screenshots of query outputs or before/after views

## 🧠 SQL Concepts Used

- `ALTER TABLE`, `UPDATE`, `JOIN`, `PARSENAME()`  
- `ISNULL()`, `CASE`, `ROW_NUMBER()`  
- CTEs for de-duplication  
- String parsing and formatting  
- Column creation and cleanup

## ✅ Outcomes

- A fully cleaned and normalized version of the Nashville housing dataset  
- Prepared for analysis, dashboarding, or model development  
- Demonstrated real-world SQL cleaning practices used in business and data science

---

📌 *This project uses public data for educational and portfolio purposes.*
