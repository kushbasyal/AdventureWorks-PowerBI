
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

Screenshots of each report page are available in the [Screenshots](./Screenshots/) folder.

---

## ✅ What's Included

- ✅ Fully interactive Power BI file [AdventuresData.pbix](./AdventuresData.pbix)
- ✅ Screenshots of dashboard pages
- ✅ This README documentation

---

## 📌 Conclusion

This Power BI project showcases the end-to-end process of building an interactive business intelligence dashboard using the AdventureWorks dataset. From data cleaning and transformation in Power Query to designing meaningful visualizations using DAX measures, tooltips, drillthroughs, and slicers, the report demonstrates practical skills in data modeling and storytelling. Each page is crafted with usability and insights in mind—empowering users to explore sales trends, returns, product performance, and customer behavior interactively. 
