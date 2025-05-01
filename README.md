# TASK7-DATA-ANALYSIS
# 📈 Sales Data Summary: SQLite-Powered Data Analysis with Python

This project demonstrates the integration of **SQLite**, **SQL queries**, **Pandas**, and **Matplotlib** to perform a basic sales data analysis pipeline. It provides a simple yet effective example of how to extract, transform, and visualize structured data using Python, without requiring any external database setup.

---

## 📌 Objective

The goal of this project is to:

- Establish a connection with a local SQLite database (`sales_data.db`)
- Execute an SQL query to compute:
  - Total quantity sold per product
  - Total revenue per product
- Load the result into a Pandas DataFrame
- Display the output in tabular form
- Visualize the revenue data using a bar chart via Matplotlib

---

## 🧰 Technologies Used

| Tool           | Purpose                                |
|----------------|----------------------------------------|
| Python 3.x     | Core scripting language                |
| SQLite         | Lightweight, file-based relational DB  |
| Pandas         | Data manipulation and analysis         |
| Matplotlib     | Data visualization                     |

---

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/sales-data-summary.git
cd sales-data-summary
pip install pandas matplotlib
python sales_summary.py
  product  total_qty  revenue
0   Apple         17      8.5
1  Banana         15      3.0
2  Orange         12      3.6

