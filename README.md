🚖 DashDrive OLA Analytics

A Data Analyst Project using SQL & Power BI

This project analyzes ride-booking data for OLA using SQL and Power BI to uncover insights about ride volumes, customer behavior, booking status, revenue, and driver performance. It enables better decision-making by identifying trends and optimization areas.

🔍 Project Overview

Tools Used:

SQL – Data cleaning, aggregation & view creation

Power BI – Interactive dashboards & visualizations

CSV/Excel – Data source

🧑‍💼 Business Objective

To analyze OLA’s operational data and extract key insights across:

Ride volumes

Booking outcomes

Payment preferences

Driver & customer ratings

Ride cancellations

Top-performing customers & vehicles

🗃️ Database Summary

Main Table: bookings.csv
Key Columns:

Booking_ID, Customer_ID, Vehicle_Type

Booking_Status, Ride_Distance

Payment_Method, Driver_Ratings, Customer_Rating

Booking_Value, Incomplete_Rides, Incomplete_Rides_Reason

🧾 Key SQL Views & Queries
#	Insight	SQL View Name
1️⃣	All successful bookings	Successful_Bookings
2️⃣	Avg. ride distance by vehicle	ride_distance_for_each_vehicle
3️⃣	Total customer cancellations	cancelled_rides_by_customers
4️⃣	Top 5 customers by rides	Top_5_Customers
5️⃣	Driver cancellations (car/personal)	Rides_cancelled_by_Drivers_P_C_Issues
6️⃣	Max/Min driver rating for Prime Sedan	Max_Min_Driver_Rating
7️⃣	Rides paid via UPI	UPI_Payment
8️⃣	Avg. customer rating per vehicle	AVG_Cust_Rating
9️⃣	Total value of successful rides	total_successful_ride_value
🔟	Incomplete rides & reasons	Incomplete_Rides_Reason

✅ File: Ola DA Project SQL.sql
📂 Contains all view creation queries.

📊 Power BI Dashboard Features

File: Ola DA Project.pbix
Size: 3.96 MB

Key Visuals & Charts:

📈 Ride Volume Over Time

📋 Booking Status Breakdown

🚗 Top 5 Vehicle Types by Ride Distance

💸 Revenue by Payment Method

👥 Top 5 Customers by Booking Value

❌ Ride Cancellation Reasons

🌟 Driver & Customer Ratings

📊 Ride Distance Distribution (Daily)

KPIs:

Total Revenue

Average Revenue per Ride

Number of Rides

Average Rating

✨ Features: Drill-through, slicers, dynamic filters, real-time visuals

🚀 How to Run the Project
SQL Setup:

Create Database:

CREATE DATABASE Ola;
USE Ola;


Import bookings.csv using MySQL Workbench

Run Ola DA Project SQL.sql to create views

Power BI:

Open Ola DA Project.pbix in Power BI Desktop

Explore the prebuilt dashboards interactively

📁 Project Files
File	Description	Size
Ola DA Project SQL.sql	All SQL queries & views	4 KB
Ola DA Project.pbix	Power BI Dashboard	3.96 MB
Bookings.csv	Raw ride bookings data	15.5 MB
📌 Summary

DashDrive OLA Analytics empowers stakeholders to make data-driven decisions through clear, interactive dashboards and optimized SQL queries—enhancing customer experience, operational efficiency, and revenue insights.
