# Ola_Rides_Data_Analysis

### OLA Ride Booking Analysis | Excel, SQL & Power BI

An end-to-end data analytics project that analyzes OLA ride booking data to uncover customer behavior, operational performance, cancellation patterns, revenue trends, and business insights through Excel, SQL, and Power BI.

### Project Overview

This project focuses on analyzing ride booking data from OLA to understand operational efficiency, customer behavior, booking trends, and revenue performance. The project follows the complete data analytics workflow—from data cleaning in Excel, querying business problems with SQL, to building an interactive Power BI dashboard for business stakeholders.

The dashboard enables decision-makers to monitor ride performance, booking status, cancellation trends, customer ratings, and revenue through interactive visualizations.

### Problem Statement

Ride-hailing companies generate massive amounts of booking data every day. Without proper analysis, it becomes difficult to answer critical business questions such as:

How many rides are successfully completed?
Why are rides being cancelled?
Which vehicle types generate the most revenue?
Which customers contribute the highest booking value?
How do ratings vary across vehicle types?
Which payment methods generate the highest revenue?

The objective of this project is to convert raw ride booking data into meaningful business insights that improve operational efficiency and support strategic decision-making.

### Dataset

The dataset contains 1 lakh (100,000) ride booking records for Bengaluru over one month and includes booking details, vehicle information, pickup and drop locations, ride status, revenue, ratings, payment methods, and ride distance.

Dataset Features
Booking ID
Date & Time
Booking Status
Customer ID
Vehicle Type
Pickup Location
Drop Location
Vehicle Arrival Time (VTAT)
Customer Arrival Time (CTAT)
Cancellation Details
Booking Value
Ride Distance
Payment Method
Driver Rating
Customer Rating

### Tools & Technologies
Microsoft Excel
Data Cleaning
Pivot Tables
Pivot Charts
Data Validation
SQL
Data Extraction
Aggregations
Views
Business Queries
Microsoft Power BI
Data Modeling
DAX Measures
Interactive Dashboard
KPI Cards
Slicers
Drill-through Analysis

### Methods
1. Data Cleaning (Excel)
Removed duplicate records
Checked missing values
Standardized date and text formats
Corrected inconsistent values
Prepared structured data for analysis
2. SQL Analysis

Solved business questions including:

Successful bookings
Average ride distance
Cancellation analysis
Top customers
Revenue analysis
Customer ratings
Driver ratings
Payment method analysis

The project includes SQL queries and reusable SQL views for each business question.

3. Power BI Dashboard

Designed an interactive dashboard consisting of:

Ride Volume Over Time
Booking Status Breakdown
Revenue Analysis
Vehicle Performance
Cancellation Analysis
Customer Ratings
Driver Ratings
Top Customers
Payment Method Analysis

These dashboard components are specified in the project brief.

### Dashboard Output
Dashboard Pages
📍 Overall Performance
Total Bookings
Successful Rides
Ride Volume Trend
Booking Status Distribution
🚗 Vehicle Analysis
Top Vehicle Types
Ride Distance Analysis
Average Ratings
💰 Revenue Analysis
Revenue by Payment Method
Top Customers
Booking Value Distribution
❌ Cancellation Analysis
Customer Cancellation Reasons
Driver Cancellation Reasons
⭐ Ratings Dashboard
Driver Rating Distribution
Customer Rating Distribution
Customer vs Driver Ratings

### Key Insights
Booking Performance
Successful rides contribute the majority of bookings, while cancellations and incomplete rides highlight operational challenges.
Revenue
Digital payment methods account for a significant share of booking revenue.
A small group of high-value customers contributes disproportionately to total revenue.
Customer Behaviour
Premium vehicle categories generate higher booking values.
Frequent customers represent opportunities for loyalty programs.
Cancellation Analysis
Customer cancellations are commonly linked to driver delays or changes in plans.
Driver cancellations often stem from personal or vehicle-related issues.
Ratings
Vehicle types with higher customer ratings indicate stronger service quality.
Comparing customer and driver ratings helps identify service gaps.

### Business Recommendations
1. Reduce Customer Cancellations
Improve driver allocation and estimated arrival times.
Notify customers proactively about delays.
2. Improve Driver Retention
Investigate recurring driver cancellation reasons.
Introduce incentives for maintaining high ride completion rates.
3. Increase Revenue
Promote digital payment methods through cashback or rewards.
Offer personalized promotions to high-value customers.
4. Optimize Fleet Allocation
Deploy high-demand vehicle types in peak-demand locations.
Use historical ride data for demand forecasting.
5. Enhance Customer Experience
Monitor low-rated rides and identify recurring service issues.
Reward highly rated drivers to encourage quality service.
6. Strengthen Customer Loyalty
Introduce rewards for frequent riders.
Offer exclusive discounts to repeat customers.

### How to Run This Project
Clone this repository.
Open the Excel workbook to review the cleaned dataset.
Import the dataset into SQL and execute the provided SQL queries/views.
Open the Power BI (.pbix) file.
Refresh the data model.
Use slicers and filters to explore booking trends, revenue, cancellations, and ratings interactively.

### Results & Conclusion

This project demonstrates an end-to-end data analytics workflow using Microsoft Excel, SQL, and Power BI.

By transforming raw ride booking data into an interactive dashboard, the project enables stakeholders to:

Monitor operational performance
Track booking success rates
Analyze cancellation patterns
Evaluate customer and driver satisfaction
Identify high-value customers
Support data-driven business decisions

The combination of Excel for preparation, SQL for analysis, and Power BI for visualization provides a scalable approach to business intelligence.

### Future Work

Future enhancements include:

Predict ride demand using Machine Learning
Develop ride cancellation prediction models
Build real-time dashboards with live database connectivity
Integrate weather and traffic data for demand forecasting
Implement customer segmentation using RFM analysis
Create automated ETL pipelines with Power Query or cloud services

### Repository Structure

OLA-Data-Analysis/
│

├── Dataset/

│   └── ola_bookings.csv

│

├── Excel/

│   └── OLA_Data_Cleaning.xlsx

│

├── SQL/

│   ├── SQL_Queries.sql

│   └── SQL_Views.sql

│

├── Power BI/

│   └── OLA_Dashboard.pbix

│

├── Images/

│   ├── Dashboard_Overview.png

│   ├── Revenue.png

│   ├── Cancellation.png

│   └── Ratings.png

│

└── README.md


### Author

Nimisha Tripathy | Data Analyst

##### Skills

Microsoft Excel
SQL
Microsoft Power BI
Data Cleaning
Data Visualization
Dashboard Development
Business Intelligence

### Contact

LinkedIn:
Email: n.tripathy200@gmail.com
