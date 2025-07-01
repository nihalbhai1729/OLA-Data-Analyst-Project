# OLA-Data-Analyst-Project
Project Name: Ola Ride Analysis Project

Tool Used: Sql(MY SQL), Power BI, MS Excel

Objective: This project analyzes Ola ride data, covering bookings, cancellations, revenue, vehicle performance, and customer/driver ratings. It demonstrates end-to-end analytics using SQL for data preparation and Power BI for interactive visualization.

🛠️ 1. Data Preparation with SQL
The raw ride data was first cleaned, transformed, and aggregated in SQL before importing into Power BI. This included:

-Data Cleaning

Removed duplicates and incomplete records.
Handled missing values for booking status, distance, payment method, and ratings.

-Data Transformation

Standardized date and time formats.
Mapped booking status codes to readable labels (e.g., 1=Success, 2=Cancelled by Driver, etc.).
Converted distance metrics to kilometers.

-Data Aggregation

Summarized total and successful bookings by vehicle type.
Calculated daily ride volumes and total ride distances.
Computed revenue per payment method.

SQL Quires Performed:
-Retrieve all successful bookings:
 -Find the average ride distance for each vehicle type:
 -Get the total number of cancelled rides by customers:
 -List the top 5 customers who booked the highest number of rides:
 -Get the number of rides cancelled by drivers due to personal and car-related issues:
 -Find the maximum and minimum driver ratings for Prime Sedan bookings:
 -Retrieve all rides where payment was made using UPI:
 -Find the average customer rating per vehicle type:
 -Calculate the total booking value of rides completed successfully:
 -List all incomplete rides along with the reason:


🎨 2. Power BI Dashboard
Once data was cleaned and aggregated, it was imported into Power BI to create an interactive dashboard with 5 key sections:

-Overall Analysis

Total bookings and booking value.
Booking status breakdown.
Ride volume trends over time.

-Vehicle Type Performance

Booking value by vehicle type (Prime Sedan, Mini, Auto, Bike, etc.).
Average & total distance traveled for each type.

-Revenue Analysis

Revenue split by payment methods (Cash, UPI, Credit/Debit Cards).
Top 5 customers by booking value.
Daily ride distance distribution.

-Cancellation Insights

Total successful and cancelled bookings.
Detailed reasons for cancellations by customers and drivers.
Overall cancellation rate.

-Ratings Overview

Average driver and customer ratings by vehicle type.


🚀 Tools Used
-SQL: MySQL/PostgreSQL (replace with the actual DBMS) for data cleaning and aggregation.
-Power BI: For creating interactive reports and dashboards.
-DAX: To calculate metrics like success rate, cancellation rate, and booking value summaries.

🔎 Key Insights
-Overall booking success rate: 62.09%, cancellation rate: 28.08%.
-Cash is the most used payment method (~20M revenue).
-Main cancellation reasons include drivers not moving toward pickup or personal issues.
-Driver and customer ratings are generally consistent at ~4.0










