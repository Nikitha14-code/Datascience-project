# Datascience- Final Project

## Project Title : ACCIDENT HOTSPOT DETECTION AND RISK PREDICTION

### Introduction:
This project analyzes road accident data collected over the last five years to identify patterns, assess risk factors, and detect high-risk accident zones. The analysis includes:

Cleaning and pre-processing datasets.

Deriving meaningful features like accident severity and clustering hotspots.

Conducting exploratory data analysis (EDA) to visualize trends.

### Loading Datasets
Dependencies
Ensure the following Python libraries are installed:

pandas

numpy

matplotlib

seaborn

plotly

scikit-learn

Setup

Clone this repository or download the code files.

Upload datasets to your Google Drive for access.

Use Google Colab or a local Python environment.

### Dataset Description
#### 1. Casuality Dataset
Contains details about individuals involved in accidents, including:

Severity

Age group

Gender

Casuality class (e.g., pedestrian, driver)

#### 2. Collision Dataset
Provides location and contextual information for accidents:

GPS coordinates

Date and time

Weather and light conditions

#### 3. Vehicle Dataset
Contains details about vehicles involved:

Vehicle type

Direction of travel

### Project Workflow
#### 1. Importing Libraries
We import essential libraries for data manipulation (pandas), numerical operations (numpy), and visualization (matplotlib, seaborn, plotly). Warnings are suppressed to enhance readability.

##### 2. Loading Datasets
Datasets are loaded from Google Drive after mounting.

#### 3. Dataset Exploration
Basic exploration includes checking the structure, data types, and summary statistics.

#### 4. Pre-processing
##### Step 4.1: Identify Missing Values
Columns with missing values are identified.
##### Step 4.2: Drop Columns
Columns with excessive missing data in the vehicle dataset are removed.
##### Step 4.3: Impute Missing Values
Missing values in the collision dataset are filled with mean values.

#### 5. Merging Datasets
The datasets are merged on the accident_index column for comprehensive analysis.

#### 6. Feature Engineering
##### Step 6.1: Extract Temporal Features
Dates are converted into day, month, and year features.
##### Step 6.2: Create Composite Severity Score
A weighted severity score is calculated.
##### Step 6.3: Simplify Features
Weather and light conditions are simplified for easier interpretation.

#### 7. Clustering for Hotspot Detection
KMeans is used to cluster accident locations into high-risk areas.

#### 8. Exploratory Data Analysis (EDA)
The data is visualized using plotly for interactive plots.

Casualty Severity Distribution

Casualty by Age Group

Casualty Class by Gender

Accidents by Hour, Day, Month, and Year

Severity Score Distribution

Severity Score by Weather Condition
