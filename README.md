[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/7lKBcjfN)
# 44-566 machine-learning project
Repo for all project documents

### Project Overview

**Objective:**
The primary objective of this project is to investigate how housing prices in New York City are affected by their distance from an iconic landmark, such as Times Square.
~~The primary objective of this project was to investigate the potential relationship between rat sightings and housing prices in New York City.~~

**Approach:**
In this iteration of the project, we are focusing on exploring the relationship between housing prices and distance from the iconic landmark. We are using a dataset containing information about house prices in New York City, including the number of bedrooms, bathrooms, property square footage, and geographic coordinates (latitude and longitude). We are also considering the distance of each house from the iconic landmark as a feature.
~~Initially, the plan was to use latitude and longitude coordinates as reference points for both datasets and explore spatial patterns. However, during the data preparation phase, it was challenging to use longitude and latitude effectively. Therefore, the decision was made to utilize zip codes as a proxy for location.~~

**Notebooks:**

1. **initial_exploration.ipynb:**
    - This notebook focuses on preparing the dataset for analysis.
    - We load the NY-House-Dataset.csv file and perform initial data exploration.
    - Columns are examined and relevant features are selected, including the number of bedrooms, bathrooms, property square footage, latitude, and longitude.
    - We calculate the distance of each house from the iconic landmark (e.g., Times Square) using geographic coordinates.

2. **linear_regression.ipynb:**
    - Linear regression and potentially other modeling techniques are applied to predict house prices based on the selected features, including the distance from the iconic landmark.
    - Evaluation metrics such as RMSE, MAE, and R-squared score are computed to assess the model's performance.
    - Alternative algorithms and feature engineering approaches may be explored to improve predictive accuracy.
  
3. **classification.ipynb:**
    - This notebook explores the classification aspect of the project.
    - We aim to classify houses based on their price range or other categorical labels.
    - Initial data preprocessing, feature selection, and model training steps are conducted.
    - Evaluation metrics for classification models will be computed to assess performance.


**Next Steps:**
- Continue refining the modeling approach and exploring alternative algorithms to improve predictive performance.
- Evaluate the model's performance using test data and consider additional features or data sources that may enhance the analysis.
- Interpret the results effectively and draw insights into how distance from iconic landmarks impacts housing prices in New York City.
