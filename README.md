# Task-2-Data-Visualization-and-Storytelling-Sales-Performance-Overview-Dashboard

# 📊 Superstore Sales Analytics Dashboard (Power BI)

This project provides an interactive and visually rich Power BI dashboard designed to analyze and interpret sales performance, customer behavior, product trends, and regional insights from the classic Superstore dataset.

---

## 📁 Dataset Used

- **Source:** Sample - Superstore.csv
- **Fields Included:** Order Date, Ship Date, Customer Info, Product Info, Sales, Profit, Discount, Shipping Mode, Region, State, City, Category, Sub-Category, etc.

---

## 🎯 Dashboard Objectives

- Track and monitor **sales performance**
- Evaluate **profitability** and **profit margins**
- Analyze **customer segments and product categories**
- Visualize **shipping trends** and delivery efficiency
- Identify **top products and customers**
- Enable **geographic** and **time-based** filtering for granular analysis

---

## 🛠️ Data Model (Star Schema)

- **Fact Table:** FactSales
- **Dimension Tables:**
  - DimCustomer
  - DimProduct
  - DimLocation
  - DimDate

### 🔗 Key Relationships
| Fact Table Column | Dimension Table | Key |
|-------------------|------------------|-----|
| Customer ID       | DimCustomer      | Customer ID |
| Product ID        | DimProduct       | Product ID  |
| Postal Code       | DimLocation      | Postal Code |
| Order Date        | DimDate          | Date        |

--- 


## 📌 Filters / Slicers
- Date Range (Order Date)
- Region
- Category
- Customer Segment
- Sub-Category

---

## Live Demo

Explore the live project here: [Sales Performance Overview Dashboard Project Report](https://app.powerbi.com/view?r=eyJrIjoiNzFlMWQzNzUtNGJhOS00ZDFmLWIwNTQtNjE4MDcyMDQ1N2QwIiwidCI6ImJkNmQzYjM4LWE4MTktNGYyZS1iODhmLThiYzVkNGM0MDEyOSJ9)

## 💡 Usage

1. Open Power BI Desktop.
2. Load the `Sample - Superstore.csv` file.
3. Apply transformations (split into fact and dimension tables if needed).
4. Create DAX measures for KPIs and visuals.
5. Build dashboard using recommended visuals above.
6. Use slicers to interactively explore the data.

---

## Copyright

© 2025 Sales Performance Overview Dashboard Project. All rights reserved.

This project and its contents are the intellectual property of the creators. Unauthorized reproduction, distribution, or use of any part of this project without explicit permission is prohibited.


