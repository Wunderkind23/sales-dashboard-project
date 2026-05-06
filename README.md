# 📊 Sales Performance Dashboard

A Business Intelligence project analyzing regional sales trends, 
top-performing products, and revenue KPIs built with SQL and Google Sheets.

**Built by:** [wunderkind23](https://github.com/wunderkind23)

---

## 🛠️ Tools Used
- **SQL** (SQLite) — data querying and aggregation
- **Google Sheets** — dashboard and data visualization

---

## 📁 Project Files
| File | Description |
|---|---|
| `README.md` | Project overview |
| `queries.sql` | All SQL queries used in this project |
| `dashboard-link.md` | Link to live Google Sheets dashboard |

---

## 🔍 Key Business Questions Answered
1. Which region generates the highest revenue?
2. What are the top 3 best-selling products?
3. What is the average order value per product?
4. How many orders were placed per region?

---

## 📌 Key Insights
- **Lagos** had the highest number of orders across all regions
- **Laptops** were the highest revenue-generating product
- **Abuja** showed strong performance in high-ticket items

---

## 💾 SQL Skills Demonstrated
```sql
-- Example: Total revenue by region
SELECT region, SUM(revenue) AS total_revenue
FROM sales
GROUP BY region
ORDER BY total_revenue DESC;
```

---

## 📸 Screenshots

### Dashboard Overview
![Dashboard](https://raw.githubusercontent.com/Wunderkind23/sales-dashboard-project/main/image/dashboard-overview.png.png)

### SQL Exercises
![SQL Table](https://raw.githubusercontent.com/Wunderkind23/sales-dashboard-project/main/image/sql-table-created.png.png)
![SQL Select All](https://raw.githubusercontent.com/Wunderkind23/sales-dashboard-project/main/image/sql-select-all.png.png)
![SQL Select Columns](https://raw.githubusercontent.com/Wunderkind23/sales-dashboard-project/main/image/sql-select-columns.png)
![SQL Where Lagos](https://raw.githubusercontent.com/Wunderkind23/sales-dashboard-project/main/image/sql-where-lagos.png.png)
![SQL Revenue Filter](https://raw.githubusercontent.com/Wunderkind23/sales-dashboard-project/main/image/sql-where-revenue-filter.png.png)
![SQL Sum Revenue](https://raw.githubusercontent.com/Wunderkind23/sales-dashboard-project/main/image/sql-sum-total-revenue.png.png)
![SQL Group By Region](https://raw.githubusercontent.com/Wunderkind23/sales-dashboard-project/main/image/sql-groupby-region-revenue.png.png)
![SQL Order By Product](https://raw.githubusercontent.com/Wunderkind23/sales-dashboard-project/main/image/sql-orderby-product-revenue.png.png)
![SQL Count Orders](https://raw.githubusercontent.com/Wunderkind23/sales-dashboard-project/main/image/sql-count-orders-region.png.png)
![SQL Average Revenue](https://raw.githubusercontent.com/Wunderkind23/sales-dashboard-project/main/image/sql-avg-revenue-product.png.png)
![SQL Top 3 Products](https://raw.githubusercontent.com/Wunderkind23/sales-dashboard-project/main/image/sql-limit-top3-products.png.png)
![SQL Full Summary](https://raw.githubusercontent.com/Wunderkind23/sales-dashboard-project/main/image/sql-full-summary.png.png)

## 📊 Live Dashboard
> [📊 Click here to view Live Dashboard]
(https://sterlingbankng-my.sharepoint.com/:x:/r/personal/john_anukua_sterling_ng/Documents/Sales%20Performance%20Dashboard.xlsx?d=wc4ca70b120464b6f9ba5fd9f17d3b5ae&csf=1&web=1&e=sTR7Md)
---

*This project was built as part of a BI portfolio to demonstrate 
data analysis and visualization skills.*
