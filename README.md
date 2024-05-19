# Bike-Sharing-Demand-Forecasting-and-Optimization
Developed predictive models to forecast bike-sharing demand and optimized bike allocation strategies to enhance operational efficiency and user satisfaction in urban bike-sharing systems



# Introduction
The bike sharing project aims to analyze and predict bike demand patterns in a bike-sharing system. By leveraging machine learning techniques, the project seeks to optimize bike distribution and improve operational efficiency.

## Part 1: Data Cleaning and Exploration

* Analyzing Birth Year 1969 Entries: Investigate and clean data entries related to the birth year 1969.
* Data Cleaning and Visualization: Perform data cleaning operations, visualize key attributes, and identify any anomalies or inconsistencies.
* Basic Statistics and Visualization: Calculate summary statistics, visualize data distributions, and explore relationships between features.
* Correlation Analysis: Compute correlation matrix to analyze relationships between features and identify significant correlations.
* Data Standardization: Standardize data to ensure consistency and avoid scaling issues.

## Part 2: Prediction Challenge

* Clustering Analysis: Employ DBSCAN algorithm for clustering, evaluate silhouette scores, and select optimal parameter combinations.
* Cluster Analysis: Identify clusters with highest demand and analyze spatial distribution of bike pickups and drop-offs.
* Time Aggregation: Aggregate data into hourly intervals and compute mean/median values for continuous variables.
* Lagged Variables: Create lagged variables to capture temporal dependencies in bike demand.
* Prediction Models: Build linear regression and artificial neural network (ANN) models to predict bike drop-offs and pickups.
* Demand Prediction: Predict bike demand for the following day based on cumulative departures and arrivals.

## Part 3: Exploratory Challenge

* Station Grouping: Group stations based on demand levels and analyze spatial distribution of demand.
* New Dataset Integration: Integrate weather dataset or other relevant datasets to study their impact on bike demand.
* Seasonal Analysis: Analyze seasonal variations in bike demand and assess correlation with weather variables.
