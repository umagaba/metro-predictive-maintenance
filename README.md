# Predictive Maintenance for Metro Train Systems

This project builds machine learning models to detect anomalies and predict failures in metro train **Air Production Units (APU)** using time-series sensor data.

## Dataset
<img width="355" height="203" alt="image" src="https://github.com/user-attachments/assets/aeaa42ef-8cac-45c0-aa0f-1dc09cacaf4d" />

MetroPT dataset

- ~10 million sensor records
- 21 features
- Multivariate time-series data
- Fault types include air leaks and compressor failures

## Tasks
<img width="353" height="197" alt="image" src="https://github.com/user-attachments/assets/f078af29-3f77-4049-94e6-3e0d7ccd735a" />

1. Fault Detection (Classification)
2. Remaining Useful Life Prediction (Regression)

## Models

### Fault Detection
- Random Forest

Performance:
- Accuracy: **99.4%**
- F1 Score: **~97%**

### RUL Prediction
- LSTM
- XGBoost

## Explainability

Used **SHAP** to analyze feature importance and model behavior.

## Pipeline

1. Data preprocessing
2. Feature engineering
3. Time-series sequence generation
4. Model training
5. Evaluation and explainability

## Tech Stack

Python  
Scikit-learn  
XGBoost  
TensorFlow / PyTorch  
SHAP  
Pandas  
NumPy
