# 🍽️ Restaurant Orders Analysis  
**By Mambila Analytics**

## 📌 Project Overview
This project analyzes a quarter’s worth of restaurant order data for an international cuisine restaurant.  
The goal is to uncover **customer ordering patterns, best-selling items, category performance, and peak business hours** using **SQL and Excel**.

The analysis supports **data-driven decision making** for menu optimization, staffing, and revenue growth.

---

## 🗂️ Dataset Description
The project uses **two related tables**:

### 1️⃣ Menu Items Table
Contains information about each item on the menu.
- `menu_item_id`
- `item_name`
- `category`
- `price`

### 2️⃣ Order Details Table
Contains transactional order data.
- `order_details_id`
- `order_id`
- `order_date`
- `order_time`
- `item_id`

---

## 🎯 Business Questions Answered
1. Which menu items sell the most?
2. Which menu categories generate the highest number of orders?
3. What are the peak ordering hours during the day?
4. How does customer demand vary throughout the day?
5. Which items and categories drive the most customer activity?

---

## 🧠 Key Insights
- **Lunch and early evening hours (12 PM – 7 PM)** experience the highest order volumes.
- Certain menu categories consistently outperform others in total orders.
- A small group of menu items drives a large share of total demand.
- Very low order activity occurs late at night and early morning.

These insights can help:
- Optimize **staff scheduling**
- Improve **menu focus**
- Increase **operational efficiency**

---

## 🛠️ Tools & Technologies
- **SQL** – data querying, joins, aggregations, time analysis
- **Excel** – validation, pivot tables, charts, screenshots
- **GitHub** – version control and project documentation

---

## 📂 Project Structure
restaurant-orders-analysis/
│
├── sql/
│   ├── 01_top_selling_items.sql
│   ├── 02_category_analysis.sql
│   ├── 03_peak_hours.sql
│
├── screenshots/
│   ├── top_items_chart.png
│   ├── hourly_orders.png
│   ├── category_breakdown.png
│
└── README.md

---

## 📊 Visual Outputs
The repository includes:
- Top-selling menu items chart
- Hourly order trend analysis
- Category performance comparison

These visuals summarize findings clearly for **business and non-technical stakeholders**.

---

## 🚀 Business Value
This analysis enables restaurant owners and managers to:
- Focus on high-performing menu items
- Schedule staff based on real demand
- Reduce inefficiencies during low-traffic hours
- Make informed, data-backed operational decisions

---

## 👤 About Mambila Analytics
**Mambila Analytics** provides data analysis and business intelligence solutions for SMEs and growing businesses, turning raw data into actionable insights.

📩 Contact: *Available via GitHub Organization*

---
