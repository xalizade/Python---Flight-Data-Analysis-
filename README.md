# Python---Flight-Data-Analysis

## Overview
This project focuses on analyzing flight data using Python, Pandas, NumPy, Matplotlib, Seaborn, and Plotly. The dataset includes flight details such as departure delays, cancellations, and various flight attributes. The goal is to explore trends in delays and cancellations across different airlines and time periods.

## Dataset
The dataset consists of multiple Parquet files stored in the `flights data` directory. It contains information such as:
- Flight Date
- Airline
- Flight Number
- Origin and Destination Airports
- Cancellation and Diversion Status
- Departure and Arrival Times
- Delay Minutes

## Features and Analysis
- **Data Preprocessing:**
  - Reads multiple Parquet files and extracts relevant columns.
  - Converts categorical variables for efficient processing.
  
- **Data Exploration:**
  - Summary of dataset using `df.info()`.
  - Histogram of flight delays between 1 and 60 minutes.
  - Categorization of flights into groups (On-time/Early, Small Delay, Medium Delay, Large Delay, Cancelled).

- **Visualization:**
  - Bar plots showing the distribution of delay groups.
  - Yearly and monthly analysis of flight delays.
  - Calendar heatmaps to visualize cancellations over time.
  - Top 10 airlines with the most delays and cancellations.

## Dependencies
Ensure you have the following Python libraries installed before running the script:

```bash
pip install pandas numpy matplotlib seaborn plotly plotly-calplot calmap
```

## Usage
1. Place the Parquet files in the `flights data` directory.
2. Run the script in a Python environment.
3. View the generated visualizations and insights.

## Results
The analysis provides insights into:
- The most delayed and canceled airlines.
- Seasonal patterns of flight delays and cancellations.
- Trends in flight operations over multiple years.
