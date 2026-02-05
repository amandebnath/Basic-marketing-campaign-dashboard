# Marketing Ad Spend & ROI Analysis Dashboard

A basic Power BI project designed to track digital marketing performance, spend efficiency, and Return on Investment (ROI) across multiple social media platforms.

**Data Source:** Dummy generated

---

## 📄 Executive Summary
This project transforms fragmented marketing campaign data into a high-impact performance dashboard. By automating the data pipeline and engineering custom marketing KPIs, the solution enables stakeholders to identify high-performing platforms, track budget depletion in real-time, and optimize ad spend based on conversion efficiency. The final dashboard provides a unified view of ROI, CTR, and CPA trends from campaign launch to completion.

---

## 🛠️ Tech Stack
* **BI Tool:** Power BI
* **Data Transformation:** Power Query (M)
* **Analytics:** DAX (Data Analysis Expressions)
* **Modeling:** Star Schema / Relational Modeling

## ⚡ Technical Highlights
* **Data ETL:** Cleaned and transformed multi-source tables, including date-type normalization and handling campaign-specific IDs.
* **Marketing DAX Metrics:** Developed custom measures for essential KPIs:
    * **ROI:** (Total Revenue - Total Spend) / Total Spend
    * **CTR (Click-Through Rate):** Total Clicks / Total Impressions
    * **CPC & CPA:** Cost Per Click and Cost Per Acquisition analysis.
* **Interactive UI:** Implemented a professional navigation system using **Bookmarks and Action Buttons** for a "Reset Filters" home experience.
* **Advanced Visualization:** Utilized the New Card Visual for consolidated KPI tracking and dual-axis line charts for Spend vs. Revenue trend analysis.

---

## 📊 Dashboard Preview

| Preview | 
| :---: | :---: |
| ![preview]([https://via.placeholder.com/400x250?text=Marketing+KPI+Cards](https://github.com/amandebnath/Basic-marketing-campaign-dashboard/blob/main/screenshot.png)) |


---

## ⚙️ Setup & Execution
1.  **Data Ingestion:** Load the `Campaign Information` and `Campaign Performance` tables into Power BI.
2.  **Modeling:** Ensure a 1:N relationship is active between tables via `Campaign ID`.
3.  **DAX Implementation:** Create a "Measures Table" and add the ROI, CTR, and CPA formulas.
4.  **Reporting:** Use the visual layout provided in the `.pbix` file to track performance across Facebook, Instagram, LinkedIn, and YouTube.
