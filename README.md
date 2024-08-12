# Hypothesis-Testing-Maximizing-Taxi-Revenue-through-Payment-Type-Analysis
This project analyzes NYC Taxi Trip data to explore how different payment methods (card vs. cash) impact fare amounts. The goal is to provide data-driven insights that can help maximize revenue for taxi drivers by identifying and encouraging the use of payment methods associated with higher fares.
Table of Contents
Project Overview
Data Description
Methodology
Results
Recommendations
Technologies Used
How to Run
Contributors
License
Data Description
The analysis uses NYC Taxi Trip records, focusing on the following variables:

payment_type: Type of payment (card or cash)
fare_amount: Total fare amount in USD
trip_distance: Distance traveled in miles
passenger_count: Number of passengers in the taxi
duration: Trip duration in minutes
Methodology
Data Cleaning & Preprocessing:

Removed missing values and irrelevant columns.
Handled outliers to ensure data accuracy.
Descriptive Statistics:

Summarized fare amounts, trip distances, and payment types.
Identified patterns and trends in the dataset.
Hypothesis Testing:

Conducted a T-test to evaluate the relationship between payment type and fare amount.
Assessed whether different payment methods result in significant fare differences.
Regression Analysis:

Applied linear regression to explore how trip duration and payment type influence fare amounts.
Results
12% Higher Average Fare: Card payments are associated with a 12% higher average fare compared to cash payments.
Statistical Significance: Hypothesis testing confirmed that the difference in fare amounts based on payment type is statistically significant.
Recommendations
Incentivize Card Payments: Offer discounts or incentives for card payments to increase their usage, potentially boosting driver revenue by 10-15%.
Enhance Payment Options: Ensure seamless and secure card payment options to further encourage adoption.
Technologies Used
Programming Language: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn, SciPy
Data Source: NYC Taxi Trip Records
