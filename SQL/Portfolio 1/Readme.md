# Portfolio Project 1 — SQL Data Cleaning
**Dataset: [Tech Layoffs 2022 — Kaggle](https://www.kaggle.com/datasets/swaptr/layoffs-2022)**

## 📌 Overview
A structured data cleaning pipeline applied to a real-world tech layoffs 
dataset using advanced MySQL techniques. The goal was to transform a raw, 
messy dataset into a clean, analysis-ready staging table.

## 🎯 Objectives
1. Remove duplicate records
2. Standardize data formats and values
3. Handle NULL and blank values
4. Remove irrelevant rows and columns

## 🔑 Key Steps
- Detected duplicates using `ROW_NUMBER()` with `PARTITION BY` across 
  all key columns
- Standardized industry names, trimmed whitespace, converted date 
  strings to proper `DATE` type using `STR_TO_DATE()`
- Handled NULLs using conditional `UPDATE` statements and self-joins
- Produced clean output table: `layoffs_staging2`

## 🛠️ SQL Techniques Used
`CTEs` `ROW_NUMBER()` `PARTITION BY` `UPDATE` `ALTER TABLE` 
`STR_TO_DATE()` `TRIM()` `JOIN` `IS NULL`

## 📁 Files
| File | Description |
|---|---|
| `Portfolio Project - Data Cleaning.sql` | Full data cleaning pipeline |
| `layoffs.csv` | Source dataset |
