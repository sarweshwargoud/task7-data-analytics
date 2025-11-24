# 📦 Task 7 — Basic Sales Summary Using Python + SQLite
📌 Objective

The goal of this task is to connect Python to an SQLite database, run a basic SQL query to get sales summaries (like total quantity and revenue), and visualize the output using a simple bar chart.

🛠 Tools Used

Python

SQLite (built-in, no installation required)

Pandas

Matplotlib

# 📂 Files Included
File	Description
create_db.py	Script that creates the sales_data.db database and inserts sample data
sales_summary.py	Script that connects to the database, runs SQL, prints results, and plots a bar chart
sales_data.db	SQLite database generated during the task
sales_chart.png	Revenue bar chart output (optional)
🧪 What the Script Does

Connects to SQLite database

Runs a query using GROUP BY to calculate:
✔ Total quantity sold
✔ Total revenue (quantity * price)

Loads results into a Pandas DataFrame

Prints the summary

Creates a simple bar chart using Matplotlib

# 📈 Output Example

Printed sales summary table

Bar chart showing revenue per product

# 🎯 Outcome

By completing this task, we practiced:
✔ Running SQL inside Python
✔ Using Pandas for data handling
✔ Visualizing results using Matplotlib
✔ Understanding database-to-Python workflow
