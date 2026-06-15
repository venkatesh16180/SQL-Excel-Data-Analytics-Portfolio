# SQL & Excel Data Analytics Portfolio
**University of Arizona | MS Information Sciences**

---

## 📌 Overview
This repository contains SQL and Excel work spanning structured skill-building exercises and two end-to-end portfolio projects on a real-world dataset. It documents my practical journey building core data analytics competencies in SQL querying, database management, and Excel-based data analysis.

---

## 📁 Repository Structure
```
SQL-Excel-Data-Analytics-Portfolio/
│
├── SQL/
│   ├── Alex_1 through Alex_15        # SQL skill-building exercises
│   ├── Portfolio 1/                   # Data Cleaning Project
│   │   ├── Portfolio Project - Data Cleaning.sql
│   │   ├── layoffs.csv
│   │   └── Readme.md
│   └── Portfolio 2/                   # Exploratory Data Analysis Project
│       ├── Portfolio Project - EDA.sql
│       └── Readme.md
│
├── Excel/
│   ├── Alex_1 through Alex_6         # Excel skill-building exercises
│   └── Readme.md
│
└── README.md
```

---

## 🗄️ SQL Portfolio Projects

### Portfolio Project 1 — Data Cleaning
**Dataset:** [Tech Layoffs 2022 (Kaggle)](https://www.kaggle.com/datasets/swaptr/layoffs-2022)

A structured data cleaning pipeline applied to a real-world tech layoffs dataset using advanced MySQL techniques.

**Key steps:**
- Removed duplicate records using `ROW_NUMBER()` with `PARTITION BY` across all key columns
- Standardized data formats — trimmed whitespace, unified industry names, converted date strings to proper DATE type
- Handled NULL and blank values using conditional logic and table joins
- Removed irrelevant rows and columns to produce a clean, analysis-ready staging table (`layoffs_staging2`)

**SQL techniques used:**
`CTEs` `ROW_NUMBER()` `PARTITION BY` `UPDATE` `ALTER TABLE` `STR_TO_DATE()` `TRIM()` `JOIN`

---

### Portfolio Project 2 — Exploratory Data Analysis (EDA)
**Dataset:** Cleaned layoffs dataset (continuation of Portfolio 1)

An exploratory analysis of the cleaned layoffs data to surface trends and insights across companies, industries, and time periods.

**Key analyses:**
- Identified companies with 100% workforce layoffs and ranked by funds raised
- Aggregated total layoffs by company, industry, country, and year
- Built a rolling monthly layoff total using window functions
- Ranked top 5 companies by layoffs for each year using `DENSE_RANK()`

**SQL techniques used:**
`GROUP BY` `ORDER BY` `SUM()` `MAX()` `Window Functions` `DENSE_RANK()` `CTEs` `Rolling Aggregations`

---

## 📊 SQL Skill-Building Exercises
15 structured SQL scripts covering the full spectrum of MySQL querying:

| Script | Topic |
|---|---|
| Alex_1 | SELECT statements |
| Alex_2 | WHERE, LIKE |
| Alex_3 | GROUP BY, ORDER BY |
| Alex_4 | WHERE vs HAVING |
| Alex_5 | LIMIT, Aliasing |
| Alex_6 | JOINs (INNER, LEFT, RIGHT) |
| Alex_7 | UNIONS |
| Alex_8 | String Functions |
| Alex_9 | CASE Statements |
| Alex_10 | Subqueries |
| Alex_11 | Window Functions |
| Alex_12 | CTEs (Common Table Expressions) |
| Alex_13 | Temporary Tables |
| Alex_14 | Stored Procedures |
| Alex_15 | Triggers & Events |

> All scripts include inline comments explaining concepts and logic for learning reference.

---

## 📈 Excel Skill-Building Exercises
6 structured Excel workbooks covering core data analyst Excel skills:

| File | Topic |
|---|---|
| Alex_1 | Pivot Tables & Sales Analysis |
| Alex_2 | Formulas (SUM, AVERAGE, IF, etc.) |
| Alex_3 | XLOOKUP |
| Alex_4 | Conditional Formatting |
| Alex_5 | Charts & Visualization |
| Alex_6 | Data Cleaning in Excel |

---

## 🛠️ Tools & Technologies
| Category | Tools |
|---|---|
| Database | MySQL |
| Spreadsheet | Microsoft Excel |
| SQL Concepts | CTEs, Window Functions, Stored Procedures, Triggers, Subqueries, Joins |
| Excel Concepts | Pivot Tables, XLOOKUP, Conditional Formatting, Charts, Data Cleaning |

---

## 🚀 How to Run the SQL Projects
1. Clone the repository:
   ```bash
   git clone https://github.com/venkatesh16180/SQL-Excel-Data-Analytics-Portfolio.git
   ```
2. Import the dataset into MySQL:
   - Open MySQL Workbench
   - Import `layoffs.csv` into a new schema
3. Run scripts in order:
   - First: `Portfolio Project - Data Cleaning.sql`
   - Then: `Portfolio Project - EDA.sql`

---

## 👤 Author
**Venkateshwara Chowdary Tallapaneni**
MS Information Sciences (Machine Learning) | University of Arizona
[LinkedIn](www.linkedin.com/in/venkateshwara-chowdary-tallapaneni) | [GitHub](https://github.com/venkatesh16180)
