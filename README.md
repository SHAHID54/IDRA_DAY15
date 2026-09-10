# Executive Hotel Booking — Exploratory Data Analysis

## Overview
This project performs an end-to-end Exploratory Data Analysis (EDA) on a hotel
booking dataset containing 25,180 records and 35 features. The goal is to
understand booking behavior, revenue drivers, and cancellation patterns across
hotel types, market segments, and customer types.

## Dataset
- **File:** `Executive_Hotel_Booking_EDA_Dataset.csv`
- **Records:** 25,180
- **Features:** 35 (categorical + numerical), including Hotel_Type, ADR,
  Lead_Time_Days, Total_Nights, Estimated_Revenue, Satisfaction_Score,
  Market_Segment, Customer_Type, and Is_Canceled.

## Objectives
- To understand the structure, data types, and quality of the dataset
- To identify missing values and outliers
- Analyze distributions of key numerical variables
- Compare booking metrics (ADR, revenue, cancellation rate) across hotel type,
  market segment, and customer type
- to study relationships between variables using scatter plots, box plots, and a
  correlation heatmap

## Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter / Google Colab

## Key Findings
- Total nights stayed has a strong positive relationship with estimated
  revenue.
- Weekday nights also correlate strongly with both total nights and revenue.
- ADR (Average Daily Rate) has a moderate positive relationship with revenue.
- Resort Hotel tends to have a higher ADR than City Hotel, though City Hotel
  shows more extreme high-value ADR outliers.
- Special requests do not show a strong relationship with guest satisfaction
  scores.
