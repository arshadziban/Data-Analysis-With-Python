# NYC Taxi Trip Analysis

This project analyzes New York City taxi trip data from January 2020. The dataset contains information about taxi rides, including passenger count, payment type, fare amount, trip distance, and duration.

## Dataset Overview

The dataset includes the following key features:
- Passenger count
- Payment type (Card or Cash)
- Fare amount
- Trip distance
- Trip duration

## Key Findings

### Passenger Distribution

The distribution of passengers per trip is as follows:

| Passenger Count | Card Payment (%) | Cash Payment (%) |
|-----------------|------------------|-------------------|
| 1               | 39.57            | 20.04             |
| 2               | 14.26            | 6.77              |
| 3               | 5.33             | 2.37              |
| 4               | 2.77             | 1.42              |
| 5               | 5.40             | 2.07              |

### Payment Methods

- Card payments are more common than cash payments across all passenger counts.
- Single-passenger trips are the most frequent for both payment methods.

### Trip Characteristics

| Payment Type | Mean Fare Amount | Std Dev Fare | Mean Trip Distance | Std Dev Distance |
|--------------|-------------------|---------------|---------------------|-------------------|
| Card         | $13.11            | $5.85         | 2.99 miles          | 1.99 miles        |
| Cash         | $11.76            | $5.61         | 2.60 miles          | 1.91 miles        |

- Card payments have slightly higher average fares and trip distances compared to cash payments.

## Data Cleaning

The analysis involved cleaning the dataset by:
- Removing rows with missing values
- Filtering out extreme outliers in fare amounts and trip distances

## Future Work

Potential areas for further analysis include:
- Temporal patterns (time of day, day of week, seasonal trends)
- Geographical analysis of pickup and drop-off locations
- Impact of external factors (weather, events) on taxi demand

## Tools Used

- Python
- Pandas for data manipulation
- Matplotlib and Seaborn for visualization
