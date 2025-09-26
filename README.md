Retail Returns Performance Dashboard (Assignment 2025) 📊

This repository contains the completed Power BI project submission for Assignment 2025, focusing on a comprehensive analytics dashboard for Retail Returns Performance.

The project delivers actionable insights into employee performance, returns analysis, and key trends using advanced Year-over-Year (YoY) comparisons.

🎯 Project Objective

The objective was to build a Power BI Report/Dashboard using the Orders, People, and Returns datasets to:

Provide insights into employee performance.

Analyze returns trends.

Highlight key KPIs with YoY comparison.

📋 Deliverables

The final submission includes:

PBIX File: Complete Power BI dashboard file.

YouTube Link: A 5-minute video walkthrough of the dashboard (to be provided upon submission).

✅ Technical Implementation
1. Data Preparation & Modeling

Data Loading: Imported, cleaned, and transformed Orders.xlsx, People.xlsx, and Returns.xlsx.

Data Model: Implemented a Star Schema with logical relationships between Orders (fact) and People/Returns (dimension).

Date Table: Created a dedicated Date Table using DAX functions and marked it as the official Date Table for time intelligence.

2. Advanced DAX Calculations

Robust measures were written with time intelligence functions such as SAMEPERIODLASTYEAR() to calculate KPIs and their YoY values.

Measure	Formula (Concept)	YoY Comparison Included?
Return Rate %	(Number of returns ÷ Total transactions)	✅ Yes
Avg. Return Value	Average value of returns	✅ Yes
Top 5 Employees	Dynamic ranking by return count	✅ Yes
% Contribution	Employee’s % contribution to returns	✅ Yes
📈 Dashboard Components
1. Key Performance Indicators (KPIs)

Five KPI cards at the top, each with YoY comparison:

Return Rate % (e.g., 0.09)

YoY Return Rate % Change (e.g., 0.60)

Avg. Return Value (e.g., 206.67)

YoY Avg. Return Value Change (e.g., -0.06)

Total Returns (e.g., 594)

2. Visual Analysis Charts
Chart Type	Name	Purpose
Donut Chart	% Contribution by Employee (with YoY difference tooltip)	Shows employee-wise contribution to total returns.
Bar Chart	Top 5 Employees by Returns (with YoY comparison)	Compares Total Returns vs. Last Year Returns for top employees.
Line Chart	Monthly Return Trends (with YoY overlay)	Displays trends & seasonality in returns since July 2014.
3. Interactivity & Filters

The dashboard includes slicers for:

Employee/Person

Region

Date

All visuals cross-filter dynamically for interactive exploration.

⭐️ Evaluation Criteria Alignment
Criteria	Weight	Implementation Highlights
DAX & Time Intelligence	30%	Correct YoY measures using robust DAX.
Data Modeling	20%	Star Schema with clear relationships.
Visualization & UI/UX	20%	Clean design, professional visuals.
Insights & Storytelling	20%	Dashboard enables meaningful YoY insights.
🖥️ How to Run the Project

Clone the Repository or download the project files.

Open in Power BI: Launch Retail_Returns_Dashboard.pbix using Power BI Desktop.

Explore the Data: Use slicers (Person, Region, Date) to interact with KPIs & visuals.

📌 Notes

This project demonstrates the application of advanced DAX, data modeling, and interactive reporting in Power BI.

Built with a strong focus on clarity, interactivity, and meaningful insights.
