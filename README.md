
# Washington State Earthquake Analysis and Prediction (1904-2024)

## Project Overview

This project analyzes and predicts earthquake activities in Washington State using historical data from 1904 to 2024. The dataset, sourced from the United States Geological Survey (USGS), provides a comprehensive record of seismic events, allowing for detailed analysis and predictive modeling of future earthquakes.

### Key Objectives:

1. **Identify Most Affected Cities:**
   - Analyze which cities in Washington State have been most impacted by earthquakes.
   
2. **Plot Historical Earthquake Data with Fault Lines:**
   - Visualize earthquake data on a map of Washington State alongside known fault lines.
   
3. **Statistical Analysis:**
   - Explore the frequency, magnitude distributions, and depth of earthquakes.
   
4. **Predict Future Earthquake Probabilities:**
   - Use machine learning models to predict the likelihood of future earthquakes based on historical data.

## Project Structure

### 1. Data Exploration
- **Data Description & Loading:** Understanding the dataset and loading it into the environment.
- **Initial Data Analysis:** Explore basic statistics and identify key features of the data.

### 2. Exploratory Data Analysis (EDA)
- **Data Cleaning & Preparation:** Handle missing values, outliers, and derive new features.
- **Univariate & Multivariate Analysis:** Explore relationships between variables and analyze temporal patterns.

### 3. Temporal Analysis
- **City Analysis:** Identify cities with the highest and lowest frequencies of earthquakes.
- **Time Analysis:** Analyze patterns over time, including time of day and year trends.

### 4. Spatial Analysis
- **Location Visualization:** Map earthquake epicenters and compare with fault lines.
- **Geospatial Analysis:** Use Moran’s I and other geostatistical techniques to identify spatial patterns.

### 5. Machine Learning Models

#### Regressive Models
- **Model Preparation:** Data preprocessing for regressive modeling.
- **Various Models:** Implement MLPRegressor, AdaBoostRegressor, and TensorFlow models.
- **Ensemble Methods:** Use ensemble techniques to improve predictions.

#### Classifier Models
- **Model Preparation:** Data preprocessing for classification tasks.
- **Various Models:** Implement RandomForestClassifier, MLPClassifier, and various ensemble methods.
- **Performance Evaluation:** Assess model performance using accuracy, mean squared error, and classification reports.

### 6. Prediction and Visualization
- **Earthquake Probability Mapping:** Visualize predictions on a map of Washington State.
- **Combined Layer Analysis:** Integrate different layers of data for comprehensive insights.

### 7. Final Analysis
- **Summary of Findings:** Discuss key insights and implications for future research and policy.

## Dependencies

The project requires the following libraries:

- **Data Handling:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`, `folium`, `geopandas`
- **Machine Learning:** `scikit-learn`, `tensorflow`
- **Geospatial Analysis:** `libpysal`, `esda`, `shapely`
- **Miscellaneous:** `warnings`

To install all dependencies, run:
```bash
pip install pandas numpy matplotlib seaborn folium geopandas scikit-learn tensorflow libpysal esda shapely
```

## Usage

1. **Load the Data:**
   Place the dataset (`WA_Earthquake_data.csv`) in the designated directory and run the notebook cells to load and preprocess the data.

2. **Run the Analysis:**
   Follow the sequential steps in the notebook to perform EDA, statistical analysis, and machine learning.

3. **Visualize the Results:**
   Use the visualization sections to view earthquake patterns, prediction maps, and other insights.

4. **Model Predictions:**
   Experiment with different models and parameters to optimize predictions for future earthquake probabilities.

## Dataset

The dataset used in this project is sourced from the [United States Geological Survey (USGS)](https://www.usgs.gov/). It includes records of earthquakes in Washington State from 1904 to 2024, detailing attributes such as magnitude, depth, and location.

## References

1. United States Geological Survey (USGS) - [Earthquake Data](https://www.usgs.gov/)
2. Scikit-learn Documentation - [Scikit-learn](https://scikit-learn.org/)
3. TensorFlow Documentation - [TensorFlow](https://www.tensorflow.org/)

## Acknowledgments

This project is developed as part of a comprehensive analysis and predictive modeling study of seismic activities in Washington State. Special thanks to the USGS for providing access to the earthquake dataset.
