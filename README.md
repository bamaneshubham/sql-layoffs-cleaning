# 🧹 SQL Data Cleaning Project – Layoffs Dataset

This project demonstrates real-world data cleaning using SQL on a tech layoffs dataset. 
It includes identifying and removing duplicates, handling nulls, standardizing data, and exporting a cleaned version of the dataset.

## 🗂 Files
- `layoffs.csv` – Original raw data
- `Data Cleaning.sql` – SQL queries for cleaning
- `cleaned_layoffs.csv` – Final cleaned dataset

## 🔧 What’s Covered in SQL
- Duplicate removal using `ROW_NUMBER()` and CTEs
- Text standardization with `TRIM()`, `LIKE`, and `UPDATE`
- Handling null/missing values
- Column formatting and date conversion

## 💡 Skills Demonstrated
- SQL data wrangling
- Use of CTEs and window functions
- String and date manipulations
- Real-world ETL logic for business data

## ✅ How to Use
You can run the SQL file step-by-step in MySQL Workbench or DBeaver to clean the dataset yourself.  
The final result is also exported as `cleaned_layoffs.csv`.

## 📊 Exploratory Data Analysis (EDA)

After cleaning the data, I performed EDA using SQL to uncover key trends and insights:

- Top companies, industries, and countries by total layoffs
- Layoff trends over time (monthly and yearly)
- Peak layoff periods
- Rolling totals using window functions
- Top 5 companies by layoffs each year (ranked)

Check the analysis queries in: `Exploratory Data Analysis.sql`

---

> Built by Shubham Bamane as a personal portfolio project.
