# Trend Analysis in Ride-Sharing Pricing and Commuting Patterns

This project was completed as part of the **DSCI 5260 – Business Process Analytics** course at the University of North Texas. It investigates dynamic pricing and ride behavior in the District of Columbia's ride-sharing ecosystem using a dataset of over 199,000 taxi transactions from December 2023.

## Files Included
- `Project.ipynb` – Main Jupyter Notebook with exploratory data analysis, modeling, and visualizations.
- `Project Report.pdf` – Formal final report including abstract, methodology, results, and literature review.

## Project Overview
- **Goal:** Identify key fare determinants and forecast ride fare totals using machine learning.
- **Models Used:** Random Forest Regression and Gradient Boosting
- **Key Findings:** 
  - `FAREAMOUNT`, `GRATUITYAMOUNT`, and `MILEAGE` are top fare predictors.
  - Random Forest achieved R² = 0.96 and was selected as the best-performing model.

## Dataset
- Source: [District of Columbia Taxi Trip Data – December 2023](https://dcgov.app.box.com/v/taxi-trips-2023)
- Records: 199,308 trips
- Variables include: fare, distance, time, tips, surcharges, pickup/drop-off locations, and payment types.

## Techniques Applied
- Data Cleaning: KNN, median/mode imputation
- Visualization: EDA, correlation analysis, geospatial plotting
- Modeling: Random Forest & Gradient Boosting Regression
- Evaluation Metrics: R², MAE, RMSE, Accuracy within 10%

## Key Insights
- Most trips are intra-city and short distance.
- Peak demand occurs mid-day and mid-week.
- Credit cards dominate payment types and tend to yield higher gratuities.
- Predictive models are effective at forecasting fare with high accuracy.


## Future Work
- Include external factors like weather and traffic data
- Extend to multi-month or city-wide datasets
- Incorporate deep learning and time series forecasting

---

> Feel free to fork, explore, or build upon this work. For questions, reach out via LinkedIn or email.

