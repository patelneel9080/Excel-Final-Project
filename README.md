# 📊 Company Sales Dashboard - Excel Project

## 📁 Dataset
- **Source:** `Final Project Dataset` sheet
- **Records:** 200+ customer transaction records
- **Data Includes:** Customer names, product categories, regions, sales, quantities, payment methods, dates, and more.

---

## 🎯 Objective
Build a full-fledged Excel-based analysis and reporting solution to:
- Analyze customer transactions
- Identify key insights and patterns
- Create interactive visualizations
- Build a dynamic sales dashboard

---

## 📌 Key Features & Implemented Concepts

### 🗓️ Date & Time Functions
- **NOW(), TODAY(), DATEDIF(), EOMONTH()** used to:
  - Create timestamps
  - Track transaction durations
  - Handle monthly comparisons

### 🔍 FILTER Function
- Used to return multiple customer or product names based on logic conditions like high sales, repeated purchases, etc.

### 🎨 Conditional Formatting
- Icons and Arrows to indicate:
  - Monthly growth
  - KPI indicators
  - Top 10 customers and high-value sales

### 🕒 Timestamp Creation
- Used `NOW()` with iterative calculations to capture action times in dynamic reports.

### 🧠 WHAT-IF Analysis
- **Scenario Manager:** Simulated changes in customer demand or sales price.
- **Goal Seek:** Used to find required sales quantity for a target revenue.

### 📈 Regression Analysis
- **Linear Regression** via Data Analysis Toolpak:
  - Analyzed relationship between sales and profit
  - Predicted outcomes for future planning

### 📊 GroupBy Analysis (via formulas)
- Identified **High-Value Customers** using:
  - `INDEX()`
  - `MATCH()`
  - `SUMIF()`
  - `LARGE()` with custom logic

### 📌 Advanced Excel Tools
- Pivot Tables & Pivot Charts for:
  - Sales by Region, Category, Month
  - Customer Segmentation
  - Payment Method Distribution
- Slicers and Timelines for interactivity
- 3D Pie & Doughnut Charts for aesthetic data storytelling

### 🛍️ Product Frequency & Abbreviations
- Used formulas to find:
  - Most frequently purchased products
  - Repeating customer names
  - Created abbreviations using `LEFT()`, `MID()`, `TEXT()`

### 📋 List Comparison
- Compared two lists (e.g., year-wise customer lists) to extract:
  - Common names
  - Unique customers in 2024 vs 2025

---

## 📌 Dashboard Highlights

- **Total Revenue:** ₹2,29,192.47
- **Top Region:** East
- **Top Product:** Bookshelf
- **Top 5 Customers:** Mark Carter, Edward Mitchell, etc.
- **Category Wise Sales & Quantity:** Radar and Bar charts
- **Month-wise Performance:** Full sales trend
- **Payment Methods:** Visual donut chart
- **Sales by Region:** 3D pie visualization

---

## 📁 Workbook Structure

| Sheet Name     | Purpose                                      |
|----------------|----------------------------------------------|
| Raw Data       | Cleaned dataset with timestamp               |
| Analysis       | Applied functions, filters, and groupings    |
| Visualizations | Charts, metrics, and summarized visuals      |
| Dashboard      | Interactive KPI dashboard with slicers       |

---

## 📌 Deliverables

✅ A fully structured Excel workbook with:
- Clean raw data
- Analytical breakdown
- KPI dashboard
- Interactive filters
- Visual storytelling

---

## 🔚 Summary Insights

- Strongest market: **East Region**
- High-value customers drove ~30% of revenue
- **Bookshelf** topped product sales
- Credit Cards dominated payment methods (27%)
- Month of **April** had highest sales
- Dashboard enabled real-time slicing by category, segment, region, and time

---

## 🛠 Tools Used

- **Microsoft Excel** (Pivot Table, Slicer, Timeline, Data Analysis Toolpak)
- **Formulas:** `SUMIF`, `INDEX`, `MATCH`, `FILTER`, `IF`, `DATEDIF`, `TEXT`, etc.
- **Visualization:** Pivot Charts, Pie, Bar, Radar, Line, Donut
- **Data Tools:** What-If Analysis, Goal Seek, Scenario Manager

---

## ✨ ScreenShot
<img width="1902" height="756" alt="image" src="https://github.com/user-attachments/assets/f21ab23c-c078-4821-b90e-72a76c898de3" />


