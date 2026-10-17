# Uber Ride Data Analysis | Python, Pandas & Data Visualization

## Project Overview

This project focuses on Exploratory Data Analysis (EDA) of an Uber ride dataset containing **80,000 records and 20 columns**. The objective is to understand ride trends, cancellation patterns, vehicle preferences, payment methods, customer and driver ratings, and the relationship between weather, traffic conditions, and average fares.

The project uses Python for data analysis and visualization to identify patterns, data quality issues, and potential business improvement opportunities.

## Objectives

- Understand the dataset structure and data quality.
- Analyze completed and cancelled rides.
- Identify the most common cancellation reasons.
- Examine daily ride trends.
- Compare ride distribution across vehicle types and payment methods.
- Analyze average fares and cancellation rates under different weather and traffic conditions.
- Create visualizations to communicate key findings.
- Provide data-driven business recommendations.

## Tools and Technologies

- **Python** — Core programming language
- **Pandas** — Data cleaning, manipulation, and analysis
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **Jupyter Notebook** — Interactive analysis and documentation

## Dataset Description

The dataset contains 80,000 ride records across 20 columns, including:

- Ride, customer, and driver IDs
- Ride date and time
- Pickup and drop-off locations
- Distance, duration, and fare
- Payment method
- Customer and driver ratings
- Ride status and cancellation reason
- Promo code
- Vehicle type
- Weather and traffic conditions
- Driver experience

**Data coverage:** January 1–9, 2023.

## Analysis Performed

### 1. Data Quality and Cleaning
- Checked missing values and duplicate records.
- Validated basic numerical ranges.
- Examined date and time formats.
- Reviewed missing cancellation reasons and promo codes.

### 2. Ride Status and Cancellation Analysis
- Compared completed and cancelled rides.
- Examined cancellation reasons and their proportions.

### 3. Daily Ride Trend Analysis
- Calculated daily ride counts.
- Visualized changes in ride volume over time.
- Investigated the sharp decline in recorded rides on January 9.

### 4. Vehicle Type Analysis
- Compared ride counts and percentages by vehicle type.
- Analyzed cancellation rates, average fares, and ratings.

### 5. Payment Method Analysis
- Compared Card, Cash, and Wallet usage.
- Examined cancellation rates, average fares, and customer and driver ratings.

### 6. Weather Condition Analysis
- Compared ride volume across Clear, Rainy, and Foggy conditions.
- Examined cancellation rates, average fares, and ratings.

### 7. Traffic Condition Analysis
- Compared ride volume under Low, Medium, and High traffic.
- Analyzed cancellation rates, average fares, and ratings.

## Key Findings

- **Ride completion:** 71,956 rides (approximately 89.95%) were recorded as completed, while 8,044 (approximately 10.06%) were cancelled.
- **Cancellation reasons:** Rider cancellations accounted for 4,005 cases (49.79% of all cancellations), making them the largest cancellation category.
- **Daily trends:** January 3 recorded the highest daily ride count at 9,825. January 9 recorded only 3,137 rides, requiring further data completeness checks.
- **Vehicle types:** Ride volumes were almost evenly distributed across SUVs, Autos, Minis, and Sedans.
- **Payment methods:** Card, Cash, and Wallet each accounted for approximately one-third of recorded rides.
- **Weather and fares:** Rainy conditions had the highest observed average fare at 21,958.55.
- **Traffic and fares:** High traffic had the highest observed average fare at 23,651.84.
- **Ratings:** Average customer and driver ratings remained close to 3 out of 5 across the analyzed categories.

*Note: Fare units and currency have not been verified. The findings describe observed patterns and do not establish causation.*

## Data Quality Issues Identified

The analysis identified several issues requiring further validation:

- Unusually large distance, duration, and fare values.
- 79,997 mismatches between the time components of `ride_date` and `ride_time`.
- A sharp decline in recorded rides on January 9.
- A unique driver ID for every ride, which may not reflect typical ride-hailing operations.
- Missing promo codes whose meaning has not been confirmed.

Missing cancellation reasons for completed rides were labeled `Not Applicable` based on the observed data. Missing promo codes were retained without replacement because their meaning remains uncertain.

## Business Recommendations

- Investigate rider cancellation reasons and improve the booking experience where supported by further evidence.
- Validate data definitions, measurement units, driver IDs, and date/time fields.
- Confirm the completeness of January 9 records.
- Investigate fare differences by comparing distance, ride duration, locations, weather, and traffic.
- Monitor customer and driver ratings and identify opportunities to improve service quality.
- Conduct location-based analysis to identify areas with high ride volumes or cancellation rates.

## Limitations

- The dataset covers only nine calendar dates.
- The completeness of January 9 records has not been confirmed.
- Fare currency and measurement units remain unverified.
- Date/time inconsistencies and the driver ID pattern require investigation.
- The analysis is descriptive and does not prove cause-and-effect relationships.

## Conclusion

This project demonstrates the use of Python, Pandas, Matplotlib, and Seaborn to perform exploratory data analysis and communicate findings through visualizations.

The analysis highlights ride completion and cancellation patterns, differences in average fares across operational conditions, and data quality issues that need further investigation.

Resolving these data reliability concerns will help establish a stronger foundation for deeper analysis of ride demand, service quality, and operational efficiency.

## Author

**Data Analytics Portfolio Project**

Skills demonstrated: Python, Pandas, Data Cleaning, Exploratory Data Analysis (EDA), Data Visualization, and Business Insights.
