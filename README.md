# NASA Nearest Earth Objects Project

## Team Members:
- Venkata Lakshman Nimmagadda
- Gayathri Kaparthi
- Ram Sai Nimmagadda
- Deekshith Kumar Singirikonda
- Surya Vamsi Chandradhar Sidda

## Introduction of Project:
Group 17 is analyzing the NASA Nearest Earth Objects (NEO) dataset, which spans from 1910 to 2024. This dataset includes comprehensive observations of NEOs, detailing their size, velocity, and distance from Earth. Our objective is to develop predictive models to assess the hazard level of these objects and determine their potential threat to Earth. This will involve using supervised learning methods, particularly binary classification, to predict whether an NEO is hazardous.

### Goals:
- **Descriptive**: Explore the attributes and distribution of NEOs.
- **Predictive**: Build models to classify NEOs as hazardous or non-hazardous.
- **Methods**: Utilize classification techniques such as logistic regression and tree-based models.

## Problem Understanding:
The goal is to identify and predict which NEOs pose a potential hazard to Earth based on their attributes. Accurate prediction is crucial for assessing potential risks and preparing for possible asteroid impacts.

## Research Question:
Can we predict with high accuracy whether a NEO is hazardous based on its physical and orbital characteristics?

## Data Understanding:
The dataset contains 338,199 records of NEOs and includes the following features:
- `neo_id`: Unique Identifier for each Asteroid
- `name`: Name given by NASA
- `absolute_magnitude`: Describes intrinsic luminosity
- `estimated_diameter_min`: Minimum Estimated Diameter (in km)
- `estimated_diameter_max`: Maximum Estimated Diameter (in km)
- `orbiting_body`: Planet that the asteroid orbits
- `relative_velocity`: Velocity Relative to Earth (in km/h)
- `miss_distance`: Distance missed (in km)
- `is_hazardous`: Boolean indicating whether the asteroid is harmful or not

[Dataset on Kaggle](https://www.kaggle.com/datasets/ivansher/nasa-nearest-earth-objects-1910-2024)

### Dataset Insights:
- **Size**: The dataset is large, with over 338,000 entries.
- **Attributes**: Includes numeric and categorical features related to asteroid characteristics.
- **Label Distribution**: 
  - Hazardous (True): 43,162
  - Non-Hazardous (False): 295,037

## Data Preparation:
The data preparation will involve:
- Removing irrelevant columns (`neo_id`, `name`) and addressing missing values.
- Normalizing numerical features (`absolute_magnitude`, `relative_velocity`, `miss_distance`).
- Handling class imbalance in the `is_hazardous` feature by applying techniques such as resampling or using class weights.

### Data Exploration:
- Visualize distributions of key features.
- Analyze correlations between features and the `is_hazardous` label.
- Identify patterns and outliers that could impact model performance.

### Modeling and Evaluation:
- Develop and train classification models to predict the hazard level of NEOs.
- Evaluate models using metrics such as accuracy, precision, recall, and F1 score.
- Compare different models to select the most effective one.

### Conclusion:
Our research aims to enhance the prediction of NEO hazards by utilizing various machine learning techniques, providing insights into which features are most indicative of potential threats.
