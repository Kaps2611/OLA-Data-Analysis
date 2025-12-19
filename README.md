# OLA Data Analysis Project
## Project Objective
To analyze OLA ride booking data using SQL and Power BI to uncover insights on ride performance, cancellations, revenue trends, and customer behavior, enabling data-driven decision-making and operational improvements.

## Dataset Used
- <a href="https://github.com/Kaps2611/OLA-Data-Analysis/blob/main/OLA%20Dataset.csv"> OLA Dataset</a>


# Questions
## SQL Questions:
1. Retrieve all successful bookings:
2. Find the average ride distance for each vehicle type:
3. Get the total number of cancelled rides by customers:
4. List the top 5 customers who booked the highest number of rides:
5. Get the number of rides cancelled by drivers due to personal and car-related issues:
6. Find the maximum and minimum driver ratings for Prime Sedan bookings:
7. Retrieve all rides where payment was made using UPI:
8. Find the average customer rating per vehicle type:
9. Calculate the total booking value of rides completed successfully:
10. List all incomplete rides along with the reason:

## Power BI Questions:
1. Ride Volume Over Time
2. Booking Status Breakdown
3. Top 5 Vehicle Types by Ride Distance
4. Average Customer Ratings by Vehicle Type
5. cancelled Rides Reasons
6. Revenue by Payment Method
7. Top 5 Customers by Total Booking Value
8. Ride Distance Distribution Per Day
9. Driver Ratings Distribution
10. Customer vs. Driver Ratings

## Dashboard Interaction:
- Overall Dashboard <a href="https://github.com/Kaps2611/OLA-Data-Analysis/blob/main/Overall.png">Overall</a>
- Vehicle Type Dashboard <a href="https://github.com/Kaps2611/OLA-Data-Analysis/blob/main/Vehicle%20Type.png">Vehicle-Type</a>
- Revenue Dashboard <a href="https://github.com/Kaps2611/OLA-Data-Analysis/blob/main/Revenue.png">Revenue</a>
- Cancellation Dashboard <a href="https://github.com/Kaps2611/OLA-Data-Analysis/blob/main/Cancellation.png">Cancellation</a>
- Ratings Dashboard <a href="https://github.com/Kaps2611/OLA-Data-Analysis/blob/main/Ratings.png">Ratings</a>

## Process:
- Data Generation – Created a synthetic OLA ride dataset for Bengaluru covering one month with realistic booking, ride, and rating details.
- Data Cleaning – Validated data consistency, handled missing values, and ensured business rules (success, cancellation, and incomplete ride limits).
- SQL Analysis – Wrote SQL queries and views to analyze bookings, cancellations, ride distance, revenue, and ratings.
- Data Visualization – Built interactive Power BI dashboards to track ride volume, booking status, revenue, cancellations, and customer/driver ratings.

## Dashboard: 
<img width="1329" height="740" alt="Overall" src="https://github.com/user-attachments/assets/85d03e11-b13d-4a7f-8ba3-b967d58f47e4" />

## Project Insights:
- Customer cancellations remained under 7%, with major reasons being drivers not moving toward pickup and last-minute plan changes.
- Driver-side cancellations (under 18%) were primarily due to personal or vehicle-related issues, highlighting fleet reliability challenges.
- Weekends and match days showed significantly higher ride demand and booking values, making them key periods for revenue optimization.
- Prime Sedan and Prime SUV contributed higher average booking values and longer ride distances compared to other vehicle types.
- UPI emerged as the most preferred payment method, driving a major share of successful transactions.
- Incomplete rides were below 6%, mainly caused by vehicle breakdowns and customer demand issues.
- Higher customer ratings strongly correlated with higher driver ratings, indicating service quality consistency.
- A small group of top customers contributed a disproportionate share of total revenue, supporting targeted loyalty strategies



