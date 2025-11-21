# ✈️ AeroSpace Airlines Dashboard
**Advanced Tableau Project | Multi-Page Analytical Suite**

---

## 📌 Overview
This project is an end-to-end Airline Analytics solution built in Tableau, designed to help business stakeholders make data-driven decisions across operations, performance, geography, and time.

The dashboard highlights passenger trends, operational performance, airport activity, route insights, and overall airline efficiency using advanced KPIs, parameter-driven controls, interactive navigation, and storytelling-focused design.

---

## 📂 Project Structure
The analytics suite contains **4 dashboards**:

### 1️⃣ Overview Dashboard
Provides a high-level operational snapshot:
- **Total Passengers**
- **Total Flights**
- **Total Revenue**
- **Total Freight (lbs)**

Each KPI includes:
- **% Change vs Last Period** *(Calculated using LOOKUP with -1 offset to compare against the previous time period)*

**Key Visuals**
- Monthly Passenger Trend (Line Chart)
- Monthly Flights Performed (Bar Chart)
- Passengers by Airline (Bar Chart)
- Flights by Distance Range (Pie Chart)
- Average Load Factor Trend (Area Chart)

### Dashboard Preview  
![Overview Dashboard Preview](Overview_Dashboard.png)

---

### 2️⃣ Performance Analysis Dashboard
Focuses on operational efficiency and service quality:
- **Average Load Factor**
- **On-Time Performance** *(Based on Departures Scheduled vs Performed)*
- **Seat Utilization**
- **Flight Completion Rate**

**Key Visuals**
- Revenue, Cost & Profit Analysis  
  - Revenue & Cost → Stacked Bar Chart  
  - Profit → Line Chart
- Load Factor by Distance Range (Lollipop Chart)
- Passengers by Distance Range (Line Chart)
- Airline Performance Comparison (Table)

### Dashboard Preview  
![Performance Analysis Dashboard Preview](Performance_Analytics.png)

---

### 3️⃣ Geographical Analytics Dashboard
Highlights airport-level and route-level activity.

**KPIs**
- Total Origin Airports
- Total Destination Airports
- Total Routes
- Average Route Distance

The dashboard uses a **button-based dynamic navigation system** with 3 sections:

#### 🛫 Airports Section
- Top 10 Airports by Passenger Volume (Bar Chart)
- Airport Traffic Visualization (Bubble Chart)
- Airport Activity Details (Table)

#### 🗺️ States Section
- Passenger Volume by State (Bar)
- State Traffic Distribution (Top 8) – Pie Chart *(using Ramp-to-Ramp Time instead of Passengers)*

#### 🔁 Top Routes Section
- Top 15 Routes by Passenger Volume
- Route Performance Details (Table)

### Dashboard Preview  
![Geographical Analytics Dashboard Preview](Geographic_Analysis.png)

---

### 4️⃣ Time Series Dashboard
Designed for temporal analysis and forecasting.

**KPIs**
- Average Flight Distance
- Month-over-Month Growth    
- Average Monthly Flights
- Peak Month  

**Key Visuals**
- Multi-Metric Monthly Analysis (Combination Chart)
  - Load Factor & Passengers → Line Chart Chart  
  - Flights → Bar Chart
- Passenger Traffic Trend (Area Chart)
- Flights by Day of Week (Bar Chart)
- Quarterly Performance Summary (Table)

### Dashboard Preview  
![Time Series Dashboard Preview](Time_Series.png)

---

## 🎛️ Global Filters (Applied to All Dashboards)
Each dashboard includes a set of **global filters** that control every visual on the page:

- **Year**
- **Quarter**
- **Month**
- **WeekDay**
- **Flight Types**
- **Airline**  
- **Airport**
- **Distance Range**

These filters are configured as **Apply to Worksheets → All Using This Data Source**, ensuring that:
✔ All charts update dynamically  
✔ KPIs recalculate instantly  
✔ Cross-dashboard consistency is maintained  
✔ Users can slice & explore data at any level  

--- 

## 🧮 Key Calculated Fields
- % Change vs Last Period
- On-Time Performance
- Seat Utilization
- Flight Completion Rate
- Revenue
- Cost
- Profit
- Distance Range

---

## 🎨 Features & Techniques Used
- Global filters applied to all visuals
- Multi-dashboard navigation buttons
- Parameter controls for revenue & cost modeling
- Dynamic titles and KPI indicators
- Table calculations (LOOKUP, WINDOW_MAX, RUNNING_SUM)
- YoY & MoM analytics
- Dual-axis lines

---

## 🔗 Live Preview
([Live Dashboard](https://public.tableau.com/app/profile/shadan.sarfaraz/viz/AeroSpaceAirlines/Overview?publish=yes))

---

## 🧰 Tools & Tech Stack
- Tableau Desktop 2023+
- Excel/CSV Data Source
- Tableau Data Model & Custom Calculations

---

## 🚀 Key Insights
The dashboard enables analysis of:
- Passenger trends
- Airline performance
- Route profitability
- Airport activity
- Geographic distribution
- Time-based growth patterns

---

## 🏁 Conclusion
This dashboard transforms complex airline data into clear, actionable insights through advanced KPIs, interactive filters, and multi-page analytics. It enables quick understanding of performance, trends, routes, and geographic patterns, helping stakeholders make smarter, data-driven decisions.

---

## 👤 Author
**Shadan Tech**   
_Data Analyst_
🔗 [LinkedIn Profile](http://www.linkedin.com/in/shadantech)  
🔗 [Tableau Public Profile](https://public.tableau.com/app/profile/shadan.sarfaraz/vizzes)
🔗 [Newsletter](https://shadantech.substack.com/)

---

## ⭐ Show Your Support
If you found this project insightful, give it a **⭐ Star** on GitHub — it helps others discover it too!  
Connect on **LinkedIn** for more Power BI, Tableau, and Data Analytics projects.