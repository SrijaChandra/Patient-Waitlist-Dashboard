# Patient-Waitlist-Dashboard (Power BI)
Interactive Power BI dashboard analyzing patient waitlist trends, specialty breakdown, and case-type performance using dynamic measures and tooltip visualizations.

## 📌 Project Overview

This project presents an interactive **Power BI dashboard** designed to analyze patient waitlist data across multiple specialties, case types, and age profiles.

The dashboard provides insights into:

* Monthly waitlist trends
* Specialty-wise patient distribution
* Case type performance (Outpatient, Day Case, Inpatient)
* Age profile and time band analysis
* Dynamic comparison of Average vs Median waitlist metrics

The objective of this project is to help stakeholders monitor patient backlog patterns and identify high-demand specialties using data-driven insights.


## 🎯 Key Features

* 📈 **Total Waitlist Comparison**

  * Latest Month vs Previous Year comparison
* 🥧 **Case Type Distribution**

  * Breakdown by Outpatient, Day Case, and Inpatient
* 📊 **Time Band vs Age Profile Analysis**

  * Stacked visual analysis of age-based patient segmentation
* 📉 **Monthly Trend Analysis**

  * Separate trend comparison for Day Case/Inpatient and Outpatient
* 🏥 **Specialty Group Breakdown**

  * Ranked specialty performance by total waitlist
* ⭐ **Top 5 Specialties**

  * Dynamic Top-N filtering
* 🔄 **Average / Median Toggle**

  * Interactive switch to compare statistical measures
* 💡 **Report Page Tooltips**

  * Custom tooltip page for deeper specialty-level insights
* 🎛️ **Dynamic Slicers**

  * Archive Date
  * Case Type
  * Specialty Name
  * Age Profile
  * Time Bands


## 🛠 Tools & Technologies Used

* **Power BI Desktop**
* **DAX (Data Analysis Expressions)**

  * Measures
  * Conditional calculations
  * Top-N filtering
* Report Page Tooltips
* Interactive Slicers
* GitHub (Version Control)



## 🧠 Data Analysis Approach

* Created calculated measures for:

  * Total Waitlist
  * Average Waitlist
  * Median Waitlist
  * Latest Month Metrics
  * Previous Year Comparisons

* Applied:

  * Top N filtering on Specialty_Name
  * Dynamic metric switching using calculation logic
  * Time-series trend analysis

* Designed a structured dashboard layout with:

  * Summary page
  * Detailed analysis page
  * Drill-down interactions



## 📊 Dashboard Pages

### 1️⃣ Summary Page

Provides high-level KPIs and visual summaries including:

* Total waitlist comparison
* Case type split
* Age vs Time Band visualization
* Monthly trend analysis

<img width="1324" height="746" alt="Screenshot 2026-02-12 195909" src="https://github.com/user-attachments/assets/70ae3c2d-a359-47e9-89df-8287227ce6ef" />


### 2️⃣ Detailed View

Provides granular specialty-level breakdown and hierarchical drill-down analysis.

<img width="1325" height="740" alt="Screenshot 2026-02-12 195929" src="https://github.com/user-attachments/assets/cbe4a83e-6b1a-49ca-a4c7-abc2f11baf35" />

## 🚀 How to Use

1. Download the `.pbix` file from this repository.
2. Open it using **Power BI Desktop**.
3. Interact with slicers and visuals to explore dynamic insights.
4. Hover over charts to view detailed tooltip analysis.



## 📈 Business Value

This dashboard helps:

* Identify high-demand medical specialties
* Monitor backlog growth patterns
* Compare waitlist metrics across time
* Support resource planning decisions
* Enable data-driven healthcare management

