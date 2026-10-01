# Cyclistic Bike Share Analysis

## Project Overview

This project analyses Cyclistic bike-share trip data covering October 2024 to September 2025. The analysis uses Python and Pandas to clean, prepare and explore millions of ride records to identify patterns in rider behaviour, trip duration and usage over time.

## Business Objective

The objective is to understand how Cyclistic riders use the bike-share service and identify meaningful differences in usage patterns between member and casual riders.

These insights can support data-driven decisions around customer engagement, service planning and rider retention.

## Dataset

The dataset contains monthly Cyclistic bike-share trip records from October 2024 through September 2025.

Key fields include:

- Ride type
- Start and end timestamps
- Start and end stations
- Geographic coordinates
- Rider membership type

The original dataset contains more than 5.5 million ride records across 12 monthly files.

## Data Preparation

The data preparation process included:

- Loading and combining 12 monthly CSV files
- Standardising timestamp fields
- Checking missing values
- Checking duplicate ride IDs
- Validating categorical values
- Validating geographic coordinates
- Calculating ride duration
- Identifying anomalous duration records
- Creating month, weekday and starting-hour features

## Analysis

The analysis will examine:

- Member versus casual rider behaviour
- Ride volume over time
- Ride duration patterns
- Weekday and hourly usage
- Rideable bike types
- Seasonal and monthly patterns

## Key Findings

*To be updated after the exploratory analysis.*

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter / Google Colab

## Project Structure

```text
cyclistic-bike-share-analysis/
├── README.md
├── cyclistic_data_cleaning.ipynb
└── .gitignore
