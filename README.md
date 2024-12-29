# Datascience- Final Project
---
## Project Title : ACCIDENT HOTSPOT DETECTION AND RISK PREDICTION

---

#### Project Title:
**Accident Hotspot Detection and Risk Prediction**

---

#### Project Description:
This project analyzes road traffic accident data to identify high-risk areas (hotspots), predict accident severity, and forecast future accident trends. Using clustering techniques, classification models, and time-series forecasting, the project provides actionable insights for policymakers to improve road safety and deploy resources effectively.

---

#### Objectives:
1. Detect accident hotspots using clustering algorithms.
2. Predict accident severity levels based on environmental, vehicular, and demographic factors.
3. Forecast future accident trends to enable proactive safety measures.

---

#### Features:
### - Clustering:
  - Identifies accident hotspots using K-Means and DBSCAN clustering techniques.
  - Visualizes geospatial clusters with heatmaps and scatter plots.
  
#### - Classification:
  - Predicts accident severity using Logistic Regression, Random Forest, and XGBoost.
  - Evaluates models with precision, recall, F1-score, and confusion matrices.

### - Forecasting:
  - Forecasts accident trends with ARIMA and LSTM models.
  - Provides insights into temporal patterns and long-term dependencies.

---

#### Dataset:
The datasets are obtained from the UK Department for Transport's road safety data:
1. **Casualty Dataset**: Demographic and severity details of casualties.
2. **Collision Dataset**: Geospatial and environmental information about accidents.
3. **Vehicle Dataset**: Details about vehicles involved in accidents.

##### Dataset Preprocessing:
- Addressed missing values using imputation (mean, mode, and forward-fill techniques).
- Feature engineering for composite severity scores, time-based attributes, and urban indicators.
- Scaled and encoded features for machine learning models.

---

#### Methodology:
### 1. Data Preprocessing:
   - Cleaning and merging datasets.
   - Feature extraction and dimensionality reduction.

### 2. Clustering:
   - Applied K-Means and DBSCAN for hotspot detection.
   - Used the Elbow Method and k-distance graph for parameter tuning.

### 3. Classification:
   - Trained Logistic Regression, Random Forest, and XGBoost models.
   - Performed hyperparameter tuning and feature importance analysis.

### 4. Forecasting:
   - Built ARIMA models for linear trend analysis.
   - Developed LSTM models for capturing long-term dependencies.

---

#### Results:
### 1. Clustering:
   - Identified 10 high-risk accident clusters, primarily in urban centers.
   - DBSCAN effectively captured irregularly shaped clusters and noise.

### 2. Classification:
   - XGBoost achieved the best accuracy (89%) and balanced precision-recall metrics.
   - Weather conditions, road surface types, and time of day were significant predictors.

### 3. Forecasting:
   - ARIMA provided accurate short-term forecasts, while LSTM excelled in long-term trend prediction.

---

#### Technologies Used:
### - Programming Language: Python
### - Libraries:
  - Data Manipulation: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`, `plotly`
  - Machine Learning: `scikit-learn`, `XGBoost`
  - Time-Series Analysis: `statsmodels`, `tensorflow`

---

#### Installation and Setup:
### 1. Clone the repository:
   ```
   git clone https://github.com/username/accident-hotspot-detection.git
   cd accident-hotspot-detection
   ```
### 2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
### 3. Ensure the `data/` directory contains the required datasets.

---

#### Usage:
### 1. Exploratory Data Analysis:
   - Run the `EDA.ipynb` notebook to explore the datasets and their features.
   
### 2. Clustering:
   - Execute the `clustering_analysis.ipynb` notebook to generate hotspot visualizations.
   
### 3. Classification:
   - Use the `classification_models.ipynb` notebook to train and evaluate severity prediction models.
   
### 4. Forecasting:
   - Open `forecasting_models.ipynb` to predict future accident trends.

---

#### Results Visualization:
### - Clustering Outputs: 
Geospatial heatmaps and scatter plots of accident hotspots.
### - Classification Metrics: 
Accuracy, precision, recall, and confusion matrices.
### - Forecasting Trends: 
Time-series plots comparing predicted vs. actual accident counts.

---

#### Future Work:
1. Integrate real-time traffic and weather data for dynamic forecasting.
2. Explore lightweight models for faster deployment on edge devices.
3. Expand the scope to include rural areas and semi-urban regions.

---

#### License:
This project is licensed under the MIT License.
