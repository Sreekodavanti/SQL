# Analyzing Startup Fundraising Deals from Crunchbase

This project focuses on processing, analyzing, and visualizing Crunchbase startup investment data using Python and SQLite.

## 📊 Dataset Overview

- Total entries: **52,870 rows**
- Significant missing data in `investor_category_code` (50,427 missing values)
- Initial memory usage: **56.99 MB**

## 🧹 Data Cleaning & Optimization

- Dropped columns with over 90% missing values (e.g., `investor_permalink`, `funded_month`)
- Optimized data types to reduce memory usage from **56.99 MB** to **26.84 MB**

## 🗄️ Data Storage

- Cleaned data loaded into an SQLite database (`crunchbase.db`)
- SQL queries used to extract insights (e.g., average raised amounts by company category)

## 📈 Visualization

- Top 15 company categories by average raised amount were visualized
- Tools used: **Matplotlib** and **Seaborn**

## 🛠️ Tools & Technologies

- Python
- Pandas
- SQLite
- Matplotlib
- Seaborn
  
