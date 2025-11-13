# 🚴‍♀️ Bike Sales Analysis Dashboard – End-to-End Power BI Project  

## 💭 Why I Chose This Dataset  
The **Bike Sales dataset** represents a realistic retail analytics scenario, helping analyze customer demographics, product performance, sales trends, and returns.  
This project was built **entirely in Power BI** — including data cleaning, transformation, modeling, and dashboard creation — to showcase modern BI capabilities from start to finish.

---

## ⚔️ Struggles I Faced  

### 🔧 Data Cleaning & Transformation in Power Query  
All preprocessing was handled in **Power Query** inside Power BI.  
I resolved issues like incorrect data types, missing values, inconsistent formats, and redundant fields using Power Query transformations.

**Key steps:**
- Converted fields into correct data types (Date, Number, Text)  
- Replaced nulls and blanks with appropriate values  
- Used conditional columns to fix inconsistent attributes  
- Appended multi-year sales tables into a unified dataset  
- Standardized column naming for modeling consistency  
- Validated data using Column Profiling tools  

This ensured a **clean, optimized dataset** ready for modeling.

---

## 💡 Power BI Challenges  
- Designing a proper **Star Schema** data model  
- Creating a **dynamic Date Table** for time intelligence  
- Implementing **sync slicers** across all dashboards  
- Using **drill-through** and **bookmarks** for smooth navigation  
- Designing **four dashboards** that are visually consistent and performance-optimized  

---

## 💼 Business Problem  
The business needed to understand:  
- Which **regions, countries, and continents** drive the most profit?  
- What is the effect of **product returns** on total sales?  
- Which **products** perform best and which result in the most returns?  
- What do **customer behaviors** like rebuy rates reveal about loyalty and retention?  

This Power BI project delivers actionable insights to support data-driven decisions.

---

## 🎯 Project Objectives  
- Clean and transform raw datasets using **Power Query**  
- Build a robust **data model** with relationships  
- Create **four analytical dashboards** for Sales, Geography, Returns, and Customer Insights  
- Use **DAX** to build KPIs and advanced calculations (MTD, growth, ratios)  
- Enable intuitive navigation through **sync slicers**, bookmarks, and drill-through  

---

## ⚙️ Tech Stack  
| Tool / Technology | Purpose |
|-------------------|----------|
| 📊 **Power BI Desktop** | Cleaning, modeling, and dashboard creation |
| 🔧 **Power Query** | Data transformation and preparation |
| 🧠 **DAX** | KPI creation & advanced analytics |
| 🔗 **Star Schema Modeling** | Efficient structured relationships |

---

## 🧾 Dataset  
The dataset includes:  
- 👥 Customer demographics  
- 🚲 Product information  
- 💸 Sales and returns data  
- 🌍 Geographic attributes  
- 📆 Time-based components  

## 📂 Explore Full Projects  

**🚴‍♀️ Power BI Dashboard:**[Bike Sales Analysis](https://app.powerbi.com/view?r=eyJrIjoiMWY3NGM3MDgtZDQ0Yy00NWU5LTg3YjYtZjE0MTZmMTY5MDgzIiwidCI6ImRlMzJkOTNlLTRlMjgtNDhlNS1hMDI3LTExOTQ2NDAzZTNhYyJ9)  

**Google Drive Dataset:** [Click to Access Dataset](https://drive.google.com/drive/folders/1GMzn-fdT5zsWwqcGjhEcbs-HNXMUM-Li?usp=drive_link) 
---

---

## 🗂️ Data Modeling  

- **Fact Table:** Sales  
- **Dimensions:** Customers, Products, Returns, Territories, Categories, Subcategories, Date  
- Built using a **Star Schema**  

**📸 Data Modeling Preview:**  
![Data Modeling](https://github.com/lubhanigola/Bike_Sales_Analysis/blob/main/Screenshots/Data%20Modeling.png)  
---

# ✨ Dashboards  

---

## 🧭 1. Performance Overview Dashboard  

**KPIs:**  
- Total Sales – **$24.94M**  
- Total Orders – **56K**  
- Quantity Sold – **84K**  
- Net Profit – **$10.46M**

**Visuals & Insights:**  
- 📊 **Bar Chart – Sales by Country:** Reveals top-performing countries in terms of total revenue.  
- 🍩 **Donut Chart – Profit by Continent:** Highlights that **North America** contributes the highest profit share.  
- 📈 **Line Chart – Quarterly Cost:** Tracks fluctuations in cost and identifies low-margin quarters.  
- 🎯 **Sync Slicers – Year, Month, Category:** Allow quick comparison between time periods and categories.  

**📸 Dashboard Preview:**  
![Performance Overview](https://github.com/lubhanigola/Bike_Sales_Analysis/blob/main/Screenshots/Performance%20Overview.png)  
---

## 🗺️ 2. Map Visual Dashboard  

**Key Features & Insights:**  
- 🗺️ **Interactive Map Visual:** Visualizes country-wise sales density across continents.  
- 💬 **Drill-through (Sales by Country):** Lets you dive deeper into specific country performance.  
- 🔄 **Bookmark Navigation:** Enhances dashboard interactivity for region-based analysis.  
- 🎛️ **Sync Slicers:** Seamlessly filter all visuals by time or geography.  

**📸 Dashboard Preview:**  
![Map Visual](https://github.com/lubhanigola/Bike_Sales_Analysis/blob/main/Screenshots/Map%20Visual.png)  
---

## 📦 3. Product & Returns Insights Dashboard  

**KPIs:**  
- Total Returns – **1,809**  
- Net Sales – **$24.15M**  
- Distinct Products – **130**  
- Return Rate – **3.23%**

**Visuals & Insights:**  
- 🔽 **Funnel Chart – Products Sold by Country:** Displays sales conversion rate across different countries.  
- 📊 **Column Chart – Top 5 Products by Return Quantity:** Identifies the most frequently returned products.  
- 📆 **Quarterly Return Rate:** Shows product performance trends over quarters to track quality issues.  
- 🎚️ **Sync Slicers – Region, Product Size, Subcategory:** Enable quick segmentation and filtering.  

**📸 Dashboard Preview:**  
![Product & Returns Insights](https://github.com/lubhanigola/Bike_Sales_Analysis/blob/main/Screenshots/Products%20%26%20Returns%20Insights.png)  
---

## 👥 4. Customer Insights Dashboard  

**KPIs:**  
- Distinct Customers – **17K**  
- Rebuy Rate – **86.64%**  
- Avg Spent – **$1.43K**  
- Avg Orders per Customer – **3.22**

**Visuals & Insights:**  
- 🌡️ **Heatmap – Monthly Return Rate:** Highlights seasonal spikes in product returns.  
- 🎯 **Gauge Chart – Target vs Current Customers:** Measures customer growth against set goals.  
- 📊 **Clustered Column Chart – Sales vs Returns by Continent:** Compares revenue with associated returns region-wise.  
- 📋 **Table – Monthly Rebuy Rate:** Tracks customer loyalty through repeat purchases.  
- ⏳ **MTD Customer Growth (DAX Measure):** Shows month-to-date progress in customer acquisition.  
- 🔄 **Sync Slicers – Year, Country:** Simplifies cross-year and country-specific analysis.  

**📸 Dashboard Preview:**  
![Customer Insights](https://github.com/lubhanigola/Bike_Sales_Analysis/blob/main/Screenshots/Customer%20Insight.png)  
---

## 📈 Key Insights  
- 🌍 **Pacific** leads in sales contribution  
- 💰 **Net Profit:** $10.46M, **Net Sales:** 24.94M  
- 🔁 **Return Rate:** 3.23% — signals quality review need  
- 🧍‍♀️ **Rebuy Rate:** 86.64% — strong customer loyalty  
- 🚲 **Top Performer:** Mountain 200 Black series  

---

## 🧠 Learnings & Takeaways  
- Complete understanding of *Power Query → Star Schema → DAX → Visualization* workflow  
- Deepened skills in **data modeling, DAX optimization, and dashboard design**  
- Mastered sync slicers, bookmarks, and drill-through actions  
- Built a fully interactive multi-page analytical solution  

---
