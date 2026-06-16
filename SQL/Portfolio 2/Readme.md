# Portfolio Project 2 — Exploratory Data Analysis (EDA)
**Dataset: Cleaned Layoffs Dataset (continuation of Portfolio 1)**

## 📌 Overview
An exploratory data analysis on the cleaned tech layoffs dataset to 
surface trends, patterns, and business insights across companies, 
industries, countries, and time periods.

## 🎯 Objectives
1. Calculate summary statistics on total and percentage layoffs
2. Identify companies with complete (100%) workforce layoffs
3. Analyze layoff trends over time — monthly and yearly
4. Rank top companies by layoffs per year

## 🔑 Key Analyses
- Aggregated total layoffs by company, industry, and country
- Built a **rolling monthly layoff total** using window functions
- Ranked top 5 companies with highest layoffs per year using 
  `DENSE_RANK()`
- Identified full-closure companies (100% layoffs) ordered by 
  funds raised

## 🛠️ SQL Techniques Used
`GROUP BY` `ORDER BY` `SUM()` `MAX()` `Window Functions` 
`DENSE_RANK()` `CTEs` `Rolling Aggregations` `Subqueries`

## 📁 Files
| File | Description |
|---|---|
| `Portfolio Project - EDA.sql` | Full EDA pipeline |
