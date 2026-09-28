# 📊 Sales Performance Dashboard | Power BI

An interactive, multi-page Power BI report that analyzes sales, customers, orders, product categories and profitability across **2023–2025**. It is built on a star-schema data model with DAX measures, so stakeholders can move from a high-level business overview down to region, customer, order and product detail.

---

## 🎯 Project Objectives
- Give a high-level view of sales, customers, orders and profitability.
- Compare regional performance in revenue, profit, discount and delivery time.
- Understand customer segments, behavior and payment preferences.
- Track order completion and cancellation patterns.
- Analyze category demand, cost and profit margin.
- Monitor revenue, cost, profit and margin trends year over year.

---

## 📑 Dashboard Pages

| Page | Purpose |
|------|---------|
| **Business Overview** | KPIs (customers, orders, quantity, cancellations, rating, discount, profit, delivery), profit by region, top 5 products by revenue, orders and revenue by year |
| **Regional Performance** | Customers, revenue, weekday orders, average delivery days and average discount by region |
| **Customer Analytics** | Customers and revenue by age group, customers by category, top months, payment methods |
| **Order Analytics** | Completed vs. canceled orders by age range, year, category, month and payment method (toggle between the two views) |
| **Product Performance** | Category cost, quantity, orders, top products by profit margin, delivery days per category |
| **Performance Overview** | Cost breakdown by year/quarter/month, discount vs. profit margin, profit and revenue by month and year, growth KPIs |

All pages include **Year** and **Quarter** slicers and a navigation menu.

---

## 🔑 Key Metrics

- **Customers:** 3,996
- **Orders:** 30K, of which 646 were canceled
- **Units sold:** 111K
- **Average rating:** 3.84
- **Average discount:** 16.67%
- **Average profit per order:** $148.22
- **Average delivery time:** 6.70 days
- **Average profit margin:** 20.90%

---

## 💡 Key Insights

- **Revenue is growing but profit is not.** Revenue rose from about $6.96M (2023) to $9.18M (2025), while profit fell from $1.54M to $1.39M.
- **Margins are under pressure.** Profit margin dropped from 24.37% to 18.25%, while the average discount rose from 14.95% to 17.68%.
- **The West region leads.** It accounts for about 30% of total profit and has the highest revenue ($7.4M), but also the longest average delivery time (8.02 days). The North is the fastest at 5.52 days.
- **Electronics is the top category** in revenue, orders and cost, and it holds the top 5 revenue-generating products.
- **Customers aged 26–45 are the core segment**, and Card is the most-used payment method, followed by COD and Wallet.
- **Orders peak in July**, and cancellations are concentrated in Electronics and Groceries.

---

## 🗂️ Data Model

The model is a **star schema**, with one fact table and five dimension tables:

- **Fact_Sales**: the transactional data
- **Dim_Customer**
- **Dim_Product**
- **Dim_Date**
- **Dim_Region**
- **Dim_Payment**

It has **5 one-to-many relationships** and **26 DAX measures** covering revenue, profit, margin, growth %, discount, delivery days and cancellations.

---

## 🛠️ Tools & Skills Used

- **Power BI Desktop**: report design and interactive visuals
- **Power Query**: data cleaning and transformation
- **DAX**: KPIs, time intelligence and growth calculations
- **Data Modeling**: star schema and relationships
- **UX/UI design**: consistent theme, navigation menu and slicers

---

## 📁 Repository Structure

```
├── SalesDashboard.pbix     # Power BI report file
├── data/                   # Dataset [add if you can share it]
├── screenshots/            # Dashboard page images
└── README.md
```

---

## 🖼️ Screenshots

![Business Overview](screenshots/business-overview.png)
![Regional Performance](screenshots/regional-performance.png)
![Customer Analytics](screenshots/customer-analytics.png)
![Order Analytics](screenshots/order-analytics.png)
![Product Performance](screenshots/product-performance.png)
![Performance Overview](screenshots/performance-overview.png)
![Data Model](screenshots/data-model.png)

---

## 🚀 How to Use

1. Download the `.pbix` file.
2. Open it in **Power BI Desktop**.
3. Use the Year and Quarter slicers and the navigation menu to explore.

---

## 👤 Author

**[Your Name]**
[LinkedIn] | [Email] | [Portfolio]
