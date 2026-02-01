# Hotel Revenue Analysis Power BI

## Project Overview
This project is part of Codebasics Resume Project Challenge, where I used Power BI to analyze hotel chain revenue performance across 4 cities and deliver actionable insights through interactive dashboards.

##### [View Codebasics Resume Project Challenge](https://codebasics.io/challenges/codebasics-resume-project-challenge/4)
##### [View Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZDc4MmQ2NzItZjYyYy00N2ZjLTk4ODctM2Y3NWI3MDc3ZmIzIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Table of Contents
- [Problem Statement](#problem-statement)
- [Task](#task)
- [Provided Mock-up Dashboard](#provided-mock-up-dashboard)
- [Tech Stack](#tech-stack)
- [Dataset](#dataset)
- [Data Model](#data-model)
- [Power BI Dashboard](#power-bi-dashboard)
- [Key Insights](#key-insights)
- [Author & Contact](#author--contact)

## Problem Statement
AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of AtliQ Grands wanted to incorporate "Business and Data Intelligence" to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.

Their revenue management team had decided to hire a 3rd party service provider to provide them with insights from their historical data.

## Task
You are a data analyst who has been provided with sample data and a mock-up dashboard to work on the following task. You can download all relevant documents from the download section.

- Create the metrics according to the metric list (dataset).
- Create a dashboard according to the mock-up provided by stakeholders.
- Create relevant insights that are not provided in the metric list/mock-up dashboard.

## Provided Mock-up Dashboard
![Mock-up Dashboard](https://github.com/RajanKumar-787/Hotel_Revenue_Analysis_Power_BI/blob/e5302259602521b52575bb1068b782d8c87355c8/Images/Mock-up%20Dashboard.png)

## Tech Stack
- **Data Sources:** CSV files
- **ETL Tool:** Power Query (Data Cleaning & Transformation)
- **Data Modeling:** Star Schema (Fact & Dimension Tables)
- **Business Intelligence Tool:** Power BI Desktop
- **Data Analysis Language:** DAX (Advanced Measures & Calculated Columns)
- **Deployment:** Power BI Service (Publishing, Sharing & Collaboration)

## Dataset
This project uses five CSV files stored in the dataset directory:

- `dim_date`
- `dim_hotels`
- `dim_rooms`
- `fact_aggregated_bookings`
- `fact_bookings`

## Data Model

This data model follows a star schema design with:
- **Fact Tables:** `fact_aggregated_bookings`, `fact_bookings`
- **Dimension Tables:** `dim_date`, `dim_hotels`, `dim_rooms`
- **Relationships:** Properly established one-to-many relationship for accurate aggregation and reliable dashboarding

![Data Model](https://github.com/RajanKumar-787/Hotel_Revenue_Analysis_Power_BI/blob/e5302259602521b52575bb1068b782d8c87355c8/Images/Data%20Model.png)

## Power BI Dashboard

This dashboard provides the overall performance of the AtliQ Grands hotel chain across Mumbai, Delhi, Bangalore, and Hyderabad, focusing on occupancy %, ADR, RevPAR, booking platforms, and property-level performance to enable data-driven revenue optimization decisions.

![Power BI Dashboard](https://github.com/RajanKumar-787/Hotel_Revenue_Analysis_Power_BI/blob/e5302259602521b52575bb1068b782d8c87355c8/Images/Power%20BI%20Dashboard.png)

## Key Insights

- The overall Occupancy % is only 57.79%, meaning 42% of rooms remain vacant, causing significant revenue loss for the hotel chain.
- Weekday occupancy (55.85%) is lower than weekends (62.64%), indicating weak business-day demand.
- The overall Realisation % is 70.14%, meaning only 70% of bookings convert to actual stays, while nearly 30% is lost due to cancellations and no-shows.
- ADR remained flat across May, June, and July, suggesting AtliQ Grands is not implementing dynamic pricing strategies to capitalize on high-demand periods such as India's summer holiday season.
- Weekday and weekend ADR showed minimal variation, indicating missed opportunities to leverage day-based pricing strategies that could capture premium rates during higher-demand weekends.
- Luxury hotels contribute 61.62% of total revenue (₹1.69B), while business hotels contribute only 38.38%, making luxury the main revenue driver.
- Mumbai generates the highest revenue (₹669M) across all cities, followed by Bangalore, Hyderabad, and Delhi.
- MakeMyTrip is one of the strongest revenue-generating platforms, making it an important booking channel for the hotel chain.
- AtliQ Exotica (Mumbai) is the top-performing hotel with ₹117M revenue, the highest RevPAR, and a strong 4.32 rating.
- AtliQ Blu (Mumbai) records one of the highest occupancy percentages, indicating strong customer demand and better room utilization.
- AtliQ Seasons (Mumbai) has the highest ADR, showing that customers are willing to pay premium rates and the property is leveraging the Mumbai market effectively.
- AtliQ Grand (Bangalore) shows weak performance with the lowest occupancy rate (44.3%), high cancellation levels, and the poorest average rating, pointing to major service quality issues and customer dissatisfaction that need immediate action.

## Author & Contact

**Author:** Rajan Kumar  
**Email:** analyst.rajankumarr@gmail.com  
**GitHub:** [https://github.com/RajanKumar-787](https://github.com/RajanKumar-787)  
**LinkedIn:** [https://www.linkedin.com/in/rajankumar0/](https://www.linkedin.com/in/rajankumar0/)  

⭐ If you found this project helpful, please consider giving it a star!  
💬 Feedback and suggestions are always welcome! 
