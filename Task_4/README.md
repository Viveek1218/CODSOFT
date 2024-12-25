# Sales Prediction Using Machine Learning

## Objective

This project aims to build a machine learning model that can effectively forecast future sales based on advertising spending across different platforms (TV, radio, and newspaper). By accurately predicting sales, businesses can make data-driven decisions to optimize their advertising strategies and ultimately increase their sales potential.

## Dataset

The project utilizes the "advertising" dataset, which contains information on advertising expenditures and corresponding sales figures. The dataset includes the following columns:

- **TV:** Advertising spending on TV (in thousands of dollars)
- **Radio:** Advertising spending on radio (in thousands of dollars)
- **Newspaper:** Advertising spending on newspaper (in thousands of dollars)
- **Sales:** Sales figures (in thousands of units)

The dataset is relatively small, with 200 observations and no missing or duplicated values. There aren't any considerable outliers present in the data.

## Model

A **Linear Regression** model was selected for this project due to its simplicity and ability to effectively capture linear relationships between variables. The model was trained on 80% of the dataset and tested on the remaining 20%.

## Summary

- The linear regression model demonstrates good performance with a high coefficient of determination (R²) of 0.90, indicating that it can explain approximately 90% of the variance in sales.
- The model's evaluation metrics, including a low mean squared error (MSE) of 2.91 and mean absolute error (MAE) of 1.27, suggest that its predictions are generally close to the actual sales figures.
- The analysis reveals that TV advertising has the most substantial impact on sales, followed by radio and newspaper advertising.
- Based on these findings, the model can be considered acceptable for predicting future sales based on advertising spending and can assist businesses in making informed decisions to optimize their advertising strategies.

## Conclusion

The Sales Prediction project successfully developed a reliable machine learning model for forecasting sales based on advertising expenditures. The model's strong predictive capabilities, coupled with its insights into the relationship between advertising and sales, can empower businesses to make data-driven decisions to maximize their sales potential.
