This repository contains the completed Power BI project submission for 

Assignment 2025 , focusing on a comprehensive analytics dashboard for 

Retail Returns Performance.

The project successfully delivers insights into employee performance, returns analysis, and key trends using advanced Year-over-Year (YoY) comparisons.
 Project Objective
The core objective was to build a Power BI Report/Dashboard using the 

Orders, People, and Returns datasets to provide insights into employee performance, returns analysis, and key trends with YoY comparison.

📋 Deliverables Met
The final submission includes the following required components:

PBIX File: The complete Power BI dashboard file.


YouTube Link: A 5-minute video presentation walkthrough (link to be provided upon submission).


✅ Technical Implementation (Tasks Performed)
The project strictly followed the technical requirements outlined in the assignment brief.

1. Data Preparation & Modeling

Data Loading: Imported, cleaned, and transformed the Orders, People.xlsx, and Returns.xlsx datasets.



Data Model: Created a Star Schema design with logical relationships between all tables (Orders, People, Returns).





Date Table: A dedicated Date Table was created using DAX functions and marked as the official date table for accurate time intelligence.


2. Advanced DAX Calculations
Complex DAX measures were written to calculate key performance indicators (KPIs) and their YoY comparisons using time intelligence functions like 

SAMEPERIODLASTYEAR().


Measure	Formula	YoY Calculation Included?
Return Rate %	
(Number of returns / Total transactions) 

Yes (YoY Return Rate % change) 

Avg. Return Value	
Average monetary value of returns 

Yes (YoY Avg. Return Value change) 

Top 5 Employees	
Dynamic calculation of top employees by return count 

Yes (YoY return count difference shown) 

% Contribution	
% Contribution of Each Employee to Total Returns 


Yes (Comparison with last year's contribution) 



Export to Sheets
📈 Dashboard Components (Visualization & UI/UX)
The final dashboard design is clean, professional, and highly interactive, meeting all visualization requirements:


1. Key Performance Indicators (KPIs)
Five KPI cards are displayed at the top, which all adhere to the requirement of showing YoY comparison:

Return Rate % (e.g., 0.09).

YoY Return Rate % Change (e.g., 0.60).

Avg. Return Value (e.g., 206.67).

YoY Avg. Return Value Change (e.g., -0.06).

Total Returns (e.g., 594).

2. Visual Analysis Charts
Chart Type	Name	Purpose & Assignment Alignment
Donut Chart	
% contribution by employee with YoY difference tooltip 


Shows the contribution of key personnel (Anna, Maigee, etc.) to the total return volume, with the last year's difference accessible in the tooltip.


Bar Chart	
Top 5 employees by returns with YoY comparison 

Visually compares 

Total Returns vs. Total Returns Last Year for the top-performing employees, highlighting YoY performance difference.

Line Chart	
Monthly return trends with YoY overlay 


Tracks return volume over time (Jul 2014 onwards) with a clear YoY trend line overlay, aiding in trend and seasonality analysis.



Export to Sheets
3. Interactivity & Filters
The dashboard features multiple slicers/filters for dynamic analysis:

Employee/Person

Region

Date

The dashboard ensures full 

interactivity, where all visuals cross-filter properly upon selection.

⭐️ Evaluation Criteria Focus
This project was developed with a strong focus on the key evaluation areas:

Criteria	Weight	Implementation Focus
DAX & Time Intelligence	30%	
Correctness and robust application of all five required YoY measures.

Data Modeling	20%	
Correct Star Schema and logical relationships established between all three tables.

Visualization & UI/UX	20%	
Professional design, consistent theme, and effective use of chart types (KPIs, Donut, Bar, Line).

Insights & Storytelling	20%	
The dashboard design facilitates the extraction and explanation of meaningful YoY insights.


Export to Sheets
🖥️ How to Run the Project
Clone the Repository: Download or clone this project's files.

Open in Power BI: Open the Retail_Returns_Dashboard.pbix file using Power BI Desktop.

Explore the Data: Use the Person, Region, and Date slicers to dynamically filter the KPIs and visualizations.
