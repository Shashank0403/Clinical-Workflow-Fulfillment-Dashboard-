# 🏥 Clinical Workflow & Fulfillment Dashboard 

## 📊 Project Overview

The **Clinical Workflow & Fulfillment Dashboard** is an interactive data visualization solution crafted to support **hospital management teams** in making informed, data-driven decisions. The dashboard provides a **centralized, real-time view** of patient activities, department performance, staff distribution, treatment feedback, and financial insights — all in one place.

Designed with ease of use and visual clarity in mind, this solution empowers healthcare administrators to monitor key performance indicators (KPIs), optimize patient care, and streamline hospital operations.

---

## 🚀 Key Features

- ✅ **Comprehensive KPIs**: Track Total Patients, InPatients/OutPatients, Staff Ratio, Bed Occupancy %, Avg ER Waiting Time, and Avg Treatment Cost.
- 📅 **Weekly InPatient & OutPatient Trends**: Understand admission patterns with interactive bar charts.
- 🛏️ **Bed Occupancy Monitoring**: Real-time gauge visualization to track current occupancy.
- 💵 **Revenue Analysis**: Breakdown of total revenue by patient age groups.
- ⏱️ **Avg ER Time by Department**: Department-wise ER time comparisons to identify bottlenecks.
- 😊 **Patient Satisfaction & Feedback**: Visual donut chart showcasing positive, neutral, and negative sentiment.
- 🧑‍⚕️ **Doctor Communication Rating**: Measure how well doctors explain treatments with patient feedback bars.
- 🌍 **Geographic Insights**: View patients by city and region on an interactive map.
- 🏥 **LOS (Length of Stay) Analysis**: Average LOS by age group and stay duration breakdown.
- 📋 **Detailed Patient Table**: Drill-through to see patient demographics and status across locations.

---

## 🧠 Tools & Technologies

- **Microsoft Power BI**
- **Power Query Editor**
- **MS Excel** (as data source)
- **DAX & M language**
- **Custom Visuals**: Rotating Cards, Scrollers, Interactive Maps, etc.

---

## 📸 Sample Dashboards

### 1️⃣ Hospital Summary
This dashboard provides an overview of hospital performance including patient count, staff ratio, bed occupancy, ER wait times, and revenue. It is designed for top-level monitoring and decision-making.
<img width="1344" height="725" alt="image" src="https://github.com/user-attachments/assets/d412c363-b915-44c2-84f0-5408afbe1299" />


### 2️⃣ Patient Summary
Focuses on patient demographics, satisfaction levels, treatment feedback, and LOS (Length of Stay) analysis. Enables deep dives into department efficiency and age-based insights.
<img width="1356" height="721" alt="image" src="https://github.com/user-attachments/assets/e953d387-4962-490f-9f85-95b8a743779a" />



### 3️⃣ Patient Details
An interactive table listing individual patient data by city, gender, age, and medical status. Ideal for detailed drill-through and cross-location comparisons.
<img width="1323" height="737" alt="image" src="https://github.com/user-attachments/assets/ccb93611-2fed-42a4-9a28-07fa71e929cf" />

---

## ⚙️ Data Preparation

All data was cleaned and transformed using **Power Query Editor**:

- 🔁 Merged, trimmed, and removed irrelevant columns
- 🔄 Changed column data types for consistency
- 🗂️ Loaded **Fact** and **Dimension** tables (Patients, Beds, Staff, Department, Feedback, etc.)

A **star schema data model** was designed to establish relationships between fact and dimension tables, ensuring optimal performance and data integrity.

---

## 📈 Data Modeling & Visuals

- Created relationships between datasets to establish a seamless data model.
- Built **customized dashboards** for:
  - **Hospital View**: Operational insights (staffing, beds, revenue, treatment cost)
  - **Patient View**: Demographic analysis, patient flow, department-level insights
- Implemented **drill-down** and **drill-through** capabilities to allow in-depth exploration.
- Integrated **filters, slicers**, and **buttons** for user-friendly navigation and interactivity.

---

## 🔍 Use Cases

This dashboard helps hospital management teams:

- Monitor ongoing hospital activities in real-time
- Improve patient satisfaction and operational efficiency
- Analyze patient trends by age, gender, geography, and department
- Identify and resolve ER delays and bed occupancy issues
- Make strategic decisions based on data-backed insights

---

## 🧾 Conclusion

This Power BI project serves as a **centralized data hub** for healthcare facilities, blending operational efficiency with high-quality patient care. With interactive visuals, deep analytics, and intuitive navigation, hospital management can seamlessly access insights and drive improvements.

---
