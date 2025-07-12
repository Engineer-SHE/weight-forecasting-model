# Weight Forecasting from Nutrition & Body Composition

This project forecasts when a target weight will be achieved using personal health data and predictive modeling. It integrates food intake logs, body composition metrics, and historical weight trends to build a regression model that estimates the future weight trajectory under specified dietary conditions.

---

## Project Overview

The goal is to construct a data-driven, personalized tool that can:

- Forecast the date of reaching a specific weight goal
- Model the relationship between calorie intake, protein intake, and body fat percentage
- Predict future weight changes under simulated macro targets
- Provide interpretable outputs based on historical behavior

---

## Features

- Merges multi-source health data (e.g., CSV from smart scales, Excel food logs)
- Computes 7-day moving averages for calories and protein to smooth fluctuations
- Trains a multiple linear regression model
- Simulates forward to forecast weight based on input macros
- Identifies the earliest date at which a goal weight is projected to be reached
- Saves forecast results to a CSV file for further analysis or visualization

---

## Sample Output

| Date       | Predicted Weight |
|------------|------------------|
| 2025-07-15 | 152.1 lbs        |
| 2025-07-20 | 150.2 lbs        |
| 2025-07-21 | 149.9 lbs        |

---

## Technologies Used

- Python 3.10+
- pandas
- scikit-learn
- matplotlib

---

## Skills Demonstrated

- Time series feature engineering
- Multiple linear regression
- Model evaluation (R², MAE)
- Data merging and cleaning
- Forecast simulation based on macro targets

---
