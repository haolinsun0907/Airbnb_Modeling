# Airbnb Barcelona Price Prediction: Data Science Project

## Overview

In this project, I embarked on an analytical journey to stage, clean, model, and predict prices for different room types for Airbnb listings in Barcelona, Spain, for the year 2019. The dataset consisted of over 6 million rows, documenting listings from the year 2018.

## Part 1: Data Staging and Cleaning

- **Data Standardization:** Ensured a consistent data format across the dataset, conducted necessary data type conversions, and reindexed data to facilitate seamless calculations.
- **Feature Extraction:** Zeroed in on room-specific details, extracting valuable insights regarding common housing amenities, user reviews, ratings, and more.
- **Data Pre-processing:** Leveraged one-hot encoding for categorical features, annotated the data, and meticulously removed outliers to ensure data integrity.
- **Visualization:** Presented a heatmap of all housing specifications, offering a comprehensive view of the data's structure and relationships, paving the way for effective modeling.

## Part 2: Data Modeling

### **Evaluation Metrics:**

- **Mean Square Error (MSE):** Employed MSE as the performance metric to assess the precision of the house price prediction model. A lower MSE indicates a more accurate model.
- **R-squared (r_2) Score:** Utilized the r_2 score from Sklearn to gauge the interpretability and robustness of the prediction model. A score closer to 1 suggests a more interpretable and robust model.

## Part 3: Price Prediction

- **Random Forest Regression:** Leveraged Sklearn's Random Forest regression to make well-informed price predictions.
- **Decision Tree Model with LightGBM:** Delved into advanced modeling using LightGBM (a sophisticated derivative of XGBoost) to further refine and enhance price predictions.

## Summary

By showcasing a thorough understanding of data science concepts and applying them to real-world data, this project exemplifies my commitment to extracting actionable insights from complex datasets.
