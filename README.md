[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/7lKBcjfN)
# 44-566 machine-learning project
Repo for all project documents

### Project Overview

**Objective:**
The primary objective of this project was to investigate the potential relationship between rat sightings and housing prices in New York City.

**Approach:**
Initially, the plan was to use latitude and longitude coordinates as reference points for both datasets and explore spatial patterns. However, during the data preparation phase, it was challenging to use longitude and latitude effectively. Therefore, the decision was made to utilize zip codes as a proxy for location.

**Notebooks:**

1. **initial_exploration.ipynb:**
   - This notebook focused on the initial exploration of the datasets.
   - Columns were dropped except for those relevant to the analysis (e.g., price, zip code).
   - Zip codes were extracted from the `MAIN_ADDRESS` column in the NY-House-Dataset.csv file.
   - The datasets were merged to incorporate the count of rat sightings by zip code and house prices.

2. **linear_regression.ipynb:**
   - Linear regression was performed to predict the count of rat sightings based on housing prices.
   - However, the model yielded a high Mean Squared Error (MSE) and a very low R-squared score, indicating poor predictive performance.

### Next Steps:
- Further exploration is needed to improve predictive performance, potentially by incorporating additional features or utilizing alternative modeling techniques.
- The project will continue with an emphasis on refining the modeling approach and interpreting the results effectively.