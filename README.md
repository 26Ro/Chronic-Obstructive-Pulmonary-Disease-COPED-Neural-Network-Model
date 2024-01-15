# Lung Disease Prediction Model

## Overview
This repository contains code for a neural network-based lung disease prediction model. The model is built using TensorFlow and Keras, and it predicts the risk of lung disease based on various patient features.

## Dataset
The model is trained on a dataset that includes the following features:
- `smoke`: Smoking status
- `FVC`: Pulmonary function test - Forced Vital Capacity
- `FEC1`: Pulmonary function test - Forced Expiratory Capacity in 1 second
- `PEFR`: Peak Expiratory Flow Rate
- `O2`: Oxygen levels
- `ABG-P-O2`: Arterial Blood Gas - Partial Pressure of Oxygen
- `ABG-P-CO2`: Arterial Blood Gas - Partial Pressure of Carbon Dioxide
- `ABG-pH Level`: Arterial Blood Gas - pH Level
- `Scan`: CT scan results
- `Asthama`: Asthma status
- `Other diseases`: Other existing diseases
- `AGE`: Age of the patient
- `Risk`: Binary label indicating the risk of lung disease (0 or 1)

## Model Architecture
The neural network model architecture includes:
- Input layer with appropriate input size
- Dense layers with ReLU activation functions
- Batch normalization for regularization
- Dropout layers to prevent overfitting
- Output layer with a sigmoid activation function for binary classification

## Usage
1. **Requirements:**
   - Python (>=3.6)
   - TensorFlow (>=2.0)
   - pandas, scikit-learn

2. **Installation:**
   ```bash
   pip install -r requirements.txt
