[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/7lKBcjfN)
# 44-566 machine-learning project
Repo for all project documents

**Overview**  
This project aims to explore the relationship between house prices in New York City and their distance from Central Park. Initially, our goal was to predict house prices using linear regression based solely on the distance from Central Park. However, as the project evolved, we incorporated additional features such as the number of bedrooms, bathrooms, and square footage to enhance our model's accuracy. Through our analysis, we discovered the importance of considering multiple factors for accurate house price prediction.

### 2. RAW_DATA

**Data Acquisition**  
The dataset used in this project was obtained from [https://www.kaggle.com/datasets/nelgiriyewithana/new-york-housing-market]. The dataset contains information on house prices, bedrooms, bathrooms, square footage, and location coordinates. The raw data file can be found in this repository.

**Data Retrieval Notebook**  
For data acquisition and initial exploration, we used the following notebook: [Data Retrieval Notebook](initial_exploration.ipynb).

### 3. DATA

**Exploratory Data Analysis**  
Our explorations into the data involved cleaning, preprocessing, and visualizing the dataset. The transformations applied to the data are documented in the following notebook: [Data Exploration Notebook](linear_regression.ipynb).

### 4. ANALYSIS (Technical results)

**Model Analysis**  
We experimented with three classification models: DecisionTreeClassifier, SVC, and RandomForestClassifier. RandomForestClassifier emerged as the best-performing model with an accuracy of 0.63.

**Model Tuning and Evaluation**  
Details on model tuning and evaluation, including metrics from cross-validation, are documented in the following notebook: [Model Analysis Notebook](classification.ipynb).

**Challenges and Limitations**  
One challenge faced was the poor performance of linear regression, which led us to explore more complex models. A limitation of our study is the focus on a single major landmark (Central Park) for distance calculations.

**Improvements**  
Future improvements could include incorporating more features, considering multiple landmarks, and exploring advanced machine learning techniques for better predictive accuracy.

### 5. CONCLUSIONS (Narrative results)

**Main Findings**  
Our main finding was that proximity to Central Park significantly influences house prices, with closer houses generally priced higher. Additionally, considering features like bedrooms, bathrooms, and square footage improved our model's predictive power.

**Narrative Conclusion**  
Through this project, we learned that accurate house price prediction requires a holistic approach, considering both location and property attributes. The journey from initial linear regression attempts to the final RandomForestClassifier model highlighted the importance of iterative experimentation and feature engineering in data science projects.

---

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
    - Clustering techniques are applied to identify distinct groups of houses based on their features and proximity to the iconic landmark.
    - KMeans clustering is utilized to segment the dataset into clusters, and the clusters are visualized to interpret the groupings.
    - Insights from the clustering analysis can inform targeted marketing strategies and provide a deeper understanding of housing market dynamics.
    - Advanced regression and classifier tools like Random Forest and Neural Networks are employed to predict and classify housing prices and features.



**Next Steps:**
- Continue refining the modeling approach and exploring alternative algorithms to improve predictive performance.
- Evaluate the model's performance using test data and consider additional features or data sources that may enhance the analysis.
- Interpret the results effectively and draw insights into how distance from iconic landmarks impacts housing prices in New York City.
