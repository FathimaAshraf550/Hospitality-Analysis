# 🏨 AtliQ Grands - Hospitality Analysis Dashboard

A data analytics project focused on helping **AtliQ Grands**, a luxury hotel chain, regain its market share and revenue through **data-driven insights**.  
The project involves end-to-end data analysis — from data transformation and modeling to visualization in **Power BI**.

---

## 🧩 Problem Statement

**AtliQ Grands**, a five-star hotel chain across India, has been losing its market share and revenue due to increased competition and ineffective management decisions.  
To address this, the company decided to incorporate **Business and Data Intelligence** to improve decision-making.

---

## 🎯 Objectives

- Develop business metrics based on stakeholder requirements  
- Design dashboards aligned with mock-ups  
- Generate additional insights beyond the given metric list  

---

## 🛠️ Solution Approach

### 1. 📥 Data Collection
Data was sourced from multiple CSV files:
- `dim_date.csv`
- `dim_hotels.csv`
- `dim_rooms.csv`
- `fact_bookings.csv`
- `fact_aggregated_bookings.csv`

---

### 2. 🧹 Data Transformation
Performed in **Power Query**:
- Removed nulls and duplicates  
- Standardized data formats  
- Merged and appended tables for consolidated analysis  

---

### 3. 🧠 Data Modeling
Built a **Star Schema** model to ensure optimized performance and easy DAX calculation.

**Dimension Tables:**
- `dim_hotels`: Hotel details (property name, city, category)  
- `dim_rooms`: Room details (room class)  
- `dim_date`: Date attributes (day type, month, week number)  

**Fact Tables:**
- `fact_bookings`: Booking-level data (revenue, ratings, guests, booking platform)  
- `fact_aggregated_bookings`: Aggregated capacity and successful bookings  

🖼️ *Data Model:*  
<img width="1104" height="674" alt="Image" src="https://github.com/user-attachments/assets/c9f4f6da-19e2-43af-9a2d-7dd14566ec36" />

---

### 4. 📊 DAX & Calculated Columns
Key measures created using **DAX**:
- ADR (Average Daily Rate)  
- DSRN (Daily Successful Room Nights)  
- DBRN (Daily Booked Room Nights)  
- DURN (Daily Utilized Room Nights)  
- Occupancy %  
- Realisation %  
- Cancellation %  
- No Show Rate  
- RevPAR (Revenue per Available Room)

---

### 5. 📈 Dashboard Development
An **interactive Power BI dashboard** was built with navigation, filters, and tooltips for seamless exploration.

**Dashboard Views:**
- **Executive Overview** – High-level summary of performance, key KPIs, and trends  
- **Revenue Insights** – Revenue by city, category, booking platform, day type, and room class  
- **Booking Insights** – Booking behavior, cancellations, and occupancy analysis  

---

## 💡 Key Insights

### 🧭 Executive View
- Delhi recorded the **highest occupancy** and **average rating**, showing strong performance.  
- Bangalore trailed slightly, suggesting the need for service improvements.  
- **AtliQ Exotica (Mumbai)** generated the highest revenue of ₹212M with 65%+ occupancy.  
- Occupancy and ratings dipped between **Week 25–27**, then recovered by **Week 32**.  
- **Weekend occupancy (52.8%)** slightly outperformed **weekday occupancy (47.2%)**.

---

### 💰 Revenue Insights
- **Mumbai** led total revenue (₹669M), followed by **Bangalore (₹420M)**, **Hyderabad (₹325M)**, and **Delhi (₹295M)**.  
- **Luxury segment** outperformed Business (₹1053M vs ₹656M).  
- **Elite (₹560M)** and **Premium (₹462M)** room classes contributed the most.  
- **Third-party platforms** dominated revenue generation.  
- Revenue fluctuations around **Week 22 and Week 31** suggest seasonal variation.  
- **ADR** remained stable, while **Occupancy %** varied (50–70%).  
- Average guest rating: **3.62/5**, indicating moderate satisfaction.  
- **Weekday revenue (₹1185M)** exceeded **weekend revenue (₹524M)**, showing corporate demand dominance.

---

### 📅 Booking Insights
- **Mumbai** led bookings (43K), followed by **Hyderabad (35K)** and **Bangalore (32K)**.  
- **Delhi** showed the lowest bookings (24K), suggesting promotional opportunities.  
- **Luxury properties** captured ~62% of total bookings.  
- Occupancy rates were balanced across room classes (≈57–59%).  
- Average **cancellation rate ~24–25%**, consistent across properties.  
- **Third-party platforms** dominated the booking share.  
- **AtliQ Palace (Delhi)** achieved the highest occupancy (66.4%).

---

## 🚀 Recommendations

- Implement **dynamic pricing** to stabilize RevPAR.  
- Enhance **guest experience** and service quality in Bangalore.  
- Strengthen **weekday corporate bookings** via partnerships and offers.  
- Launch **loyalty programs** to increase direct bookings.  
- Target underperforming cities (like Delhi) with **localized marketing campaigns**.  
- Address **cancellation behavior** through flexible booking policies.  

---

## 🧰 Tools & Technologies

| Tool | Purpose |
|------|----------|
| **Power BI** | Dashboarding & DAX |
| **Power Query** | Data Cleaning & Transformation |
| **Excel** | Data Exploration |
| **GitHub** | Version Control & Documentation |

---

## 📎 Additional Information
🔗 **Dashboard Link (if published)**: [View Interactive Dashboard](your-dashboard-link-here)  

🙏 Special thanks to **Codebasics**, **Indian Data Club**, and **DPD Zero** for inspiring and guiding this initiative.

---

## 🏁 Conclusion
This project demonstrates how **data analytics and visualization** can transform strategic decision-making in the hospitality industry.  
With the Power BI dashboard, **AtliQ Grands** can monitor KPIs, identify patterns, and make informed, data-driven decisions to improve performance and profitability.

---
