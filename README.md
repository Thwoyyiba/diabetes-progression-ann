# Diabetes Progression Prediction using ANN

## 📌  Overview

This  predicts diabetes disease progression using an Artificial Neural Network (ANN).

The  Diabetes dataset available in the Scikit-learn library. The data is explored, preprocessed, normalized, and used to train a neural network regression model.

## 🎯 Objective

The main objective is to model diabetes progression using the available independent variables and evaluate how well an ANN can predict the target value.

## 📊 Dataset

The Diabetes dataset is obtained directly from Scikit-learn.

* Number of samples: 442
* Number of input features: 10
* Target: Diabetes progression

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* TensorFlow
* Keras
* Jupyter Notebook

## 🔄  Workflow

1. Load the Diabetes dataset
2. Understand the dataset
3. Check for missing values
4. Perform Exploratory Data Analysis (EDA)
5. Visualize feature and target relationships
6. Split data into training and testing sets
7. Normalize the features using StandardScaler
8. Build a baseline ANN model
9. Train the ANN
10. Evaluate the model
11. Improve the ANN architecture
12. Compare baseline and improved models

## 🧠 ANN Architecture

### Baseline Model

```text
Input Layer
     ↓
Dense Layer - 64 neurons - ReLU
     ↓
Dense Layer - 32 neurons - ReLU
     ↓
Output Layer - 1 neuron
```

### Improved Model

```text
Input Layer
     ↓
Dense Layer - 128 neurons - ReLU
     ↓
Dense Layer - 64 neurons - ReLU
     ↓
Dense Layer - 32 neurons - ReLU
     ↓
Output Layer - 1 neuron
```

## ⚙️ Model Configuration

The ANN uses:

* Optimizer: Adam
* Loss Function: Mean Squared Error (MSE)
* Evaluation Metrics: MAE and R² Score
* Early Stopping for the improved model

## 📈 Evaluation Metrics

The models are evaluated using:

### Mean Squared Error (MSE)

Measures the squared difference between actual and predicted values.

Lower MSE indicates better performance.

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted values.

Lower MAE indicates better performance.

### R² Score

Measures how well the model explains the variation in the target variable.

Higher R² generally indicates better performance.




## 👩‍💻 Author

THWOYYIBA NASREEN C
