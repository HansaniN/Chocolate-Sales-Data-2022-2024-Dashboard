# Corporate Sales Performance Dashboard (Excel)

An interactive Microsoft Excel dashboard designed to analyze and visualize global sales data, track key performance indicators (KPIs), and uncover regional product trends. This project demonstrates end-to-end data processing, from raw data cleaning to interactive data modeling and professional UI/UX design in Excel.

![Dashboard Preview](image_e6cdb9.png) *(Note: Replace this with your actual image path or GitHub URL once uploaded)*

## 📊 Business Metrics & Features
* **Dynamic KPIs:** Real-time tracking of Total Revenue ($19.79M), Total Boxes Shipped (540K), and Unique Product Lines (22).
* **Interactive Slicers:** Allows stakeholders to seamlessly filter the entire dashboard by **Year** and **Country** with a single click.
* **Sales Person Analysis:** Cleanly visualizes individual sales performance using optimized data labels.
* **Time-Series Insights:** Tracks sales fluctuations across different months and quarters to identify seasonal trends.
* **Product & Regional Breakdown:** Identifies top-performing chocolate categories and geographic market distributions (UK, India, Canada, Australia, USA, NZ).

## 🛠️ Data Cleaning & Engineering Process
Raw data is rarely analysis-ready. To maximize chart readability and model accuracy, the following data transformation techniques were applied within Excel:

1.  **Primary Key Generation:** Manually engineered a unique `Order_ID` column to ensure robust data integrity and precise cross-referencing.
2.  **Date Parsing:** Utilized the **Text-to-Columns** feature to extract and isolate `Month` values from standard date strings, enabling cleaner time-series aggregation.
3.  **String Manipulation (Flash Fill):** Extracted only the **First Names** of the sales representatives. This significantly optimized horizontal bar chart real estate, preventing text overlap and ensuring a clean visual layout.
4.  **Pivot Architecture:** Built structured intermediate pivot tables to aggregate multi-year transactional rows into responsive chart sources.

## 📈 Dashboard Design Best Practices Applied
* **Z-Pattern Layout:** Placed high-level aggregate KPIs at the top left, naturally guiding the viewer's eye down into granular visual trends.
* **Clutter Reduction:** Removed unnecessary gridlines, chart borders, and default field buttons to achieve a modern, software-like UI.
* **Strategic Typography:** Created a clear visual hierarchy using distinct font sizes and weights for titles, metrics, and labels.

## 📁 Repository Structure
* `CS3.xlsx`: The core Excel workbook containing the raw data, pivot tables, and final interactive dashboard.
* `image_e6cdb9.png`: Screenshot preview of the dashboard interface.
* `README.md`: Project documentation.

## 🚀 How to Interact with the Dashboard
1. Download or clone the `CS3.xlsx` file.
2. Open the file in Microsoft Excel (2019 or later recommended for full Slicer compatibility).
3. Ensure macros/content are enabled if prompted.
4. Use the **Year** and **Country** slicers on the left panel to dynamically filter and explore the sales metrics.
