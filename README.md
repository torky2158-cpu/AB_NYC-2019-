# Airbnb NYC 2019 — Data Cleaning & Modeling

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Project-yellow)

## About the project
This project focuses on cleaning and modeling the AB_NYC_2019 dataset using Power BI. The raw data came as a single flat file and was transformed into a proper star schema with fact and dimension tables.

## What was done
- Cleaned and transformed raw data using Power Query
- Split the flat file into fact and dimension tables
- Created a `dim_area` table with a surrogate key (`area_id`) derived from unique neighbourhood + neighbourhood_group combinations
- Linked `dim_area` to the fact table using Merge Queries to ensure correct ID mapping
- Built relationships in the data model with proper cardinality and filter direction
- Designed a one-page dashboard showing key KPIs and insights

## Dashboard highlights
- Total listings, revenue, median price, and occupancy rate
- Top 10 neighbourhoods by estimated revenue
- Room type distribution
- Listings trend over time
- Revenue distribution by location (map)

## Dataset
AB_NYC_2019 — publicly available Airbnb listings data for New York City.

## Tools used
- Power BI Desktop
- Power Query (M language)
  
