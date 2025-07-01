# OLA-Data-Analyst-Project
Project Name: Ola Ride Analysis Project

Tool Used: Sql(MY SQL), Power BI, MS Excel

Objective: This project analyzes Ola ride data, covering bookings, cancellations, revenue, vehicle performance, and customer/driver ratings. It demonstrates end-to-end analytics using SQL for data preparation and Power BI for interactive visualization.

Dataset Overview:
- Source: Sample ola ride dataset
- Size: 1oo,ooo+ rows
- Fields Included: Booking_ID, Booking_Status, Customer_ID, Vehicle_Type, Vehicle_Type, Pickup_Location, Drop_Location, V_TAT, C_TAT ...

🛠️ Data Preparation with SQL
The raw ride data was first cleaned, transformed, and aggregated in SQL before importing into Power BI. This included:

✅ Data Cleaning

- Removed duplicates and incomplete records.
- Handled missing values for booking status, distance, payment method, and ratings.

✅ Data Transformation

- Standardized date and time formats.
- Mapped booking status codes to readable labels (e.g., 1=Success, 2=Cancelled by Driver, etc.).
- Converted distance metrics to kilometers.

✅ Data Aggregation

- Summarized total and successful bookings by vehicle type.
- Calculated daily ride volumes and total ride distances.
- Computed revenue per payment method.













