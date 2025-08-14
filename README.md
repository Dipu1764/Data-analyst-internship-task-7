# Data-analyst-internship-task-7
SQLite Sales Summary with Python

**Basic Sales Summary from a SQLite Database using Python**
**Project Overview**

This project demonstrates how to connect to a SQLite database using Python, run SQL queries to summarize sales data, and visualize the results with Matplotlib.
It covers:

Creating a sample sales database (sales_data.db)

Running SQL queries inside Python

Displaying query results using Pandas

Creating a simple bar chart for sales revenue

**Project Structure**
**project-folder**
│-- create_sales_db.py     # Script to create SQLite database with sample data
│-- sales_summary.py       # Script to query the database and plot revenue chart
│-- sales_data.db          # SQLite database file
│-- sales_chart.png        # Output bar chart
│-- README.md              # Project documentation

**Tools & Libraries Used**

Python 3

SQLite (built into Python)

Pandas (pip install pandas)

Matplotlib (pip install matplotlib)

**Dataset**
The sales table in sales_data.db contains the following fields:

id – Primary key (integer)

product – Product name (text)

quantity – Quantity sold (integer)

price – Price per unit (real)

**Sample Data:**

product	quantity	price
Apples	10	2.5
Bananas	8	1.8
Cherries	6	3.0
Dates	15	5.0

**Sales Summary:**
   product  total_qty  revenue
0   Apples         15     37.5
1  Bananas         20     36.0
2 Cherries        10     30.0
3    Dates         25    125.0


**Bar Chart:**
A simple bar chart showing revenue for each product.

**Learning Outcomes**

By completing this project, you will:

Learn to connect Python to SQLite databases

Write and run SQL queries from Python

Use Pandas to process SQL query results

Visualize data using Matplotlib

**License**

This project is free to use for learning and educational purposes.
