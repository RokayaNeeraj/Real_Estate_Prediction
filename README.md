
# Regression Challenge: Real Estate Price Prediction

## Overview
In this project, the goal is to predict the selling price of residential properties, a value that hinges on numerous factors including transaction_date, house_age, transit_distance, local_convenience_stores, latitude,	longitude,	price_per_unit. We delve into a real estate sales transaction dataset to forecast the price-per-unit of properties, with the unit measurement standard set at 3.3 square meters.

## Data Source
The dataset employed in this analysis is sourced from the following study: 
Yeh, I. C., & Hsu, T. K. (2018). Building real estate valuation models with comparative approach through case-based reasoning. Applied Soft Computing, 65, 260-271.
It's obtained from the UCI Machine Learning Repository (Dua, D., and Graff, C. (2019). UCI Machine Learning Repository. Irvine, CA: University of California, School of Information and Computer Science).

## Challenge Objectives
- Conduct comprehensive data exploration and preparation.
- Identify predictive features to estimate the 'price_per_unit' label.
- Develop a regression model aiming for the highest accuracy.

## Methodology
- Application of regression models: Linear Regression, Decision Tree, Random Forest, Gradient Boosting, XGBoost.
- Initial preference for Random Forest due to its higher accuracy (72%).
- Subsequent development and integration of a preprocessing pipeline, yielding an accuracy of 71%.

## Results
- The refined model consistently predicts real estate prices with approximately 71% accuracy, underlining the complexity inherent in real estate market analysis.
