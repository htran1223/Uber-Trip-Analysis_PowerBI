# Uber-Trip-Analysis_PowerBI
End-to-end analysis of Uber trip data using Power BI. Includes data cleaning, exploratory analysis, and interactive dashboards to reveal demand patterns, peak hours, and location trends.
# 🚖 Uber Trip Analysis (Power BI)

This project presents a comprehensive Uber Trip Analysis dashboard built using Microsoft Power BI. It analyzes trip bookings, revenue, distance, and time-based patterns to help stakeholders make **data-driven decisions** on pricing, operations, and customer experience.

---

## 🧠 Problem Statement
The goal of this dashboard is to gain valuable insights into Uber’s ride data to answer key questions such as:
- How many trips were booked in a given period?  
- What is the total and average revenue per trip?  
- How far and how long are customers traveling on average?  
- Which locations and vehicle types drive the most demand?  

---

## 📊 Key Performance Indicators (KPIs)
- **Total Bookings** – Number of trips booked  
- **Total Booking Value** – Total revenue generated  
- **Average Booking Value** – Revenue per trip  
- **Total Trip Distance** – Sum of all trip distances  
- **Average Trip Distance** – Distance per trip  
- **Average Trip Time** – Duration of trips  

---

## 📈 Dashboards & Visualizations

### 1. Overview Analysis
- Bookings by Payment Type (Card, Cash, Wallet, etc.)  
- Bookings by Trip Type (Day vs Night)  
- Total Bookings by Day (trend analysis)  
- Vehicle Type Analysis (UberX, Comfort, Black, XL, Green)  
- Location Analysis (Pickup/Drop-off, Farthest Trip, Most Frequent Points)  

**Screenshot:**  
![Overview Analysis](75071569-5ea1-4ad7-b9a5-999a05f38bdf.png)

---

### 2. Time Analysis
- **Pickup Time Analysis (10-min intervals)** – peak vs off-peak demand  
- **Day Name Analysis** – weekday vs weekend trends  
- **Heatmap by Hour & Day** – busiest hours across weekdays/weekends  

**Screenshot:**  
![Time Analysis](f239d926-cb82-4cb9-8447-b496ca60fafc.png)

---

### 3. Details Tab
- Grid table with Trip ID, Date, Vehicle, Payment Type, Distance, and Value  
- Drill-through functionality for granular analysis  
- Toggle between filtered data and full dataset  

**Screenshot:**  
![Details Tab](06a6ef9a-5846-4024-97fa-3e603a546e3b.png)

---

## 💾 Data Source
- Sample Uber trips dataset (CSV/Excel)  
- Includes fields: *Trip ID, Pickup Date/Time, Vehicle, Payment Type, Distance, Value, Pickup & Drop-off Location*  

---

## 🛠 Tools & Techniques
- **Power BI Desktop**  
- **Power Query** for data cleaning and transformation  
- **DAX** for dynamic measures (Total Sales, Avg Booking, Trip Distance, etc.)  
- **Bookmarks, Slicers, Tooltips** for enhanced interactivity  

---

## 👥 Intended Audience
- **Operations Managers** – optimize driver allocation  
- **Pricing Teams** – evaluate and refine pricing models  
- **Data Analysts** – explore booking patterns and trends  
- **Executives** – monitor key metrics for business performance  

---

## 🚀 How to Use
1. Clone this repository  
2. Open `Uber_Trip_Analysis.pbix` in Power BI Desktop  
3. Use slicers (Date, City, Vehicle Type) to filter the data  
4. Drill through to the **Details Tab** for record-level insights  

---

## 📌 Key Highlights
- Dynamic measure selector for KPI switching  
- Drill-through enabled for deeper exploration  
- Heatmap and time-based analysis for demand forecasting  
- Location-based insights for driver placement strategy  

---

## ⚠️ Note
This is a **sample project for learning and portfolio purposes**. Data does not represent actual Uber operations.

