# 🛒 Online Retail Data Analysis
### AnalystLab Africa — Data Analytics Internship Project
**Analyst:** Charles Tabi Gyansah | **Duration:** June – August 2026

---

## 📌 Project Overview

This project is a complete end-to-end data analysis of the **Online Retail dataset** a real-world e-commerce transaction dataset from a UK-based online retailer covering December 2010 to December 2011.

I completed this project as part of the **AnalystLab Africa Data Analytics Internship**, learning Python from scratch alongside the actual analysis work.

---

## 📂 Dataset

| Detail | Info |
|---|---|
| **Source** | UCI Machine Learning Repository — Online Retail Dataset |
| **Rows** | 541,909 transactions |
| **Columns** | 8 (InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country) |
| **Period** | December 2010 – December 2011 |
| **Countries** | 38 |

---

## ✅ Tasks Completed

### Task 1 — Dataset Understanding
- Loaded dataset into Python (Pandas)
- Identified data types, numerical vs categorical columns
- Found unique identifiers and described dataset contents

### Task 2 — Data Cleaning
- Handled 135,080 missing CustomerIDs and 1,454 missing Descriptions
- Removed 5,268 duplicate rows
- Fixed InvoiceDate from text to datetime format
- Standardised text formatting (Title Case, UPPERCASE)
- Lowercased all column names
- Excluded cancellations, returns, and invalid prices
- **Final clean dataset: 524,878 valid rows**

### Task 3 — Exploratory Data Analysis (EDA)
- Top 10 best-selling products by quantity
- Top 10 revenue-generating countries
- Monthly revenue trend analysis
- Top 10 customers by revenue
- Customer purchase frequency analysis

### Task 4 — Data Visualisation
- 📊 Bar Chart — Top 10 Best-Selling Products
- 📊 Bar Chart — Revenue by Country (with UK comparison)
- 📈 Line Chart — Monthly Revenue Trend
- 🥧 Pie Chart — Revenue Share by Country
- 📉 Histogram — Unit Price Distribution

### Task 5 — Key Insights
Five actionable business insights derived from the analysis (see notebook for full details)

---

## 💡 Top Findings

> **The UK generates £9M in revenue — over 31x more than any other country**

> **Revenue nearly triples from February (£522K) to November (£1.5M) every year**

> **The top single customer spent £280,206 — likely a wholesale buyer**

> **Median unit price is just £2.08 — a high-volume, low-margin business**

> **25% of all transactions had no CustomerID — limiting customer analytics**

---

## 🛠️ Tools & Libraries Used

| Tool | Purpose |
|---|---|
| Python 3 | Programming language |
| Pandas | Data loading, cleaning, and analysis |
| Matplotlib | Data visualisation |
| Seaborn | Chart styling |
| Jupyter Notebook | Development environment |

---

## 📁 Project Files

| File | Description |
|---|---|
| `OnlineRetail_Analysis.ipynb` | Full Jupyter Notebook with all 5 tasks |
| `Summary_Report.docx` | One-page summary report |

> ⚠️ **Note on Datasets:** The cleaned dataset are not included in this repository due to GitHub's file size limit (the files exceed 25MB). You can access both CSV files via the Google Drive link below

---

## 🔗 Full Project on Google Drive
All deliverables including the cleaned dataset and raw data are available here:
https://drive.google.com/drive/folders/1HGI9UGAFSad6pEbzdK_b60q5_j1mGIBy?usp=drive_link

---

## 🎓 About This Internship

This project was completed as part of the **AnalystLab Africa Data Analytics Internship Programme** (June – August 2026). The programme provides hands-on experience with real-world datasets to help build practical data skills.

I started this project with **no prior Python experience**, learning every concept — from DataFrames to groupby to matplotlib — while building the actual analysis. Every line of code in the notebook is commented to explain what it does and why.

---

*#DataAnalytics #Python #Pandas #EDA #DataCleaning #AnalystLabAfrica*
