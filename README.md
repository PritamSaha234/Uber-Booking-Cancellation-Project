# Uber-Booking-Cancellation-Project (Interactive Dashboard creation using Power BI and Analysing the Data using SQL)
## Project Objective
Uber India wants to create booking and cancellation report From 1st July 2025 to 30th July 2025 for the Bangalore location. So that the stakeholder of Uber India can understand their customers' and drivers' behavior to grow bookings and optimize cancellations in upcoming months.

## Dataset used
- <a href="https://github.com/PritamSaha234/Uber-Booking-Cancellation-Project/blob/main/Bookings.csv">Dataset</a>

## Questions (KPIs)
### SQL Questions:
- Retrieve all successful bookings.
- Find the average ride distance for each vehicle type.
- Get the total number of cancelled rides by customers.
- List the top 5 customers who booked the highest number of rides.
- Get the number of rides cancelled by drivers due to personal and car-related issues.
- Find the maximum and minimum driver ratings for Prime Sedan bookings.
- Retrieve all rides where payment was made using UPI.
- Find the average customer rating per vehicle type.
- Calculate the total booking value of rides completed successfully.
- List all incomplete rides along with the reason.
### Power BI Questions:
- Ride Volume Over Time.
- Booking Status Breakdown.
- Top 5 Vehicle Types by Ride Distance.
- Average Customer Ratings by Vehicle Type.
- cancelled Rides Reasons.
- Revenue by Payment Method.
- Top 5 Customers by Total Booking Value.
- Ride Distance Distribution Per Day.
- Driver Ratings Distribution.
- Customer vs. Driver Ratings.

## Process for SQL
To analyze Uber booking and cancellation trends, I followed a structured SQL-driven approach:
### Database Setup
- Created a database 'uber' and imported the 'bookings' table containing ride details such as customer info, vehicle type, booking status, payments, and ratings.
### Data Exploration
- Queried the dataset to get an overview (total bookings, successful rides, cancellations).
- Used simple SELECT queries to validate and understand the raw data.
### View Creation for Insights
To simplify analysis and improve reusability, I built SQL views for different scenarios:
- Successful Bookings – Filtered all rides that were completed successfully.
- Average Ride Distance by Vehicle Type – Found average distances for Autos, Prime Sedans, SUVs, Bikes, etc.
- Cancelled Rides by Customers – Counted how many rides customers canceled.
- Top 5 Customers – Identified the most frequent riders.
- Rides Cancelled by Drivers (Personal/Car Issues) – Focused on driver-side cancellations.
- Driver Ratings (Max & Min) for Prime Sedan – Checked service quality variations.
- UPI Payments – Extracted all rides paid via UPI.
- Average Customer Ratings per Vehicle Type – Measured customer satisfaction trends.
- Total Value of Successful Rides – Summed up the revenue from completed rides.
- Incomplete Rides with Reasons – Captured why some rides were left incomplete.
### Attachment
- <a href="https://github.com/PritamSaha234/Uber-Booking-Cancellation-Project/blob/main/uberBooking.sql">SQL File</a>
### Insight Extraction
- Each view allowed targeted exploration (e.g. cancellations, payments, ratings).
- This approach made it easier to integrate with Power BI dashboards for visualization and storytelling.
### Outcome
- Built a clear picture of cancellations, driver behavior, customer behavior, vehicle performance, and payment preferences.
- These insights can help improve decision-making, enhance customer experience, and optimize driver operations.
