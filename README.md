# Traffic Dynamics ML Project

## Overview

This repository contains an analysis of traffic dynamics within six fictional futuristic cities, leveraging a dataset comprising over 1.2 million records. 

### Dataset Description
The dataset is a simulated study reflecting the challenges of traffic management in futuristic urban settings.

It includes:

- Vehicle Types: Cars, autonomous vehicles, drones, and flying cars.
- Weather Conditions: From clear skies to snow and solar flares.
- Economic Conditions: Ranging from booming to recession.
- Traffic Dynamics: Speed, energy consumption, traffic density.
- etc.

### Methods Used
- **Data Preprocessing**: Handling categorical data, missing values, and splitting the dataset.
- **Exploratory Data Analysis**: Using histograms, scatter plots, and bar charts to understand data distribution.
- **Machine Learning Models**:
  - **Linear Regression**: To establish a baseline.
  - **Decision Tree and Random Forest Regressors**: For capturing non-linear relationships and feature importance.
  - **Gradient Boosting and Elastic Net**: To improve prediction accuracy.

## Repository Content

- **ProjectSubmission.ipynb**: Contains the main project report, findings, and conclusions.
- **Traffic Flow and Energy Consumption.ipynb**: Offers additional modeling and detailed analysis regarding traffic flow and energy consumption.

-  **futuristic_city_traffic.csv**: Dataset used for the analysis.

## File Setup and Execution

Both notebooks are fully self-contained, with all necessary code and markdown annotations to guide you through the traffic dynamics analysis. Instructions for using these notebooks are as follows:

### ProjectSubmission.ipynb:

- This notebook serves as the core of the project, featuring the complete analysis from data preprocessing to advanced modeling.
- It includes detailed visualizations, model evaluations, and our final conclusions.
- To view the results, open this notebook in your Jupyter Notebook environment and run each cell sequentially from top to bottom. Ensure all cells are executed to replicate the results and figures presented in the analysis.

### Traffic Flow and Energy Consumption.ipynb:

- This supplemental notebook focuses on specific aspects of traffic flow and energy consumption, providing deeper insights into these areas.
- It includes specialized analyses such as time series predictions and the impact of specific events on traffic patterns.
- Like the main notebook, open this in Jupyter Notebook and execute all cells in order to view the complete analysis and derive results.

## ``My Contributions:``

- **Exploratory Data Analysis (EDA)**:

  - Led the comprehensive Exploratory Data Analysis (EDA) for the project across two main files: the project.ipynb and the supplemental traffic flow and energy consumption.ipynb. This involved detailed data examination and preparation to ensure robust modeling and insights.

- **In-Depth Modeling and Analysis in Supplemental File**: Conducted extensive modeling analyses focused on the interaction between traffic density and energy consumption, including:

  - ``Variability Analysis``: Differentiated traffic behaviors between weekdays and weekends, providing clear visualizations and insights into daily and hourly variations.
  - ``Time Series Analysis``: Developed simulated time series models to forecast short-term traffic changes and energy usage patterns (for both sections *Traffic Density vs Hour of Day* and *Energy Consumption vs Traffic Density*)
  - ``Special Events Impact Analysis``: Assessed how special events influence traffic density, using data visualization to underscore significant deviations and patterns. Outliers detected possible special events
  - ``Predictive Modeling for Traffic Density``: Implemented and evaluated predictive models to forecast near-future traffic conditions


- **Core Project File Contributions**:

    - ``EDA Execution``: Spearheaded the initial data exploration, including generating histograms, bar plots, scatter plots, and two sets of correlation heatmaps (one inclusive of categorical features and another restricted to numerical features).
    - ``Top Correlations Analysis``: Identified and visually represented the top five correlations from the heatmap, applying linear fit line (using np.polyfit() ) to highlight their predictive relevance.
    - ``Baseline Linear Regression Model``: Developed the baseline predictive model without regularization, crafted and analyzed the actual vs. predicted results plot to establish a performance benchmark.
    - ``Decision Tree Improvement Modeling``: Enhanced model complexity by implementing Decision Tree models at two depths (5 and 10), including visualizations of actual vs. predicted outcomes and feature importance extraction for critical insight generation.
    - ``Hyperparameter Tuning``: Optimized Decision Tree parameters using RandomizedSearchCV, followed by detailed visual analysis of parameter impacts on model performance.
    
- **Documentation and Reporting**:

    - Authored and edited sections of the project report, including dataset characteristics, baseline results, improvement model analysis, and the comprehensive experiments and conclusions section. 

