# Diabetes Health Indicators Analysis and Visualization
## Overview

This project focuses on analyzing and visualizing health indicators related to diabetes using a dataset from the Behavioral Risk Factor Surveillance System (BRFSS) 2015. The goal is to explore the relationship between various health factors and diabetes, providing insights that can help in understanding and potentially predicting diabetes risk.

**Dataset**
The dataset used in this project is diabetes_binary_health_indicators_BRFSS2015.csv, which contains 22 health-related features and a binary target variable indicating the presence or absence of diabetes. The dataset includes features such as high blood pressure, high cholesterol, BMI, smoking status, physical activity, and more.

## Key Features
**Data Loading and Exploration:** The dataset is loaded and explored to understand its structure and contents.

**Data Cleaning and Preparation:** Columns are renamed for better readability, and the target variable is mapped to more descriptive labels.

## Visualizations:

Diabetes vs. BMI Distribution: A box plot showing the distribution of BMI for diabetic and non-diabetic individuals.

High Blood Pressure & Diabetes: A count plot illustrating the relationship between high blood pressure and diabetes status.

Insights: The visualizations provide meaningful insights into how certain health indicators correlate with diabetes.

### Libraries Used
**Pandas:** For data manipulation and analysis.

**Matplotlib:** For creating static visualizations.

**Seaborn:** For creating more attractive and informative statistical graphics.

## Insights
**BMI and Diabetes:** The box plot reveals that individuals with diabetes tend to have a higher BMI compared to those without diabetes. This suggests that BMI could be a significant factor in diabetes risk.

**High Blood Pressure and Diabetes:** The count plot shows a higher prevalence of diabetes among individuals with high blood pressure, indicating a potential link between these two health conditions.

### Future Work
Machine Learning Models: Implement machine learning models to predict diabetes based on the health indicators.

Additional Visualizations: Explore more visualizations to uncover other potential risk factors for diabetes.

Interactive Dashboards: Create interactive dashboards using tools like Plotly or Dash for more dynamic data exploration.

### Contributions are welcome! Please feel free to fork the repository, make changes, and submit a pull request.
