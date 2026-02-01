# Crime Pattern Detection, Analysis & Prediction using Machine Learning

## Overview
This project focuses on analyzing, visualizing, and predicting crime patterns using machine learning techniques. By leveraging historical crime data, the system identifies high-risk crime hotspots, forecasts future crime trends, and classifies crime types to assist law enforcement agencies in proactive decision-making and efficient resource allocation.

---

## Objectives
- Analyze historical crime data to uncover hidden patterns  
- Identify crime hotspots using clustering techniques  
- Predict future crime trends using time-series forecasting  
- Classify crime types using supervised learning models  
- Support proactive and data-driven policing strategies  

---

## Dataset
- **Source**: Toronto Police Service – Public Safety Portal  
- **Key Features**:
  - Occurrence date & reporting date  
  - Neighborhood / location  
  - Type of offense  
  - Major Crime Indicators (MCI)

---

## Machine Learning Techniques Used

### 🔹 Clustering (Spatial Analysis)
- **Algorithm**: K-Means  
- **Purpose**: Identify crime hotspots  
- **Validation**: Elbow Method, Silhouette Score  

### 🔹 Time Series Forecasting (Temporal Analysis)
- **Models**: ARIMA, SARIMA  
- **Purpose**: Predict future crime trends and seasonal patterns  

### 🔹 Classification (Categorical Analysis)
- **Model**: Random Forest Classifier  
- **Task**: Predict crime type  
- **Accuracy Achieved**: ~58.38%  

### 🔹 Dimensionality Reduction
- **Technique**: Principal Component Analysis (PCA)  
- **Purpose**: Improve clustering efficiency and visualization  

---

## System Workflow
1. Data Collection  
2. Data Preprocessing & Encoding  
3. Exploratory Data Analysis (EDA)  
4. Crime Hotspot Detection (Clustering)  
5. Crime Trend Forecasting  
6. Crime Type Classification  
7. Visualization & Evaluation  

---

## Technologies Used
- **Language**: Python  
- **Libraries**:  
  - pandas, numpy  
  - matplotlib, seaborn  
  - scikit-learn  
  - statsmodels  
- **Environment**: Jupyter Notebook  

---

## Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Silhouette Score (for clustering)  

---

## Results
- Successfully identified high-crime neighborhoods  
- Forecasted crime trends with seasonal variations  
- Classified crime types with reasonable accuracy  
- Visualized crime patterns using heatmaps and graphs  

---

## Future Enhancements
- Integration of real-time crime data  
- Use of deep learning models (LSTM) for forecasting  
- Inclusion of socioeconomic and behavioral features  
- Deployment as a web-based dashboard for law enforcement  

---

## License
This project is intended for academic and research purposes.
