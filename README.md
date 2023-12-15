**Food Delivery Time Prediction using Spatial Analysis**
This repository contains code and resources for predicting food delivery times based on spatial analysis. The project uses data scraped from the original Zomato database, and spatial coordinates are generated using the Haversine formula. Additionally, the project includes visualizations using GeoPy to display different delivery locations.

**Overview**
The goal of this project is to leverage spatial analysis techniques to predict accurate food delivery times. The spatial analysis involves calculating distances between restaurant locations and delivery destinations, using the Haversine formula to account for the curvature of the Earth.

Three different models have been implemented to predict delivery times, and their performance is compared. The models are trained on the dataset derived from Zomato's restaurant and delivery data, including spatial coordinates.

**Key Components**
Data Collection:

Zomato data is scraped to gather information about restaurants, their locations, and historical delivery times.
Spatial Analysis:

Spatial coordinates are generated using the Haversine formula, enabling precise distance calculations between restaurant and delivery locations.
**Modeling:**

Three different models are implemented for predicting delivery times. The code for each model is organized in separate directories.
**Visualization:**

GeoPy is utilized for visualizing delivery locations on maps, providing insights into the spatial distribution of food deliveries.
**Models**
The repository includes implementations of the following models:

Model 1: Linear Regression
Model 2: Random Forest
Model 3: Long Short-Term Memory (LSTM)
Each model is accompanied by a Jupyter Notebook that explains the training process, model evaluation, and predictions.
