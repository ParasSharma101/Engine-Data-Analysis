# Engine Data Analysis

## Project Overview
This project involves analyzing engine performance data to identify patterns and relationships between various parameters. The dataset contains multiple features such as engine RPM, lubrication oil pressure, fuel pressure, coolant pressure, and temperature metrics.

## Dataset
The dataset used in this analysis is `engine_data.csv`, which includes the following key features:
- **Engine rpm**
- **Lub oil pressure**
- **Fuel pressure**
- **Coolant pressure**
- **Lub oil temp**
- **Coolant temp**
- **Engine Condition** (Target variable)

## Data Preprocessing
- Checked dataset information and unique values.
- Removed outliers using the interquartile range (IQR) method.
- Visualized key numerical features using box plots and histograms.

## Data Visualization
- Scatter plots to understand relationships between different parameters.
- Box plots to detect anomalies and outliers.
- Histograms to analyze the distribution of values.
- Correlation heatmap to find relationships among features.
- Pairplot to visualize pairwise relationships between numerical features.

## Model Training and Evaluation
Two machine learning models were trained on the dataset:

### **1. K-Nearest Neighbors (KNN) Classifier**
- **Accuracy Score:** 60.90%
- **F1 Score:** 71.17%

### **2. Random Forest Classifier**
- **Accuracy Score:** 65.54%
- **F1 Score:** 75.66%

The Random Forest model outperformed the KNN model in terms of accuracy and F1 score.

## Libraries Used
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical operations
- **Matplotlib & Seaborn**: Data visualization
- **Scikit-learn**: Machine learning model training and evaluation

## How to Run the Project
1. Install required dependencies:
   ```sh
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```
2. Load the dataset (`engine_data.csv`).
3. Preprocess and visualize the data.
4. Train and evaluate machine learning models.

## Conclusion
This project provides insights into engine performance data and applies machine learning models to predict engine conditions. The Random Forest model demonstrated better performance, suggesting its suitability for predictive maintenance applications.

