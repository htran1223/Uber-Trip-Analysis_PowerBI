# Uber-Trip-Analysis_PowerBI
End-to-end analysis of Uber trip data using Power BI. Includes data cleaning, exploratory analysis, and interactive dashboards to reveal demand patterns, peak hours, and location trends.
#  Uber Trip Analysis (Power BI)

This project delivers a **comprehensive analytics dashboard** that explores Uber ride data using **Microsoft Power BI**. The dashboard provides insights into **trip demand, revenue generation, customer behavior, and operational efficiency**.  

Through interactive visualizations, advanced **DAX measures**, and drill-through functionality, stakeholders can identify patterns, optimize pricing strategies, and make **data-driven decisions** that improve both customer experience and business performance.  

---

##  Problem Statement
In the ride-hailing industry, companies like Uber manage **millions of trips daily**, generating vast amounts of operational data. To remain competitive, Uber must continuously answer critical questions:  

- How many trips are being booked across time periods, cities, and customer segments?  
- Which **payment methods and trip types** (day vs night) dominate customer behavior?  
- How do **vehicle categories** (UberX, Comfort, Black, etc.) contribute to revenue?  
- What are the **most common pickup and drop-off locations**?  
- How do trip **distance and time** impact efficiency and profitability?  

The purpose of this dashboard is to consolidate raw trip data into **meaningful business intelligence**.  

---

##  Business Objectives
✔ Identify **trends** in ride bookings and revenue generation  
✔ Analyze **trip efficiency** (distance and duration vs. revenue)  
✔ Compare booking values and demand patterns across **time and geography**  
✔ Optimize **pricing models** and improve customer satisfaction  
✔ Provide **location-based insights** to guide driver allocation strategies  

---

##  Key Performance Indicators (KPIs)
- **Total Bookings** – Total number of trips completed  
- **Total Booking Value** – Total revenue earned  
- **Average Booking Value** – Avg. revenue per trip  
- **Total Trip Distance** – Aggregate miles traveled  
- **Average Trip Distance** – Avg. distance per ride  
- **Average Trip Time** – Avg. trip duration in minutes  

---

## 📈 Dashboards & Visualizations

### 1. Overview Analysis
Provides a high-level **snapshot of business performance**.  

- **Bookings by Payment Type** (Uber Pay, Cash, Wallets)  
- **Day vs Night Trip Analysis** (demand segmentation)  
- **Bookings Trend by Day** (seasonality & daily fluctuations)  
- **Vehicle Type Analysis** (UberX vs Comfort vs Premium categories)  
- **Location Analysis**: most frequent pickup/drop-off, farthest trip, preferred vehicle type by area  


<img width="1206" height="679" alt="Screenshot 2025-08-26 143017" src="https://github.com/user-attachments/assets/38c6b710-c1b3-4246-b407-d940f684ed85" />


---

### 2. Time Analysis
Reveals how **demand fluctuates across hours, days, and weeks**.  

- **Pickup Time (10-min intervals)** → detects peak/off-peak hours  
- **Day Name Analysis** → weekday vs weekend ride patterns  
- **Hourly Heatmap** → busiest time slots segmented by weekday  

 
<img width="1205" height="687" alt="Screenshot 2025-08-26 143046" src="https://github.com/user-attachments/assets/5d1006b9-8c8d-4454-94da-b8ebd60927ce" />


---

### 3. Details Tab
A drill-through view for **record-level exploration**.  

- Interactive grid with: Trip ID, Date, Vehicle, Payment Type, Distance, Value, Pickup & Drop-off Location  
- Drill-through from any visual to see detailed records  
- Toggle between **filtered data** and **entire dataset**  

 
<img width="1221" height="690" alt="Screenshot 2025-08-26 143055" src="https://github.com/user-attachments/assets/edd4923f-b103-47d0-95da-60b8e4b90215" />


---

##  Data Source
- **Sample Uber Trips Dataset** (Excel/CSV format)  
- ~150K+ rows of data including:  
  *Trip ID, Pickup Date/Time, Vehicle Type, Payment Method, Distance, Value, Pickup & Drop-off Location, Trip Duration*  

---

##  Tools & Techniques
- **Microsoft Power BI Desktop** – visualization and modeling  
- **Power Query (ETL)** – data cleaning and transformation  
- **DAX Measures** – business logic and KPI calculation  
- **Bookmarks & Buttons** – improved user navigation (clear filters, data details view)  
- **Conditional Formatting** – highlight high/low values in grid tables  
- **Drill-through functionality** – deep dive into trip details  

---

##  Sample DAX Measures
```DAX
-- Total Revenue
Total Booking Value = SUM(Trips[Booking_Value])

-- Average Revenue per Trip
Avg Booking Value = DIVIDE([Total Booking Value], [Total Bookings])

-- Distance Efficiency
Avg Trip Distance = AVERAGE(Trips[Trip_Distance])

-- Profitability Measure
Operating Margin = DIVIDE([Total Booking Value] - [Operational Costs], [Total Booking Value])
