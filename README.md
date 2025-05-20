# AtliQ_Hospitality_Analysis_PowerBI
# Dashboard & Reporting

An interactive Power BI dashboard was developed, focused on key financial and operational metrics with filters and visualizations designed for executive decision-making.

## Live Dashboard Link:- https://app.powerbi.com/view?r=eyJrIjoiMWYyNmE2ZjgtYTZlYy00NWM2LWIyMTctZWQ2ZWQ1ZjE3OGU2IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9

Video Presentation Link

## Overview
This project was developed as part of the Codebasics Resume Challenge and centres on AtliQ Grands, a fictional chain of five-star hotels across India. The company has been experiencing a decline in market share and revenue in the luxury/business hotel segment, primarily due to inefficient management decisions.
This project leverages business intelligence and data analytics to support strategic decision-making and business revitalization.


## Problem statement
Atliq Grands has been losing market share and revenue primarily due to increased competition and suboptimal management decisions. This project aims to reverse this trend by applying hospitality analytics to derive actionable insights.


### Objectives
•	Design and calculate KPIs based on a predefined metric list.

•	Develop a fully interactive Power BI dashboard based on a stakeholder-provided mock-up.

•	Extract additional business insights beyond the initial requirements to support data-driven decision-making.


## Hotel & Data Overview

•	Hotel Chain: AtliQ Grands

•	Locations: 4 major cities across India

•	Properties: 7 five-star hotels

•	Room Categories: Standard, Elite, Premium, Presidential

•	Booking Channels: 6 key online platforms plus other direct channels


## Data Sources Used

•	dim_date: Calendar data including week numbers, months, and day types

•	dim_hotels: Property IDs, names, categories, and locations

•	dim_rooms: Room class information

•	fact_aggregated_bookings: Daily bookings, capacity, check-in dates by room category and hotel

•	fact_bookings: Detailed booking information (ID, guest count, revenue, platform, status, and ratings)


# Skills Acquired

## Key Metrics
•	Revenue

•	RevPAR (Revenue per Available Room)

•	ADR (Average Daily Rate)

•	DBRN / DSRN / DURN (Room night metrics)

•	Realisation %

•	Occupancy %

•	Cancellation %

•	Booking %

•	Average Rating

## Power BI & Analytics
•	Power BI fundamentals

•	Data cleaning and transformation

•	Snowflake schema modeling

•	Page navigation, tooltips, and conditional formatting

•	Visuals: Donut chart, Line chart, Area chart, Line & stacked column chart, Clustered column-line chart, Clustered bar chart, Matrix table

## Soft Skills

•	Hospitality domain knowledge

•	Understanding stakeholder needs via mock dashboards

•	Presenting insights and strategic recommendations


# Filters Applied

•	Room Class

•	Hotel Property

•	City

•	Booking status

•	Booking Platform

•	Month

•	Week Number


# Key Insights
•	Mumbai leads in revenue generation, contributing 668.6M, followed by Bangalore (420.4M), Hyderabad (325.2M), and Delhi (294.5).

•	Luxury rooms contributed the most to total revenue (61.61%), while the Business category contributed 38.39%.

•	Delhi stands out as the top performer in Occupancy Percentage (60.5%) and Average Rating (3.8). 

•	Hyderabad, Mumbai, and Bangalore also show strong overall performance, closely trailing behind Delhi.

•	AtliQ Exotica led among all properties with 320M revenue, an average rating of 3.62, occupancy is 57.3%, and a 24.37% cancellation rate.

•	Occupancy increases by 7% on weekends (Fri-Sat), though RevPAR remains nearly unchanged.

•	Weekday revenue accounts for 69.34%, while weekend revenue contributes 30.66%.

•	May recorded the highest monthly revenue at 581.93M, outperforming June and July.

•	Elite rooms generated the highest revenue at 560M, while Standard rooms earned the lowest at 310 M.

•	Most bookings came from other sources, 55K (699M), followed by MakeYourTrip, 27K (314M). The lowest number of bookings came from direct offline, 7K (86M).


# Recommendations

## Enhance Customer Ratings:
Customer ratings can be enhanced by delivering exceptional service, maintaining high standards of cleanliness, and offering quality food, all of which directly impact bookings and overall revenue.

## Implement Dynamic Pricing:
As the Average Daily Rate (ADR) is almost the same on weekdays and weekends, using dynamic pricing for all properties and platforms can help increase revenue.

## Address High Cancellation Rates:
Others and MakeYourTrip are the top sources of bookings, but they also have a high cancellation rate of 25% across different cities and properties. This needs attention, as high cancellations hurt hotel rankings in search results, which can reduce bookings and revenue. Additionally, Elite rooms show the highest cancellation rate and should be addressed separately.

## Optimize Room Pricing Based on Occupancy:
With an overall occupancy rate of 57.9%, the management should explore dynamic pricing strategies, particularly for properties with lower occupancy, to boost room utilization and increase revenue.


## Acknowledgments
Special thanks to Codebasics for hosting this insightful challenge and providing a real-world case study for hands-on analytics learning.


