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

## 📊 Live Dashboard
> [📊 Click here to view Live Dashboard]
(https://sterlingbankng-my.sharepoint.com/:x:/r/personal/john_anukua_sterling_ng/Documents/Sales%20Performance%20Dashboard.xlsx?d=wc4ca70b120464b6f9ba5fd9f17d3b5ae&csf=1&web=1&e=sTR7Md)
---

*This project was built as part of a BI portfolio to demonstrate 
data analysis and visualization skills.*
