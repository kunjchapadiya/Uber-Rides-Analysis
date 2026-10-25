# Uber Ride Booking Analysis Dashboard

An interactive Power BI dashboard for analyzing ride-booking
performance, revenue, vehicle categories, ratings, and cancellations.

## Dashboard Pages

### Overall Dashboard

High-level KPIs such as total bookings, completed rides, revenue,
cancellations, cancellation rate, and average ratings.

### Financial Analysis

Recommended visuals: - Revenue trend over time (line chart) - Revenue by
vehicle type (bar chart) - Revenue by payment method (donut chart) -
Revenue by hour or day (column chart) - Average booking value by vehicle
type (bar chart)

### Vehicle-Wise Analysis

Compare vehicle categories available in the dataset, such as Auto, Bike,
eBike, Go Mini, Go Sedan, Premier Sedan, and Uber XL.

Recommended KPIs: - Total bookings - Revenue from completed rides -
Completed rides - Cancellation rate - Average driver rating

Recommended visuals: - Bookings by vehicle type - Revenue by vehicle
type - Booking status by vehicle type (stacked column chart) - Average
ride distance by vehicle type - Ratings by vehicle type - Cancellation
rate by vehicle type

### Ratings Analysis

Recommended visuals: - Driver rating distribution - Customer rating
distribution - Average driver and customer ratings by vehicle type -
Ratings over time - Ride distance versus driver rating (scatter chart)

### Cancellation Analysis

Recommended KPIs: - Total cancellations - Customer cancellations -
Driver cancellations - Cancellation rate

Recommended visuals: - Cancellation trend over time (line chart) -
Cancellation reasons (horizontal bar chart) - Customer versus driver
cancellations (donut chart) - Cancellation rate by vehicle type -
Booking status distribution

### Vehicle-Specific Pages

Create separate pages for categories such as Go Sedan, Uber XL/Go XL, Go
Mini, and Bike/eBike, using the exact category names in the dataset.
Apply a page-level filter on `Vehicle Type` to filter every visual on
that page.

## Dataset

**Source:** `ncr_ride_bookings.csv`

The dataset includes booking status, booking value, vehicle type, ride
distance, payment method, date/time, ratings, and cancellation reasons.
Verify exact column names and category values in Power BI.

## How to Use

1.  Open Power BI Desktop.
2.  Import `ncr_ride_bookings.csv`.
3.  Check the table name and data types, especially dates, booking
    value, ride distance, and ratings.
4.  Create the required DAX measures.
5.  Build the dashboard pages and visuals.
6.  Add page-level vehicle filters to vehicle-specific pages.
7.  Configure slicers, page-navigation buttons, and bookmarks.
8.  Validate results and save or publish the Power BI report.

## Tools

-   Microsoft Power BI Desktop
-   Power Query
-   DAX
-   CSV dataset

------------------------------------------------------------------------

**Project:** Uber Ride Booking Analysis Dashboard\
**Purpose:** Analyze financial performance, vehicle usage, ratings, and
cancellations through interactive Power BI reports.
