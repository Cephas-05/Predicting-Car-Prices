# Car Price Prediction with Mean Encoding

## Overview

This project builds a **regression model to predict car prices** using machine learning. The focus of the project was improving model performance through **feature engineering**, specifically by applying **mean encoding** to a categorical variable.

## Objective

Predict the **price of a car** based on its features and improve prediction accuracy by transforming categorical data into more meaningful numerical representations.

## Key Steps

1. **Data Preprocessing**

   * Cleaned the dataset
   * Handled missing values
   * Selected relevant features

2. **Feature Engineering**

   * Created a new feature called **`model_encoding`**
   * This feature represents the **average price of each car model**
   * Helps the model capture the relationship between car models and their typical market price

3. **Model Training**

   * Trained a regression model using the processed features
   * Compared model performance before and after feature engineering

4. **Model Evaluation**

   * Evaluated using **R² score**
   * Performed **residual analysis**
   * Checked error distribution using:

     * Residual histogram
     * Q-Q probability plot

## Results

* **Baseline Model R²:** ~0.70
* **Improved Model R²:** **0.8848**

Mean encoding significantly improved the model's ability to capture pricing patterns.

## Residual Analysis

Residual diagnostics show that:

* Errors are centered around **zero**, indicating minimal bias
* Residuals are **approximately normally distributed**
* Some deviations in the tails suggest the presence of outliers

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Seaborn
* Matplotlib
* SciPy

## Conclusion

Applying **mean encoding to the model feature significantly improved predictive performance**, increasing the model's explanatory power from **70% to about 88%**. This demonstrates how effective **feature engineering** can be in improving machine learning models.

## Author

Chad
