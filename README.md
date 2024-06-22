# Lead Prediction System

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Methodology](#methodology)
- [Results](#results)
- [Acknowledgments](#acknowledgments)

## Project Overview
The Lead Prediction System is developed for a mid-size private bank, "World Plus", to enhance their marketing efforts by accurately identifying prospective customers who are most likely to convert and purchase a new term deposit product. This system aims to reduce marketing costs by targeting potential leads effectively and avoiding expenditure on uninterested customers.

## Features
- Predictive modeling to identify potential leads
- Data preprocessing and cleaning
- Implementation of multiple machine learning algorithms
- Evaluation and comparison of model performance
- Visualization of results

## Methodology
The project follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology which includes:

1. **Business Understanding**: Understanding the project objectives and requirements from a business perspective.
2. **Data Understanding**: Collecting initial data and identifying data quality issues.
3. **Data Preparation**: Cleaning and transforming data for modeling.
4. **Modeling**: Applying various machine learning algorithms to build predictive models.
5. **Evaluation**: Assessing the models to determine the best performing one.
6. **Deployment**: Deploying the final model to predict leads.

### Detailed Steps

#### Data Preparation
- Data cleaning and preprocessing using libraries such as `tidyverse`, `dplyr`, and `mice`.
- Handling class imbalance using techniques like SMOTE (Synthetic Minority Over-sampling Technique) from the `performanceEstimation` package.

#### Modeling
- Implemented various models including Decision Trees (`C50`), Linear Discriminant Analysis (`MASS`), Support Vector Machines (`e1071`), and Random Forests (`randomForest`).
- Feature selection performed using `FSelector`.

#### Evaluation
- Models evaluated using ROC curves and other performance metrics from the `pROC` package.
- Cumulative gain charts generated using `CustomerScoringMetrics`.

## Results
The lead prediction model achieved significant accuracy in identifying prospective customers who are likely to convert. The final report and presentation detailing the results showcase the effectiveness of the predictive models used and provide strategic insights for targeted marketing.

## Acknowledgments
This project was completed as part of the Analytics in Practice course at Warwick Business School. Special thanks to the course instructors and my project team for their support and collaboration.
