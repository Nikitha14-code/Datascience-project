# Datascience- Final Project
---
## Project Title : ACCIDENT HOTSPOT DETECTION AND RISK PREDICTION

---

## Project Title:
**Accident Hotspot Detection and Risk Prediction**

---

## Project Description:
This project analyzes road traffic accident data to identify high-risk areas (hotspots), predict accident severity, and forecast future accident trends. Using clustering techniques, classification models, and time-series forecasting, the project provides actionable insights for policymakers to improve road safety and deploy resources effectively.

---

## Objectives:
1. Detect accident hotspots using clustering algorithms.
2. Predict accident severity levels based on environmental, vehicular, and demographic factors.
3. Forecast future accident trends to enable proactive safety measures.

---
## Technologies Used:
### - Programming Language: 
Python
### - Libraries:
  - Data Manipulation: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`, `plotly`
  - Machine Learning: `scikit-learn`, `XGBoost`
  - Time-Series Analysis: `statsmodels`, `tensorflow`

---

## Features:

#### - Classification:
  - Predicts accident severity using Logistic Regression, Random Forest, and XGBoost.
  - Evaluates models with precision, recall, F1-score, and confusion matrices.


### - Clustering:
  - Identifies accident hotspots using K-Means and DBSCAN clustering techniques.
  - Visualizes geospatial clusters with heatmaps and scatter plots.
  

### - Forecasting:
  - Forecasts accident trends with ARIMA and LSTM models.
  - Provides insights into temporal patterns and long-term dependencies.

---

## Dataset:
The datasets are obtained from the UK Department for Transport's road safety data:
1. **Casualty Dataset**: Demographic and severity details of casualties.
2. **Collision Dataset**: Geospatial and environmental information about accidents.
3. **Vehicle Dataset**: Details about vehicles involved in accidents.

### Dataset Preprocessing:
- Addressed missing values using imputation (mean, mode, and forward-fill techniques).
- Feature engineering for composite severity scores, time-based attributes, and urban indicators.
- Scaled and encoded features for machine learning models.

---

## Methodology:
### 1. Data Preprocessing:
   - Cleaning and merging datasets.
   - Feature extraction and dimensionality reduction.

### 2. Classification:
   - Trained Logistic Regression, Random Forest, and XGBoost models.
   - Performed hyperparameter tuning and feature importance analysis.

### 3. Clustering:
   - Applied K-Means and DBSCAN for hotspot detection.
   - Used the Elbow Method and k-distance graph for parameter tuning.

### 4. Forecasting:
   - Built ARIMA models for linear trend analysis.
   - Developed LSTM models for capturing long-term dependencies.

---

## Results:

### 1. Classification:
   - XGBoost achieved the best accuracy (82%) and balanced precision-recall metrics.
   - Weather conditions, road surface types, and time of day were significant predictors.

     
### 2. Clustering:
   - Identified 10 high-risk accident clusters, primarily in urban centers.
   - DBSCAN effectively captured irregularly shaped clusters and noise.


### 3. Forecasting:
   - ARIMA provided accurate short-term forecasts, while LSTM excelled in long-term trend prediction.

---

## Results Visualization:
### - Clustering Outputs: 
Geospatial heatmaps and scatter plots of accident hotspots.
### - Classification Metrics: 
Accuracy, precision, recall, and confusion matrices.
### - Forecasting Trends: 
Time-series plots comparing predicted vs. actual accident counts.

---

## Future Work:
1. Integrate real-time traffic and weather data for dynamic forecasting.
2. Explore lightweight models for faster deployment on edge devices.
3. Expand the scope to include rural areas and semi-urban regions.

---

## License:
This project is licensed under the MIT License.
