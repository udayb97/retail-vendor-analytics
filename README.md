
# Retail Vendor Performance Analysis

This project delivers a detailed vendor performance analysis by consolidating transactional data from multiple retail sources, computing financial and operational metrics, and preparing the output for exploratory analysis and future visualization. The goal is to empower procurement teams and decision-makers with actionable insights into vendor efficiency, profitability, and purchasing behavior.

---

## Objective

To automate and streamline vendor performance analysis by:

- Ingesting and structuring data from multiple raw CSV files into a relational database  
- Generating a unified vendor summary using SQL and pandas-based transformations  
- Performing exploratory analysis on profitability, sales volume, and turnover metrics  

---

## Tools & Technologies

- **Python 3.x** – Scripting and automation  
- **pandas** – Data manipulation and metric computation  
- **SQLite** – Lightweight relational storage for structured data  
- **SQLAlchemy** – Interface for programmatic database ingestion  
- **SQL** – Complex joins and vendor-level aggregations  
- **Jupyter Notebook** – Interactive analysis and validation  
- **Logging** – Traceable execution and debugging  

---

## Project Workflow

1. Data Collection & Structuring
All raw vendor-related data, including purchases, sales, prices, and freight invoices, is collected and organized into a structured database. This ensures consistency and enables seamless access for analysis.

### 2. Vendor Performance Summary Generation
Key metrics such as purchase volumes, sales revenue, gross profit, and freight costs are calculated by consolidating data across multiple sources. This step produces a unified view of each vendor’s contribution to the business, allowing for fair comparison and evaluation.

### 3. Exploratory Data Analysis (EDA)
- Performed data validation to ensure the accuracy and consistency of the computed vendor metrics  
- Analyzed key indicators such as gross profit, margin, and turnover to rank vendors and identify top and bottom performers  
- Evaluated the completeness of each dataset, addressed missing values, and excluded irrelevant sources (e.g., inventory tables)

---

## Key Business Questions Addressed

- Which vendors contribute the most to total purchase dollars?  
- Which brands demonstrate high margins but low sales — suggesting promotional or pricing opportunities?  
- How concentrated is procurement spend among top vendors?  
- Are bulk purchases resulting in better unit pricing across brands?  
- What is the capital exposure from unsold inventory, and which vendors are responsible for it?  

---
