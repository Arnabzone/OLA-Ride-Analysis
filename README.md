# OLA Ride Analysis | SQL & Power BI

## Project Overview
An end-to-end data analytics portfolio project analyzing 100,000 synthetic ride-booking records using **PostgreSQL, SQL, Power BI, and DAX**.

The project explores booking performance, vehicle demand, cancellation patterns, booking value, payment methods, and customer and driver ratings through a five-page interactive Power BI dashboard.

## Tools & Technologies

- **PostgreSQL** — Data storage and SQL analysis
- **pgAdmin** — Database management and query execution
- **Microsoft Power BI Desktop** — Dashboard development and visualization
- **DAX** — KPI calculations and measures
- **PBIP / TMDL** — Power BI project and semantic model files

## Repository Structure

- `data/` — Synthetic booking dataset
- `report/` — Power BI report and semantic model
- `SQL_queries/` — SQL analysis and validation queries

## Dashboard Pages

1. **Executive Overview** — Booking volume, success rate, cancellation rate, booking value, and booking-status distribution.
2. **Demand & Distance** — Booking demand by vehicle type, daily trends, and average successful ride distance.
3. **Cancellations & Ride Failures** — Customer and driver cancellation reasons and incomplete rides.
4. **Revenue & Payment** — Successful booking value by payment method, vehicle type, and date.
5. **Ratings & Customers** — Driver and customer ratings, vehicle comparisons, and top customers by successful booking value.

## Key Findings

- **100,000** total booking records
- **62,000** successful bookings
- **62.0%** booking success rate
- **25.0%** combined customer and driver cancellation rate
- **₹29.63 million** successful booking value
- **₹477.91** average booking value for successful rides
- **4.25** average driver rating
- **4.25** average customer rating

## Business Questions Explored

- What proportion of bookings are successful, cancelled, incomplete, or expired?
- Which vehicle categories receive the most bookings?
- What reasons are most frequently associated with cancellations?
- Which payment methods and vehicle types contribute the most successful booking value?
- How do driver and customer ratings vary across vehicle types?
- Which customers have the highest total successful booking value?

## Data & Methodology
The dataset contains synthetic OLA-style booking records for October 2026. SQL queries were used to aggregate booking outcomes, investigate cancellation reasons, compare vehicle categories, analyze payments and ratings, and validate key metrics.

The Power BI report connects to a PostgreSQL database and uses a semantic model with DAX measures and a Calendar table.

## Important Disclaimer
This is an independent portfolio project using **synthetic data**. It is not an official OLA report, and the results do not represent actual OLA operations. “Successful booking value” is a booking-value metric and should not be interpreted as verified company revenue or profit.

## How to Explore

1. Review the SQL queries in `SQL_queries/`.
2. Open the `.pbip` project in Power BI Desktop, keeping the associated report and semantic model folders together.
3. Configure your own PostgreSQL connection if you want to refresh the data.
4. Explore the five report pages and their filters.
