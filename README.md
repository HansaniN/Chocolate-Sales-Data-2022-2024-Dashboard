# Corporate Sales Performance Dashboard (Excel)

An interactive Microsoft Excel dashboard designed to analyze and visualize global chocolate sales data, monitor key business KPIs, and uncover regional product performance trends. This project demonstrates an end-to-end Excel analytics workflow including data cleaning, transformation, KPI modeling, pivot-based aggregation, and interactive dashboard development.

![Dashboard Preview](Screenshot(705).png)


---

# 📊 Business Metrics & Features

### Dynamic KPI Monitoring
Track core business metrics in real time:
- **Total Revenue:** $19.79M
- **Total Boxes Shipped:** 540K
- **Unique Product Lines:** 22

### Interactive Filtering
Integrated **Year** and **Country** slicers allow users to dynamically filter the entire dashboard for focused analysis and faster business exploration.

### Sales Performance Analysis
Visualizes individual sales representative performance using optimized layouts and readable labeling techniques.

### Time-Series Trend Analysis
Tracks monthly and quarterly sales fluctuations to identify seasonality patterns and revenue trends over time.

### Product & Regional Insights
Highlights top-performing chocolate categories and geographic market contributions across:
- UK
- India
- Canada
- Australia
- USA
- New Zealand

---

# 🛠️ Data Cleaning & Engineering Process

Raw data is rarely analysis-ready. To improve model reliability, readability, and dashboard responsiveness, several transformation techniques were applied within Excel.

### 1. Primary Key Generation
Manually engineered a unique `Order_ID` column to maintain data integrity and enable accurate cross-referencing across pivot structures.

### 2. Date Transformation
Extracted `Month` values from raw date fields using Excel’s **Text-to-Columns** functionality, then converted numeric month values into readable month names to improve time-series analysis and chart readability.

### 3. String Manipulation Using Flash Fill
Extracted only the **First Names** of sales representatives using Excel Flash Fill. This optimized chart spacing and prevented label overlap within horizontal visualizations.

### 4. Pivot Data Modeling
Constructed structured intermediate pivot tables to aggregate large transactional datasets into efficient and responsive chart-ready data models.

---

# 📈 Dashboard Design Best Practices Applied

### Z-Pattern Layout
Positioned high-level KPIs at the top-left section to naturally guide user attention toward deeper analytical insights.

### Clutter Reduction
Removed unnecessary:
- Gridlines
- Chart borders
- Default pivot field buttons

This created a cleaner and more modern software-style dashboard interface.

### Visual Hierarchy & Typography
Applied strategic font sizing, weight variation, and spacing to establish a clear hierarchy between:
- Titles
- KPIs
- Labels
- Supporting metrics

### Consistent Color Strategy
Used a cohesive dark-themed color palette to improve readability and maintain professional visual consistency.

---

# 💡 Key Insights Derived

- Australia and the UK generated the highest overall sales revenue.
- Monthly revenue trends revealed noticeable seasonal fluctuations.
- A limited number of product categories contributed disproportionately to total revenue.
- Sales performance varied significantly between representatives and regions.

---

# 🧰 Excel Features & Skills Demonstrated

- Pivot Tables
- Pivot Charts
- Slicers
- KPI Card Design
- Data Cleaning
- Flash Fill
- Text-to-Columns
- Dashboard UI/UX Design
- Time-Series Analysis
- Interactive Reporting

---

# 📁 Repository Structure

```text
├── CS3.xlsx
├── image_e6cdb9.png
└── README.md
```

### Files Included

| File | Description |
|---|---|
| `CS3.xlsx` | Main Excel workbook containing raw data, pivot tables, calculations, and the final dashboard |
| `image_e6cdb9.png` | Dashboard preview screenshot |
| `README.md` | Project documentation |

---

# 🚀 How to Use the Dashboard

1. Download or clone this repository.
2. Open `CS3.xlsx` using Microsoft Excel (2019 or later recommended).
3. Enable editing/content if prompted.
4. Use the **Year** and **Country** slicers to interactively filter dashboard insights.

---

# 🎯 Project Objective

The goal of this project was to simulate a professional business intelligence reporting workflow entirely within Microsoft Excel while emphasizing:
- Data storytelling
- Dashboard usability
- Interactive analytics
- Clean visual design
- Business insight generation

---

# 📌 Author

Hansani Nawarathna

Aspiring Data Analyst | UI/UX Enthusiast | Excel Dashboard Developer
