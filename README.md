# Metro Train Data Mining Project

## Introduction

This repository contains the code and documentation for a data mining project focused on the Metro train dataset. The project involves various data analysis and modeling tasks to extract insights and make predictions based on the provided dataset.

## Dataset Overview

The MetroPT-3 Dataset comprises data collected from various sensors on a compressor's Air Production Unit (APU) within a metro train. This dataset presents practical predictive maintenance scenarios encountered in the industry, featuring readings from pressure, temperature, motor current, and air intake valves. It is a collection of multivariate time series data, obtained from both analog and digital sensors installed on the train's compressor.

The dataset consists of the following details:

- Total Entries: 1,516,948
- Columns: 17
- Data Types: Integer, Float, Object

## Project Steps

Here is an overview of the key steps undertaken in this project:

1. **Exploratory Data Analysis (EDA):** We began by conducting EDA to gain insights into the dataset. This involved summarizing statistics, identifying missing values, and exploring data distributions.

2. **Data Preprocessing:** Data preprocessing is critical to ensure the dataset is clean and ready for analysis. 
3. **Z-Score Normalization:** we applied Z-score normalization for analog sensors to standardize the data, making it suitable for further analysis and modeling.

4. **Data Visualization:** We utilized various visualization techniques like heatmaps and time series plots to visualize the data and identify patterns, correlations, and trends.

5. **Regression Model:** A Linear regression model was developed to predict oil temperature and motor current based on the sensor readings. We carefully examined heatmaps and correlations among all parameters, using these insights to choose the most relevant features for our models.

6. **Classification Model:** We built a logistic regression and Random Forest models for failure detection. This model can help identify potential failures or issues in the Metro train system by analyzing sensor readings.

## Contributors

- [Arnish Satasiya](https://github.com/arnishsatasiya) - 202001031
- [Jay Kuvadiya](https://github.com/JaYkuvadiya17) - 202001042
- [Jenish Mangukiya](https://github.com/MrJenish) - 202001176
- [Aastha Shetty](https://github.com/aasthashetty) - 202001260
- [Deep Kanani](https://github.com/202001454) - 202001454

