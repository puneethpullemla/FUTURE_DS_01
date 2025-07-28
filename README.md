# FUTURE_DS_01

# 📊 Business Sales Dashboard – Power BI Project

This is a sales analytics dashboard created as part of my **Data Science & Analytics Internship** with **Future Interns**.  
The project focuses on building an interactive and insightful **Business Sales Dashboard** using data from customer orders and product details.

---

## ✅ Task Objective

To develop a Power BI dashboard that enables dynamic insights into:
- 📈 Total Sales, Profits, Quantity, and Order Counts
- 🧭 Regional and Category-level sales performance
- 🔄 Filterable views by City, State, Category, Sub-Category, and Payment Method

---

## 📁 Dataset Overview

Two datasets were used and merged on the `Order ID` field:

### 1. `Orders.xlsx`
Contains customer order details:
- `Order ID`
- `Order Date`
- `CustomerName`
- `City`, `State`

### 2. `Details.xlsx`
Contains sales and product information:
- `Order ID`
- `Total Sales`, `Profit`, `Quantity`
- `Category`, `Sub-Category`
- `PaymentMode`

🔗 **Join Key**: `Order ID` (1-to-1 relationship)

---

## 📊 Dashboard Features

- **KPI Cards**:  
  ✅ Total Sales  
  ✅ Total Profit  
  ✅ Total Quantity  
  ✅ Total Orders

- **Visuals**:
  - 📊 Bar Chart: Sales by Sub-Category
  - 📍 Pie Chart: Profit by State
  - 💳 Donut Chart: Payment Method Share
  - 🧑‍💼 Top Customers by Sales
  - 🌆 City-wise Order Volume
  - 🗓 Sales Trend by Month/Quarter

- **Filters/Slicers**:
  - 📆 Order Date (Month, Quarter)
  - 🧭 Region: City & State
  - 🪑 Category / Sub-Category
  - 💳 Payment Mode

---

## 🛠 Tools & Technologies Used

- **Power BI Desktop**
- **Microsoft Excel** (for data formatting)
- **DAX Measures**:
  - `Total Sales = SUM(Details[Total Sales])`
  - `Total Profit = SUM(Details[Profit])`
  - `Total Quantity = SUM(Details[Quantity])`
  - `Total Orders = DISTINCTCOUNT(Orders[Order ID])`

---

## 🎥 Demo Video

▶️ Watch my dashboard in action:  
[]

---

## 📸 Screenshot

| Dashboard Preview |
|-------------------|
<img width="1920" height="1080" alt="Screenshot" src="https://github.com/user-attachments/assets/4f60b2e3-0ee8-4b9f-8cc4-c7ec0c0f029a" />

---

## 📚 Learnings & Takeaways

- ✅ Data modeling across multiple tables (with relationships)
- ✅ Creating insightful KPI cards and visual storytelling
- ✅ Designing dynamic dashboards with slicers and filters
- ✅ Exploring real-world sales analytics with regional dimensions

---


