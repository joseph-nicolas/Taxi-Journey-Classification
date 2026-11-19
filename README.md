# Urban Transport & Traffic Data Analysis
This repository contains a collection of machine learning models applied to urban transport datasets. The project is divided into three primary analyses: classifying taxi journey lengths, clustering traffic incidents geographically in the UAE, and predicting the coordinates of traffic incidents using regression models.

## Project Components

### 1. Taxi Journey Classification
*   **Dataset:** RTA Anonymous Journeys.
*   **Goal:** Classify taxi trips as "short" (<5 km) or "long" (>=5 km) based on start/end coordinates and distance.
*   **Models Used:** Support Vector Machine (SVM) with a linear kernel, and k-Nearest Neighbors (k-NN).
*   **Results:** Both models achieved exceptionally high accuracy (approx. 99.9%).

### 2. Traffic Incidents Clustering
*   **Dataset:** UAE Traffic Incidents.
*   **Goal:** Identify spatial patterns and hotspots by clustering the geographic coordinates (latitude/longitude) of traffic accidents.
*   **Models Used:** K-Means (optimized using K-Fold cross-validation and silhouette scores) and DBSCAN.
*   **Visualization:** Includes interactive Folium heatmaps and scatter plots of the clusters.

### 3. Traffic Incident Coordinate Regression
*   **Dataset:** UAE Traffic Incidents.
*   **Goal:** Predict the exact (X, Y) geographic coordinates of a traffic incident based on temporal features (hour, day, weekday) and the type of accident.
*   **Models Used:** Decision Tree Regressor, Random Forest Regressor, and Linear Regression.

## Tech Stack & Libraries
This project is built using Python and utilizes the following core libraries:
*   **Data Processing:** `pandas`, `numpy`
*   **Machine Learning:** `scikit-learn`
*   **Visualization:** `matplotlib`, `seaborn`, `folium`

## Getting Started
To run the notebooks, you will need to install the required dependencies:
`pip install pandas numpy scikit-learn matplotlib seaborn folium`

*Note: The datasets (`RTA_Anonymous_Journies.csv` and `Traffic_Incidents.csv`) must be placed in the same directory as the notebooks for the notebooks to run properly.*

## 👥 Authors
*   **Yasser**
*   **Joseph**
*   **Liana**
