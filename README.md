# Customer Churn Prediction using ANN

## Project Overview
This project predicts whether a customer will leave the bank or not using Artificial Neural Network (ANN).

## Dataset
- 10,000 records
- 11 features
- Target: churn (0 = No, 1 = Yes)

## Steps Performed

### 1. Data Preprocessing
- Removed customer_id column
- Encoded gender using LabelEncoder
- Applied One-Hot Encoding on country
- Standardized features using StandardScaler

### 2. Model Building
- ANN model built using Keras Sequential API
- Input Layer + 2 Hidden Layers
- Activation: ReLU
- Output Layer: Sigmoid

### 3. Training
- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Epochs: 50
- Batch Size: 32

### 4. Evaluation
- Model evaluated on test data
- Accuracy and loss calculated

### 5. Output
- Predictions saved in CSV file
- Trained model saved in .keras format

## Conclusion
The ANN model successfully predicts customer churn with good accuracy.
