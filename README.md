# 📊 Sales Data Analysis with SQLite and Python

This task involves analyzing a sales dataset using **SQLite** for querying and **Pandas + Matplotlib** for data processing and visualization.

## 🗂 Dataset Overview

**Columns:**
- `id`: Unique transaction ID
- `date`: Date of sale (YYYY-MM-DD)
- `product_name`: Name of the product sold
- `category`: Product category
- `quantity_sold`: Units sold
- `unit_price`: Price per unit
- `revenue`: Total revenue
- `region`: Region of sale (e.g., East, West)

**Size:** 520 rows covering ~31 days

## 🔧 Tools & Technologies
- Python
- Pandas
- SQLite (via `sqlite3`)
- Matplotlib for charts

## 🗃 SQLite Usage

- Loaded data into a SQLite database from a Pandas DataFrame
- Queried using SQL via `pandas.read_sql_query()`
- Grouping, aggregation, and date extraction (`strftime`) done via SQL

# 📉 Visualizations

Charts were created using `matplotlib`, including:
- Bar charts (e.g., revenue by category, product)
- Line chart (monthly revenue trend)
- Pie charts for distribution
