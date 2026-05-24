# 🍫 Chocolate Sales Performance Dashboard (Excel)

An interactive Microsoft Excel dashboard designed to analyze, visualize, and monitor global chocolate sales performance across multiple countries, products, and sales representatives.

This project demonstrates an end-to-end Excel analytics workflow — transforming raw transactional data into a clean, structured, and interactive business intelligence solution through data cleaning, transformation, Pivot Table modeling, KPI engineering, and dashboard UI/UX design.

---

# 📊 Dashboard Preview

![Dashboard Screenshot](Ch_Dashboard.png)

---

# 📌 Business Problem

The goal of this project was to design a structured analytical dashboard that enables stakeholders to:

- Monitor overall sales performance across regions
- Identify top-performing products and countries
- Track shipment and revenue trends over time
- Evaluate salesperson contribution to total revenue
- Enable fast, interactive decision-making using slicers

---

# 🚀 Key Features & Functionality

## 📈 KPI Summary
The dashboard dynamically tracks core business KPIs:

- **Total Revenue:** $19.79M  
- **Total Boxes Shipped:** 540K+  
- **Top Performing Product**  
- **Top Performing Salesperson**  
- **Top Revenue-Contributing Country**

---

## 🎛️ Interactive Filtering (Slicers)

The dashboard includes fully dynamic slicers for:

- Year (2022–2024)
- Month
- Country

These enable real-time filtering and instant insight generation across all visuals.

---

## 🌍 Regional Performance Analysis

Sales performance is analyzed across key global markets:

- Australia
- Canada
- India
- New Zealand
- United Kingdom
- United States

This helps identify regional demand strength and revenue concentration patterns.

---

## 🏆 Product & Salesperson Insights

The dashboard highlights performance rankings for:

- Best-selling chocolate products
- Highest revenue-generating sales representatives
- Product-level contribution to overall sales

Top products identified include:
- Smooth Silky Salty
- Raspberry Choco
- Milk Choco

---

# 🛠️ Data Cleaning & Transformation Process

Raw transactional data was transformed into an analytics-ready dataset using Excel:

---

## 1️⃣ Primary Key Creation (`Order_ID`)
A unique sequential `Order_ID` column was manually created to:
- Ensure data integrity
- Support structured aggregation in Pivot Tables
- Prevent duplication errors during analysis

---

## 2️⃣ Date Transformation (Text to Columns)
Month values were extracted from raw date fields using **Text-to-Columns**, then converted into readable month names.

This improved:
- Time-series clarity
- Chart readability
- Dashboard usability

---

## 3️⃣ Text Optimization (Flash Fill)
Used Excel Flash Fill to extract first names from salesperson full names.

Benefits:
- Cleaner labels
- Improved dashboard readability
- Reduced visual clutter in charts

---

## 4️⃣ Pivot Table Modeling
Built structured Pivot Tables to:
- Aggregate sales data
- Power dashboard visuals
- Enable slicer-driven interactivity

---

# 📈 Design & UX Principles Applied

- Clean KPI-first layout for executive readability
- Removed gridlines and visual noise
- Consistent dark theme for professional BI look
- Balanced spacing for better visual hierarchy
- Optimized chart labeling for clarity

---

# 💡 Key Insights

- Australia emerged as the top revenue-generating country
- Premium chocolate products outperformed standard variants
- Sales distribution shows stable year-over-year growth (2022–2024)
- A small number of products contribute to a large share of revenue

---

# 🧰 Tools & Skills Demonstrated

- Microsoft Excel
- Pivot Tables & Pivot Charts
- Data Cleaning & Transformation
- KPI Design
- Dashboard Development
- Data Visualization
- Business Intelligence Reporting
- Flash Fill & Text-to-Columns

---

# 📚 Dataset Source

This project uses the publicly available dataset from Kaggle:

👉 https://www.kaggle.com/datasets/saidaminsaidaxmadov/chocolate-sales

The dataset contains:
- Salesperson
- Country
- Product
- Date
- Revenue
- Boxes Shipped

---

# 📂 Project Structure

```
📁 Chocolate-Sales-Dashboard
│
├── CS3.xlsx
├── Ch_Dashboard.png
└── README.md
```

---

# 🚀 How to Use

1. Clone or download this repository
2. Open `CS3.xlsx` in Microsoft Excel (2019+ recommended)
3. Enable editing/content if prompted
4. Use slicers (Year, Month, Country) to explore insights

---

# 🎯 Project Objective

This project simulates a real-world Business Intelligence workflow in Excel by focusing on:

- Interactive reporting
- Clean data modeling
- Visual storytelling
- Executive-level dashboard design
- Analytical thinking

---

# 📌 Author

**Hansani Nawarathna**  
Aspiring Data Analyst | Excel Dashboard Developer | UI/UX Enthusiast
