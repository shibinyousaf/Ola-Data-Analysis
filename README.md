# Ola Data Analysis

## Overview
This project focuses on analyzing **Ola ride data** using **SQL, Excel, and Power BI**. The goal is to extract valuable insights related to **ride bookings, cancellations, payments, ratings, and revenue trends**. The project involves SQL queries for data extraction and transformation, along with Power BI visualizations for interactive reporting.

## SQL Analysis
By leveraging SQL, we dive deep into Ola ride data to uncover meaningful trends. We explore the success rate of bookings, analyze ride distances across different vehicle types, and assess customer and driver behavior. Our queries help quantify cancellations, track revenue flow, and compare driver ratings, ensuring a clear understanding of ride performance.

## Power BI Insights
Using Power BI, we bring data to life with dynamic dashboards and visualizations. We track ride volume trends over time, identify the most preferred vehicle types, and analyze how different payment methods contribute to revenue. Our visual reports highlight key performance indicators, such as ride completion rates, customer satisfaction scores, and cancellation reasons. We also compare customer and driver ratings, providing insights into the overall ride experience.

## Data Columns
The dataset consists of the following columns:

```plaintext
1. Date - Booking date.
2. Time - Booking time.
3. Booking_ID - Unique identifier for each booking.
4. Booking_Status - Status of the booking (Completed, Cancelled, Incomplete, etc.).
5. Customer_ID - Unique identifier for customers.
6. Vehicle_Type - Type of vehicle booked.
7. Pickup_Location - Location where the ride started.
8. Drop_Location - Location where the ride ended.
9. V_TAT - Vehicle turnaround time.
10. C_TAT - Customer turnaround time.
11. Cancelled_Rides_by_Customer - Indicator for customer-initiated cancellations.
12. Cancelled_Rides_by_Driver - Indicator for driver-initiated cancellations.
13. Incomplete_Rides - Rides that were not completed.
14. Incomplete_Rides_Reason - Reason for ride incompletion.
15. Booking_Value - Revenue generated per booking.
16. Payment_Method - Mode of payment used.
17. Ride_Distance - Distance covered during the ride.
18. Driver_Ratings - Ratings provided by customers for drivers.
19. Customer_Rating - Ratings provided by drivers for customers.
```

## Conclusion
Through SQL analysis and Power BI visualizations, this project provides a **data-driven understanding of Ola rides**. By uncovering patterns in **customer behavior, driver performance, and revenue generation**, the insights gained can be leveraged for **business growth, operational efficiency, and enhanced user experience**. 🚖📊
