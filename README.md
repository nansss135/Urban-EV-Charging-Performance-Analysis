# Urban-EV-Charging-Performance-Analysis
Data analysis of urban EV charging station performance using Excel Pivot Tables, Charts, and Slicers to generate business insights.

# 🚗⚡ Urban EV Charging Performance Analysis

#  Project Overview

This project analyzes a large-scale **Urban EV Charging Infrastructure
Dataset (200 rows)** using Microsoft Excel. The dataset represents
electric vehicle charging station operations across multiple cities.

The goal of this project is to perform data analysis using Pivot Tables,
Charts, and Slicers to generate meaningful business insights.

------------------------------------------------------------------------

# Type of Data

This is a structured, quantitative, operational dataset.

# Dataset Features:

-   200 Clean Rows
-   No duplicates
-   Proper date format (YYYY-MM-DD)
-   Numeric + Categorical data
-   Suitable for Pivot Tables & Dashboard

# Columns Included:

-   Station_ID
-   City
-   Location_Type
-   Charger_Type
-   Date
-   Vehicles_Charged
-   Energy_Consumed_kWh
-   Avg_Charging_Time_Min
-   Revenue_INR
-   Peak_Slot
-   Weather
-   Maintenance_Status

------------------------------------------------------------------------

#  What I Have Done (Basic to Standard Level)

# Step 1: Data Preparation

-   Imported clean dataset into Excel
-   Verified no missing values
-   Checked correct data types (Date, Numbers, Text)

# Step 2: Created Pivot Tables

Used Excel Pivot Tables to summarize and analyze data.

# Step 3: Created Charts

Converted Pivot Tables into visual charts: - Line Chart - Bar Chart -
Column Chart - Pie Chart

# Step 4: Added Slicer

Inserted City Slicer to make dashboard interactive. Connected slicer to
all Pivot Tables.

------------------------------------------------------------------------

#  Analysis Performed

#  1️⃣ Revenue Trend Over Time 

# Pivot Settings:

-   Rows → Date
-   Values → Revenue_INR (Sum)

# Why?

Date is placed in rows to track revenue changes over time.

# Insight:

Revenue shows increasing trend as vehicle charging increases.

------------------------------------------------------------------------

## 2️⃣ City-wise Performance (Bar Chart)

# Pivot Settings:

-   Rows → City
-   Values → Revenue_INR (Sum)
-   Values → Vehicles_Charged (Sum)

# Why?

City is placed in rows to compare performance between cities.

# Insight:

Identified highest revenue generating city.

------------------------------------------------------------------------

# 3️⃣ Fast vs Standard Charger Comparison

# Pivot Settings:

-   Rows → Charger_Type
-   Values → Revenue_INR (Sum)
-   Values → Vehicles_Charged (Sum)

# Why?

Charger_Type is used to compare profitability and usage between charger
categories.

# Insight:

Fast chargers generate higher revenue than Standard chargers.

------------------------------------------------------------------------

# 4️⃣ Maintenance Impact Analysis

# Pivot Settings:

-   Rows → Maintenance_Status
-   Values → Revenue_INR (Sum)
-   Values → Vehicles_Charged (Sum)

# Why?

Maintenance_Status helps analyze operational efficiency.

# Insight:

Operational stations generate maximum revenue. Stations under
maintenance generate lower revenue.

------------------------------------------------------------------------

# 5️⃣ Weather vs Vehicles Charged

# Pivot Settings:

-   Rows → Weather
-   Values → Vehicles_Charged (Average)

# Why?

Weather is placed in rows to analyze environmental impact on EV demand.

# Insight:

Sunny weather shows higher charging demand compared to rainy conditions.

------------------------------------------------------------------------

# Why I Used City Slicer

-   Makes dashboard interactive
-   Allows filtering entire report by city
-   Helps compare city-level trends instantly
-   Enhances professional presentation

------------------------------------------------------------------------

#  Tools Used

-   Microsoft Excel
-   Pivot Tables
-   Charts
-   Slicers

------------------------------------------------------------------------

#  Skills Demonstrated

-   Data Cleaning
-   Data Aggregation
-   Business Insight Extraction
-   Visualization
-   Dashboard Creation
-   Analytical Thinking

------------------------------------------------------------------------

#  Conclusion

This project demonstrates how operational EV charging data can be
transformed into actionable insights using Excel tools.

The analysis highlights: - Revenue growth trends - City performance
comparison - Charger efficiency differences - Maintenance impact -
Weather influence on EV demand

This project reflects beginner-to-intermediate level data analytics
skills using Excel.

------------------------------------------------------------------------

# 👩‍💻 Prepared By

Nandani Rajput

