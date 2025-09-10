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

## Process for Power BI
The project was carried out in two main stages – data preparation with SQL and visualization with Power BI.

### Setting Up the Data
- I started by creating a dedicated database called 'uber' and loaded the 'bookings' data into it.
- This raw data included details like booking IDs, customer IDs, vehicle type, payment method, ride status, ratings, and booking value.
- Before jumping into analysis, I ran some basic queries to validate the data and understand its structure.

### Structuring Insights with SQL
To avoid writing long queries again and again, I built SQL views for different business questions. Each view gave me a focused dataset.

### Visualizing with Power BI
Once the data was clean and structured, I connected it to Power BI. Here’s where the numbers started telling stories:
- Cancellation trends by customers vs. drivers.
- Rating patterns across different vehicle types.
- Revenue contribution from successful rides.
- Seasonal or monthly booking and cancellation behavior.

### Attachment
- <a href="https://github.com/PritamSaha234/Uber-Booking-Cancellation-Project/blob/main/uberBooking.pbix">Dashboard</a>
- <a href="https://github.com/PritamSaha234/Uber-Booking-Cancellation-Project/blob/main/uberBooking.pdf">Dashboard (PDF)</a>

I designed the dashboard with a focus on clarity and storytelling so that anyone could quickly understand what’s happening with Uber bookings and cancellations in Bangalore.

### Final Outcome
By combining SQL and Power BI, the process flowed naturally:
- SQL handled the heavy lifting of cleaning and structuring.
- Power BI brought the data to life with visuals and trends.

The result is a project that doesn’t just crunch numbers but also highlights where cancellations happen most, who the top customers are, and how ratings and payments shape the overall booking experience.

## Project Insights
From the analysis of Uber bookings and cancellations, here are the main findings:

- Cancellations are high – Many rides were canceled, mostly by customers. Driver cancellations also happened, mainly due to personal or car-related issues.
- Top riders matter – A small group of customers booked far more rides than others, showing that loyal users contribute strongly to overall bookings.
- Vehicle type patterns – Short trips were often taken in Autos and Bikes, while longer trips were done with Prime Sedans and SUVs.
- Ratings vary – For Prime Sedan, the gap between the highest and lowest driver ratings was big, showing inconsistency in service. Average customer ratings also changed depending on the vehicle type.
- Digital payments rising – Many users preferred paying through UPI, showing a clear move towards cashless rides.
- Revenue insights – Most of the booking value came from successful rides, making it important to reduce cancellations and incomplete trips.
- Incomplete rides reveal issues – Recording the reasons for incomplete trips gave useful insights into where the service can be improved.
