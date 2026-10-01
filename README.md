# 🛍️ Blinkit Sales & Delivery Analytics Dashboard

An interactive Power BI dashboard designed to analyze Blinkit order performance, revenue, delivery status, payment methods, monthly order trends, and delivery delays.

## 📌 Project Overview

This project uses Power BI to convert Blinkit order data into a compact business analytics dashboard.

The report is built around a `blinkit_orders` data model and includes KPI cards plus multiple visualizations for operational and sales analysis.

## 🎯 Objectives

- Monitor overall revenue and order performance.
- Track total orders and average order value.
- Analyze delivery-status distribution.
- Understand payment-method usage.
- Examine monthly order trends.
- Analyze average delivery delay by delivery status.
- Present business metrics in an interactive dashboard.

## 📊 Dashboard KPIs

The report contains KPI measures for:

- **Total Revenue**
- **Total Orders**
- **Average Order Value**
- **On-Time %**

## 📈 Dashboard Visuals

The Power BI report contains visualizations covering:

### Delivery Status
A clustered-column visualization compares order counts across `delivery_status`.

### Payment Methods
A pie chart shows the distribution of orders by `payment_method`.

### Monthly Order Trend
A line chart analyzes `Total Orders` across `Order Month`.

### Average Delay
A clustered-column chart compares `Avg Delay` across delivery-status categories.

## 🧮 Measures Used

The report model includes measures such as:

```text
Total Revenue
Total Orders
Avg Order Value
On Time %
Avg Delay
```

## 🗂️ Data Model

The main model entity identified in the Power BI report is:

```text
blinkit_orders
```

Important fields used by the visuals include:

```text
delivery_status
payment_method
Order Month
```

## 🛠️ Tech Stack

- Microsoft Power BI
- Power Query
- DAX measures
- Data modeling
- Data visualization
- KPI analysis
- Business intelligence

## 📂 Project Structure

```text
Blinkit-PowerBI-Dashboard/
│
├── Blinkit_Dashboard(1).pbix
└── README.md
```

## ▶️ How to Open

1. Install Microsoft Power BI Desktop.
2. Open:

```text
Blinkit_Dashboard(1).pbix
```

3. Refresh the data if the original data source is available.
4. Review the KPI cards and visuals.
5. Interact with the dashboard to explore the available dimensions.

## 💡 Business Questions Answered

The dashboard is designed to answer questions such as:

- How much total revenue was generated?
- How many orders were placed?
- What is the average order value?
- What percentage of orders were on time?
- Which delivery statuses have the most orders?
- Which payment methods are most frequently used?
- How does order volume change by month?
- Which delivery statuses have higher average delays?

## 🚀 Future Improvements

- Add slicers for date, location, outlet, category, and product.
- Add revenue and order trends by product category.
- Add customer/order segmentation.
- Add outlet-level performance analysis.
- Add drill-through pages.
- Add tooltip pages for deeper exploration.
- Add a dedicated executive summary page.

## 👩‍💻 Author

**Challa Swapna**

GitHub: `https://github.com/swapnachalla4826-sudo`
