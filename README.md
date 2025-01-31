﻿# Integrated_Space_Risk_Management_System

## NEO-Detection

### Datasets

This project uses datasets from various sources like NASA, Amerigeoss, Kaggle, and Vizier to detect Near Earth Objects (NEOs) and classify them into hazardous and non-hazardous NEOs. The project therefore will work on 2 level classification:

### Details

1. The first level is binary classification, checking whether the detected data is that of an NEO or a non-NEO.
2. The second level will be binary classification, checking whether the detected NEO is hazardous or non-hazardous, if the first level classifies the object as an NEO.

### Results

-   Best accuracy: 99.9%
-   Model Used: Logistic Regression

## Solar Flare Prediction

### Datasets
1. DATA FROM DSCOVR SATELLITE
- Data collected from 2016
- Different magnitudes related to geomagnetic storms

2. DATA FROM EARTH’S MAGNETOMETERS
- Data from the Canadian Space Agency
- Relevant indices of Kp and Ap

### Details
- Time-series based data
- PlasMag data + Kp 
- Preprocessing 
- LSTM was used to predict Kp based on historical data
- Deployment using Streamlit
- Predictions 10-12 days in advance

### Results
- MSE: 0.010157716188031482
- F1 Score: 0.7096
