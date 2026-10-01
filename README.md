# 🧹 World Layoffs - SQL Data Cleaning Project

## 🎯 Project Overview
This project focuses on cleaning and standardizing a raw global tech layoffs dataset using advanced MySQL queries. Real-world datasets are usually messy, and this project demonstrates the end-to-end data preparation phase required before performing Exploratory Data Analysis (EDA) or financial reporting.

## 🛠️ Skills & Techniques Applied
* **Staging Tables:** Duplicated raw data into a staging table (`layoffs_staging`) to preserve the original source data safely.
* **Removing Duplicates:** Utilized Window Functions (`ROW_NUMBER()` with `PARTITION BY`) combined with Common Table Expressions (CTEs) to find and delete duplicate rows.
* **Data Standardization:** Trimmed unwanted spaces, fixed spelling inconsistencies in categorical columns, and converted text-based dates into standard SQL `DATE` data types.
* **Handling Nulls & Blanks:** Addressed missing values in text columns (like industry fields) and cleaned up rows with critical missing data.
* **Dropping Unnecessary Data:** Removed redundant columns and rows that did not add analytical value.

## 📁 File Included
* `Layoffs_Data_Cleaning.sql`: The complete, well-commented SQL script containing all data cleaning queries.
