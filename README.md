# 📦 Monthly Sales and Price Analysis | Power BI Dashboard

Welcome to the **Monthly Sales and Price Analysis** project! This interactive dashboard was built using **Power BI** to analyze a detailed dataset from a fictional retail supply chain. The goal is to extract actionable business insights and showcase how data visualization can support decision-making in sectors like food distribution, utilities, and transportation.

---

## 🔍 Project Objective

The main aim of this project is to explore monthly sales and pricing trends across several product categories and suppliers, while uncovering key metrics such as:

- Sales performance over time  
- Category-wise revenue contribution  
- Supplier impact on total revenue  
- Price fluctuations across months and products  
- Geographic distribution of goods sold  

This project can support inventory managers, financial analysts, and business executives in identifying trends, planning procurement, and optimizing pricing strategies.

---

## 🧾 Dataset Description

The dataset includes a rich collection of transaction-level details covering multiple locations, suppliers, and item categories. Key variables include:

- **Item Name**: Name of the product (e.g., Rice, Gas, Kerosene)  
- **Category**: Product classification (Food, Utility, Transport)  
- **Supplier**: Vendor or source of the product  
- **Month & Year**: Date of transaction  
- **Location**: Geographic location of the transaction (city)  
- **Unit Price (₦)**: Selling price per unit  
- **Quantity Sold**: Volume of units sold  
- **Total Sales (₦)**: Computed as Unit Price × Quantity  

---
![image](https://github.com/user-attachments/assets/95c709b2-f0ea-4a00-8c41-ca8ed3c13950)

---

## 📊 Dashboard Features

The Power BI dashboard is designed to deliver insight through simple, interactive visualizations:

- **Total Sales KPI**  
  Displays overall sales (₦34.15 million) across all categories and months.

- **Sales by Supplier**  
  A donut chart ranking supplier contribution to total revenue.

- **Sales by Category**  
  A clustered bar chart showing the revenue share of Food, Utility, and Transport items.

- **Average Unit Price Trends**  
  A multi-line chart tracking unit price changes per product over 12 months.

- **Monthly Sales by Item**  
  A stacked column chart displaying which items drive sales in each month.

- **Location Map**  
  A filled map showing where the highest quantity of goods are sold.

---

## Key Insights

### 1. Overall Sales
- **Total Sales**: ₦34.15 million

---

### 2. Sales by Supplier

| Supplier       | Total Sales (₦) | % of Total Revenue |
|----------------|------------------|---------------------|
| BulkTrader     | 8.51 M           | 24.93%              |
| Urban Goods    | 8.03 M           | 23.52%              |
| Jumia          | 6.77 M           | 19.82%              |
| Market Direct  | 5.46 M           | 15.75%              |
| AgroMart       | 5.38 M           | 15.75%              |

**Insight**: BulkTrader and Urban Goods together account for nearly **half of all revenue**.

---

### 3. Sales by Category

| Category  | Total Sales (₦) |
|-----------|------------------|
| Food      | ~18 M            |
| Utility   | ~10.8 M          |
| Transport | ~4.5 M           |

**Insight**: **Food dominates**, contributing over **50% of total sales**, followed by Utility and Transport.

---

### 4. Monthly Trends

- **Average Unit Price (₦)** fluctuates across months—no consistent upward or downward pattern.
- **Eggs** peak around **June–July**.
- **Cooking Gas, Kerosene, Fuel** see price spikes during **colder/drier months**.
- **January** is the strongest month in sales, followed by a **gradual decline** through December.
- Early months: **Beans** and **Bread** dominate.
- Later months: **Garri** and **Yam** increase in prominence.

---

### 5. Quantity Sold by Location

- **Top locations by quantity sold**:  
  1. Lagos  
  2. Kano  
  3. Abuja  
  4. Ibadan  

- **Regional patterns**:  
  - Coastal cities (e.g., **Port Harcourt**, **Lagos**) have strong Utility sales.  
  - Northern hubs (e.g., **Kano**) rely heavily on Food staples.

---

### 6. 💵 Top & Low Price Points

- **Highest unit price recorded**: ₦1,995.96 (Cooking Gas, **April 2024**)  
- **Lowest unit price recorded**: ₦106.74 (Transport item, **January 2024**)

---

## Methodology

1. **Data Cleaning & Transformation**  
   - Formatted date fields, corrected data types, and ensured consistent naming conventions.  
   - Derived `Total Sales` from price × quantity.

2. **Data Modeling in Power BI**  
   - Created a central fact table with dimensions for category, supplier, item, and time.  
   - Used DAX measures for KPIs and trend metrics.

3. **Visual Design & UX**  
   - Incorporated slicers for interactivity by month, category, location, and item.  
   - Used intuitive color schemes, tooltips, and drill-through capabilities.

---

## Tools & Technologies

- **Power BI Desktop** – Data modeling and dashboard design  
- **DAX (Data Analysis Expressions)** – For calculations and KPIs  
- **Excel / CSV** – For raw data import and preparation  
- **GitHub** – For version control and documentation

---



