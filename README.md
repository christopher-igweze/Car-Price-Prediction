# CAR PRICE PREDICTION USING LINEAR REGRESSION
## by Igweze Ifeanyi


## Dataset

> This dataset contains information about used cars listed on different websites of shape 301 x 8 and 2 duplicated rows.


## Objective

> Create a good Linear Regression model to predict the selling prices of the test data.


## Summary of Findings & Actions

> The two main features with the highest correlation with the selling price where the Present Price and the Fuel Type Petrol (Gotten after encoding the Fuel Type column). Before creating the model I dropped the Car Name and Owner columns. 

## Key Insights

> From this, I created a Linear Reggression model with R2 score of 87.04% in the `main` branch, But in the `Dropped-duplicates` branch, I dropped the duplicated rows and had my R2 score drop to 75.81%
