# 🛒 E-Commerce Sales Analysis
### Tools: SQL · Power BI | Domain: Retail & Sales

---

## 📌 Problem Statement
A retail company wanted to understand what is driving their revenue and 
where they are losing profit. The Sales Manager needed answers to:
- Which region, product category, and customer segment is most profitable?
- Are discounts helping sales or hurting profit margins?
- Which customers are the most valuable?

---

## 🎯 Objective
Analyze 12 months of sales transaction data and build an interactive 
Power BI dashboard to help the business make data-driven decisions.

---

## 🛠️ Tools & Skills Used
| Tool | Purpose |
|------|---------|
| SQL | Data exploration, aggregation, window functions |
| Power BI | Dashboard building, DAX measures |
| Power Query | Data cleaning, column transformations |
| DAX | KPI measures — Revenue, Profit Margin, Growth % |

---

## 📁 Dataset Overview
- **File:** `ecommerce_sales.csv`
- **Records:** 100 orders across 12 months (Jan–Dec 2023)
- **Columns:** 18 fields including order date, region, product category,
  customer segment, sales, profit, discount, and shipping cost

| Column | Description |
|--------|-------------|
| order_id | Unique order identifier |
| order_date | Date of purchase |
| customer_segment | Consumer / Corporate / Home Office |
| region | East / West / North / South |
| category | Technology / Furniture / Office Supplies |
| sales | Final revenue after discount |
| profit | Profit after all costs |
| discount | Discount % applied on the order |

---

## 🔍 SQL Analysis — What I Did

### Step 1: Data Exploration
- Checked total records, date range, and NULL values
- Verified data types and unique category values

### Step 2: Business Questions Answered via SQL
1. Overall KPIs — Total Revenue, Profit, Orders, Avg Order Value
2. Monthly revenue trend — which months performed best?
3. Category-wise sales and profit margin breakdown
4. Regional performance — state and region level
5. Customer segment analysis — who spends the most?
6. Discount impact — do heavy discounts reduce profit?
7. Repeat customer analysis — who are the loyal customers?

### Step 3: Advanced SQL
- Month-over-Month growth using **LAG() window function**
- Running cumulative revenue using **SUM() OVER()**
- Customer ranking within segments using **RANK() PARTITION BY**
- Category-wise pivot using **CASE WHEN**

---

## 📊 Power BI Dashboard — 4 Pages

### Page 1: Executive Summary
- KPI Cards — Total Revenue, Total Profit, Profit Margin %, Total Orders
- Line Chart — Monthly Revenue Trend
- Donut Chart — Revenue by Category
- Bar Chart — Revenue by Region

### Page 2: Product & Category Analysis
- Matrix Table — Category → Sub-Category with conditional formatting
- Top 5 Products by Revenue
- Scatter Chart — Discount % vs Profit Margin (key insight visual)

### Page 3: Regional & Customer Analysis
- Map Visual — Sales by State
- Customer Segment comparison
- Top 10 Customers table

### Page 4: Trend Analysis
- Revenue vs Profit over 12 months
- Quarterly Sales by Category
- Profit Margin % monthly trend

---

## 💡 Key Insights

1. **Technology** is the highest revenue category — contributes **35% of total sales**
2. **Orders with >20% discount have 60% lower profit margins** — discounting is hurting the business
3. **Corporate segment** has the highest average order value — best target for premium sales
4. **West region** consistently outperforms all other regions in revenue
5. **Q4 shows peak sales** — inventory should be stocked by October
6. **Repeat customers** generate a significant share of revenue — loyalty program recommended

---

## ✅ Business Recommendations

| # | Recommendation | Impact |
|---|---------------|--------|
| 1 | Cap discounts at 15% for Technology products | Protect profit margins |
| 2 | Launch targeted campaigns for Corporate segment | Increase high-value orders |
| 3 | Focus expansion efforts in West region | Maximize ROI |
| 4 | Start a loyalty program for repeat customers | Increase retention |
| 5 | Pre-stock inventory before Q4 | Capture peak demand |

---

## 📂 Repository Files

| File | Description |
|------|-------------|
| `ecommerce_sales.csv` | Raw dataset |
| `project1_ecommerce_sql.sql` | All SQL queries — exploration to advanced |
| `project1_powerbi_guide.md` | Step-by-step Power BI dashboard guide |

---

## 📷 Dashboard Preview
*(Screenshot will be added after Power BI dashboard is built)*

---

## 👤 About Me
Aspiring Data Analyst with skills in SQL, Power BI, and Python basics.
Currently working at Cognizant and transitioning into a data analyst role.

📧 [kajaravi4023@gmail.com] | 💼 [linkedin.com/in/ravindra-kaja-835292222]
