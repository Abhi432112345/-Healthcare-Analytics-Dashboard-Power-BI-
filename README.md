# 🏥 Healthcare Analytics Dashboard

A powerful **Power BI dashboard** designed for hospital administrators to monitor and analyze key performance indicators (KPIs), financial metrics, and patient demographics in real-time. This project delivers actionable insights through advanced analytics and intuitive visualizations.

## 🎯 Purpose

This dashboard empowers healthcare professionals to:
- Track financial performance (billing, costs, insurance).
- Analyze patient demographics and geographic trends.
- Monitor departmental and procedural efficiency.
- Identify patterns in diagnoses and service types.

## 🚀 Features

Here’s what makes this dashboard stand out:

- **Advanced DAX Calculations**: Built complex measures for precise KPI tracking, including:
  - `Total Billing Amount`
  - `Average Billing per Visit`
  - `Average Medication Cost`
  - `Average Insurance Coverage`
 
    
  - Departmental and procedural revenue breakdowns.
 
    - - <img width="1332" height="749" alt="image" src="https://github.com/user-attachments/assets/17388575-c5d6-4d76-943b-85fe399477a7" />

- **Interactive Visualizations**: A suite of charts for multi-dimensional insights:
  - **Bar Charts**: Compare billing across departments (Cardiology, Orthopedics) and procedures (X-Ray, CT Scan).
  - **Donut/Pie Charts**: Visualize distribution of diagnoses (Hypertension, Asthma) and service types (Emergency vs. Non-Emergency).
  - **Map Visuals**: Display patient geographic data (City, State) with a "Patients Location Switch" toggle.

- **Dynamic Filtering**: Slicers for `Race`, `Year`, `Quarter`, and `Month` enable granular analysis.
- **Robust Data Model**: A star-schema connecting tables like `visits`, `patients`, `departments`, `diagnoses`, `procedures`, `insurance`, and `providers`.
- **User-Friendly Design**: Clean layout with KPI cards that double as filters, ensuring intuitive navigation.

## 📊 Key Metrics

- **Financials**: Total Billing, Treatment Costs, Insurance Covered, Out-of-Pocket Expenses, Room Charges.
- **Averages**: Per-visit Billing, Medication Costs, Out-of-Pocket amounts.
- **Breakdowns**: Revenue by Department, Procedure, Diagnosis, and Service Type.
- **Geographic Insights**: Patient distribution by location.
