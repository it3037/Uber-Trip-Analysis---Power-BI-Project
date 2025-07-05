# 🚖 Uber Trip Analysis - Power BI Project

## 📌 Business Requirement

Analyze Uber trip data using Power BI to gain insights into booking trends, revenue, trip efficiency, and location-based patterns. The dashboards help stakeholders make data-driven decisions.

---

## 📊 Dashboard 1: Overview Analysis

### 🎯 KPIs:
1. **Total Bookings** – Number of trips over a period  
2. **Total Booking Value** – Total revenue from all bookings  
3. **Average Booking Value** – Revenue per booking  
4. **Total Trip Distance** – Sum of trip distances  
5. **Average Trip Distance** – Average distance per trip  
6. **Average Trip Time** – Average trip duration  

### ✅ Expected Outcomes:
- Identify trends in ride bookings and revenue  
- Analyze trip efficiency by distance and time  
- Compare booking patterns across periods  
- Provide insights to optimize pricing and satisfaction  

---

## 📈 Charts and Visuals

### 📌 Measure Selector:
- Total Bookings  
- Total Booking Value  
- Total Trip Distance  

### 📌 Analysis By:
- **Payment Type** (Card, Cash, Wallet)  
- **Trip Type** (Day/Night)  

### 📌 Enhancements:
- Dynamic Title (changes based on selected measure)  
- Slicers for Date, City  
- Tooltips (e.g., Avg Booking Value, Trip Distance)  

---

## 🚗 Vehicle Type Analysis (Grid View)

- KPIs by Vehicle Type:
  - Total Bookings  
  - Total Booking Value  
  - Avg Booking Value  
  - Total Trip Distance  
- Conditional formatting  
- Sorting & filtering enabled  

---

## 📅 Total Bookings by Day

- Detect daily fluctuations  
- Identify peak vs off-peak days  
- Measure effects of holidays and events  
- Plan resources and pricing accordingly  

---

## 📍 Location Analysis

- **Most Frequent Pickup Point**  
- **Most Frequent Drop-off Point** (using inactive relationship)  
- **Farthest Trip** (longest distance)  
- **Top 5 Locations by Booking Count**  
- **Most Preferred Vehicle by Pickup Location**

---

## 🧩 Dashboard Enhancements

- 📑 **Bookmark for Data Details**
  - Show KPI explanations, source info, and tables used  
- 🧹 **Clear Slicer Button**
  - One-click filter reset  
- 📥 **Download Raw Data Button**
  - Export CSV/Excel using Power BI or Power Automate  

---

## 🕒 Dashboard 2: Time Analysis

Understand trip patterns over time for better operations and pricing.

### 🔄 Global Dynamic Measure (filters all charts):
- Total Bookings  
- Total Booking Value  
- Total Trip Distance  

### ⏱ Visualizations:
- Area Chart by 10-minute intervals  
- Line Chart by Day Name (Mon–Sun)  
- Heatmap (Matrix) by Hour × Day of Week  

---

## 📋 Dashboard 3: Details Tab

Explore granular trip-level data with drill-through features.

- Grid table with essential fields  
- Right-click visuals to drill-through  
- Bookmark toggle to view full dataset  

---

## 🛠 Tools Used

- Power BI (DAX, visuals, modeling)  
- Excel (cleaning, transformation)  
- Power Automate (optional for exports)  
- Power BI Bookmarks, Buttons, Tooltips  

---

## 🚀 Final Outcome

- Identify trends by time, location, and vehicle type  
- Optimize revenue, driver assignment, and pricing  
- Deliver interactive dashboards for data-driven decisions
