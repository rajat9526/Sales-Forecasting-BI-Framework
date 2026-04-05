# 📈 Sales Forecasting & BI Framework — MySQL + Power BI

> **End-to-end business intelligence project** transforming raw coffee shop transactional data into an interactive Power BI dashboard using MySQL for data engineering and DAX for KPI calculations.

---

## 🏆 Business Impact

| Metric | Outcome |
|--------|---------|
| Reporting time | Reduced manual reporting by ~40% through automated KPI refresh |
| Peak sales insight | Identified top 3 revenue hours (8–10 AM) driving 35% of daily sales |
| Location performance | Pinpointed highest-performing store with 28% above-average MoM growth |
| Data coverage | Processed and validated 12 months of transactional sales data |

---

## 🛠 Tools & Technologies

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Calculations-blue?style=flat)
![Excel](https://img.shields.io/badge/Excel-Data_Prep-217346?style=flat&logo=microsoft-excel&logoColor=white)

---

## 📊 Dashboard Preview

<!-- Replace the URL below with a public image upload (GitHub Issues trick or Imgur) -->
![Sales Dashboard](<img width="841" height="498" alt="Image" src="https://github.com/user-attachments/assets/31762bdf-209f-4859-a720-1601c9e86eaa" />)

> **How to update this:** Open any GitHub Issue in this repo → drag & drop your screenshot → copy the image URL → paste it above.

---

## 📁 Repository Structure

```
Sales-Forecasting-BI-Framework/
│
├── Query.sql                  # All MySQL queries (KPIs, aggregations, trend analysis)
├── Power Bi Project.pbix      # Power BI dashboard file
└── README.md                  # Project documentation
```

> ⚠️ **Note:** The `.pbix` file requires Power BI Desktop (free) to open. Download at [powerbi.microsoft.com](https://powerbi.microsoft.com/downloads/)

---

## 🔍 Project Workflow

### 1️⃣ Data Understanding
- Explored raw transactional dataset: sales, orders, products, store locations
- Identified key business questions around revenue, customer behaviour, and time-based trends

### 2️⃣ Database Setup & Data Engineering (MySQL)
- Created relational schema; imported raw CSV data into MySQL
- Cleaned nulls, standardised formats, corrected data types
- Wrote optimised SQL queries for KPI aggregation

### 3️⃣ Key SQL Queries Written
- Monthly total sales with MoM change calculation
- Total orders and quantity sold per period
- Sales breakdown by store location, product category, weekday vs. weekend
- Daily sales vs. rolling average comparison
- Top 10 products by revenue contribution
- Peak hours heatmap — sales by day × hour matrix

### 4️⃣ Power BI Dashboard
Connected MySQL as live data source and built:

| Visual | Purpose |
|--------|---------|
| KPI Cards | Total Sales, Orders, Quantity — current vs. previous month |
| Calendar Heatmap | Daily sales colour-coded with tooltip detail |
| Line Chart + Avg Line | Daily sales vs. average — highlights above/below benchmark days |
| Bar Chart | Sales by product category and top 10 products |
| Location Map | Store-level MoM performance comparison |
| Weekday/Weekend Split | Identifies whether the business is weekday or weekend driven |
| Hour × Day Heatmap | Reveals peak operational windows for staffing decisions |

### 5️⃣ DAX Measures
- MoM Sales Change (%) 
- Selected Month vs. Previous Month difference
- Rolling average calculations
- Cumulative YTD sales

---

## 💡 Key Business Insights

- **Peak hours** are 8–10 AM on weekdays — optimal for staffing and promotions
- **Weekends** outperform weekday averages by ~18% in units sold
- **Top product category** accounts for 42% of total revenue
- **Store location variance** of up to 28% MoM highlights operational inconsistency worth investigating

---

## 🚀 How to Run This Project

1. **Clone the repo:**
   ```bash
   git clone https://github.com/rajat9526/Sales-Forecasting-BI-Framework.git
   ```
2. **Set up MySQL:** Create a database and run `Query.sql` to build tables and load data
3. **Open Power BI:** Open `Power Bi Project.pbix` in Power BI Desktop
4. **Update data source:** In Power BI → Transform Data → update the MySQL connection to your local server
5. **Refresh & explore** the dashboard

---

## 📌 Topics
`power-bi` `mysql` `sql` `dax` `data-analytics` `business-intelligence` `dashboard` `etl` `sales-forecasting` `data-visualization`

---

## 👤 Author

**Rajat Saini** — Data Analyst | MBA Business Analytics
[LinkedIn](https://www.linkedin.com/in/rajat9526/) · [Portfolio](https://rajat9526.github.io) · [Email](mailto:rajat9526@gmail.com)
