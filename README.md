
# 📊 Power BI Project: AdventureWorks Sales & Returns Dashboard

## 📝 Overview

This Power BI project explores the **AdventureWorks dataset**, focusing on sales, returns, products, customers, and territories. The goal is to derive actionable business insights through data cleaning, modeling, and rich interactive visualizations.

---

## 📁 Project Structure

```
AdventureWorks-PowerBI/
│
├── AdventureWorksDashboard.pbix       # Main Power BI report file
├── Screenshots/
│   ├── overview_page.png
│   ├── map_page.png
│   ├── product_page.png
│   └── customer_page.png
└── README.md
```

---

## 🎯 Objectives

- Clean and transform raw sales and return data
- Build a data model with proper relationships
- Create calculated columns and DAX measures
- Develop an interactive dashboard with slicers, tooltips, and drillthroughs
- Analyze KPIs like revenue, profit, return rate, and customer insights

---

## 🧾 Data Model

- **Fact Tables**:
  - `Sales`
  - `Returns`

- **Lookup Tables**:
  - `Customer`
  - `Territory`
  - `Product`
  - `Calendar`
  - `Category` & `Subcategory`

The model was built using Power Query for transformations and Power BI’s relationship view to link fact and dimension tables.

---

## 🧮 Key Metrics & DAX

Custom **DAX measures** and **calculated columns** were used for:
- Total Revenue
- Total Orders
- Profit
- Return Rate
- Monthly Revenue, Orders, and Profit

---

## 📊 Dashboard Pages

### 📌 **Page 1: Overview**
- High-level KPIs: Total Revenue, Orders, Profit, Return Rate
- Category-wise bar chart
- Top 100 Products by Revenue (Line Chart)
- Monthly, Weekly, and Yearly tooltips
- Well-formatted card visuals for monthly metrics
- Navigation buttons for user-friendly experience

### 🌍 **Page 2: Geographic Insights**
- Bubble map showing total orders by continent
- Interactive slicers for deep-dives

### 📦 **Page 3: Product Details**
- Drillthrough from Top 100 Products (Page 1)
- Detailed breakdown of individual product performance
- Navigation buttons to jump between views

### 👥 **Page 4: Customer Insights**
- Line chart: Revenue per customer over time
- Donut chart: Orders by income level & occupation
- Top 10 customers table with year filter
- Revenue by customer category and sliceable comparisons

---

## 🧰 Features & Techniques Used

- Power Query for data cleaning
- Relationships and star schema modeling
- Calculated columns & DAX measures
- Drillthrough & tooltips
- Slicers (Year, Category, Continent, Customer Group)
- Navigation bar & formatted buttons
- Clean color formatting for all visuals

---

## 🖼️ Preview

Screenshots of each report page are available in the `Screenshots/` folder.

---

## ✅ What's Included

- ✅ Fully interactive Power BI file (`.pbix`)
- ✅ Screenshots of dashboard pages
- ✅ This README documentation

---

## 💡 Suggestions (Optional But Good to Have)

If you're planning to share this online (GitHub or portfolio), consider:
- Adding a short Loom or YouTube video demo walkthrough (2–3 mins)
- Exporting PDF versions of each page for offline viewing
- Including a brief write-up on project learnings

---

## 📬 Contact

**Author**: *[Your Name]*  
**Email**: *[your.email@example.com]*  
**LinkedIn**: *[linkedin.com/in/yourprofile]*

