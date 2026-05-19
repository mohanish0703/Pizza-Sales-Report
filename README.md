# Pizza-Sales-Report# 🍕 Pizza Sales Report

A comprehensive sales analysis project built with **SQL** and **Power BI** to uncover trends, bestsellers, and revenue insights from a pizza restaurant's order data.

---

## 📊 Dashboard Preview

### Home Dashboard
![Pizza Sales Home Dashboard](https://raw.githubusercontent.com/mohanish0703/Pizza-Sales-Report/main/Screenshot%202025-09-14%20222320.png)

### Best & Worst Sellers
![Best and Worst Sellers Dashboard](https://raw.githubusercontent.com/mohanish0703/Pizza-Sales-Report/main/Screenshot%202025-09-14%20222335.png)

### SQL Query Reference
![SQL Queries](https://raw.githubusercontent.com/mohanish0703/Pizza-Sales-Report/main/Screenshot%202025-09-14%20223057.png)

---

## 📌 Overview

This project analyses pizza sales data to help restaurant managers and business stakeholders understand sales performance, identify top and bottom performing products, and optimise business strategies. SQL is used for data extraction and KPI validation, while Power BI delivers interactive, visually rich dashboards.

---

## 🎯 Objectives

- Track key sales KPIs: total revenue, total orders, average order value, pizzas sold
- Analyse daily and monthly sales trends
- Identify best and worst selling pizzas by revenue, quantity, and total orders
- Break down sales by pizza category and size
- Validate Power BI results against SQL queries for accuracy

---

## 🗂️ Repository Structure

```
Pizza-Sales-Report/
│
├── pizza_sales_excel_file - pizza_sales.csv   # Raw sales dataset
├── PIZZA REPORT powerBi.pbix                  # Power BI dashboard file
├── PIZZA SALES REPORT.docx                    # Project report with SQL queries
├── Screenshot 2025-09-14 222320.png           # Dashboard screenshot – Home
├── Screenshot 2025-09-14 222335.png           # Dashboard screenshot – Best/Worst Sellers
├── Screenshot 2025-09-14 223057.png           # SQL query validation screenshot
└── README.md
```

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **SQL (MySQL / MS SQL Server)** | Data querying and KPI validation |
| **Power BI** | Interactive dashboard and visualisations |
| **Excel / CSV** | Raw data source |
| **MS Word** | Project documentation and SQL reference |

---

## 📈 KPIs Tracked

| KPI | Description |
|-----|-------------|
| **Total Revenue** | Sum of all pizza order prices |
| **Average Order Value** | Revenue divided by total orders |
| **Total Pizzas Sold** | Sum of pizza quantities across all orders |
| **Total Orders** | Count of distinct orders placed |
| **Average Pizzas Per Order** | Average number of pizzas per transaction |

---

## 📊 Dashboard Pages

### 1. 🏠 Home Dashboard
- **Daily Trend** — Bar chart of orders by day of week
- **Monthly Trend** — Line chart showing orders across months
- **Sales by Pizza Category** — Donut chart (Classic, Supreme, Veggie, Chicken)
- **Sales by Pizza Size** — Donut chart (S, M, L, XL, XXL)
- **Total Pizzas Sold by Category** — Funnel chart
- KPI cards for Revenue, Avg Order Value, Total Orders, and more

### 2. 🏆 Best / Worst Sellers Dashboard
- **Top 5 Pizzas** by Revenue, Quantity, and Total Orders
- **Bottom 5 Pizzas** by Revenue, Quantity, and Total Orders
- Helps identify high-performing products and underperformers for menu optimisation

---

## 📁 Dataset

**File:** `pizza_sales_excel_file - pizza_sales.csv`

Key columns include:

| Column | Description |
|--------|-------------|
| `pizza_id` | Unique pizza identifier |
| `order_id` | Unique order identifier |
| `pizza_name` | Name of the pizza |
| `quantity` | Number of pizzas ordered |
| `order_date` | Date of the order |
| `order_time` | Time of the order |
| `unit_price` | Price per pizza |
| `total_price` | Total price for that line item |
| `pizza_size` | Size (S / M / L / XL / XXL) |
| `pizza_category` | Category (Classic / Supreme / Veggie / Chicken) |
| `pizza_ingredients` | Ingredients in the pizza |

---

## 🔍 Key Insights

- **Orders peak on Fridays and Saturdays**, indicating higher weekend demand
- **July and January** see the highest order volumes across the year
- **Classic pizzas** contribute the most to total sales and orders
- **Large size** is the most popular pizza size by revenue
- **The Thai Chicken Pizza** ranks among the top revenue generators
- **The Brie Carre Pizza** consistently appears among the lowest performers

---

## 🚀 How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/mohanish0703/Pizza-Sales-Report.git
   ```

2. **Load data into SQL**
   - Import `pizza_sales_excel_file - pizza_sales.csv` into MySQL or MS SQL Server
   - Run SQL queries from `PIZZA SALES REPORT.docx` to calculate KPIs

3. **Open Power BI Dashboard**
   - Open `PIZZA REPORT powerBi.pbix` in Power BI Desktop
   - Update the data source to point to your local CSV or SQL connection

4. **Explore the dashboards**
   - Use slicers to filter by pizza category and size
   - Toggle between **Home** and **Best/Worst Sellers** pages

---

## 👤 Author

**Mohanish**  
B.Tech Computer Science & Engineering  
Vellore Institute of Technology (VIT)  
[GitHub Profile](https://github.com/mohanish0703)
![report](https://github.com/mohanish0703/Pizza-Sales-Report/blob/31c599ad27a8b10ab7a9f31f6f5c37aff01c0fbe/Screenshot%202025-09-14%20222320.png)
![report](https://github.com/mohanish0703/Pizza-Sales-Report/blob/df31740fb53b4218ff1c537507174fa07b49b0cb/Screenshot%202025-09-14%20223057.png)
