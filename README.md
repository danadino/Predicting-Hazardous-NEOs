# Predicting-Hazardous-NEOs
Predicting Hazardous NEOs
Dataset Specifications:
File: nearest-earth-objects(1910-2024).csv
Records: 338,199
Features: 9
Memory Usage: 21.0+ MB
Format: CSV

Implementation Details
Data Preprocessing

Missing Value Treatment:

Magnitude: Mean imputation (22.93)
Diameter Min: Mean imputation (0.158)
Diameter Max: Mean imputation (0.353)


Feature Engineering:

Label encoding for orbiting_body
Standard scaling for numerical features
SMOTE resampling for class balance



Model Architecture
Training Configuration

Train-Test Split: 70/30
Random State: 42
Scaling: StandardScaler
Class Balancing: SMOTE

Models Performance

1-Logistic Regression
2-Random Forest

