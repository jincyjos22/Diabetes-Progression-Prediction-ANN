# Diabetes Progression Prediction using Artificial Neural Network (ANN)

## Overview

This project develops an Artificial Neural Network (ANN) model to predict diabetes progression using the Diabetes dataset from Scikit-learn. The model analyzes various patient-related features and estimates disease progression, helping demonstrate the application of deep learning in healthcare prediction tasks.

## Objective

- Load and preprocess the Diabetes dataset.
- Perform Exploratory Data Analysis (EDA).
- Build an ANN model using TensorFlow/Keras.
- Train and evaluate the model.
- Improve model performance through experimentation with hyperparameters and architecture.

## Dataset

The dataset is available in the Scikit-learn library.

### Features

- Age
- Sex
- Body Mass Index (BMI)
- Blood Pressure
- Six Blood Serum Measurements

### Target Variable

- Quantitative measure of diabetes progression after one year.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras

## Project Workflow

### 1. Data Loading and Preprocessing

- Loaded the Diabetes dataset from Scikit-learn.
- Checked for missing values.
- Normalized features using StandardScaler.
- Prepared data for model training.

### 2. Exploratory Data Analysis (EDA)

- Examined dataset structure and statistics.
- Visualized feature distributions.
- Analyzed correlations between features and target variable.
- Generated plots for better understanding of the data.

### 3. ANN Model Development

- Built a Sequential Neural Network model.
- Added hidden layers with ReLU activation.
- Used a linear activation function in the output layer for regression.

### 4. Model Training

- Split the dataset into training and testing sets.
- Used Adam optimizer.
- Used Mean Squared Error (MSE) as the loss function.
- Trained the ANN model on training data.

### 5. Model Evaluation

Performance metrics used:

- Mean Squared Error (MSE)
- R² Score

### 6. Model Improvement

- Experimented with additional hidden layers.
- Tuned the number of neurons.
- Adjusted learning rates and epochs.
- Compared results before and after improvements.

## Results

The ANN model successfully learned patterns from the dataset and predicted diabetes progression with reasonable accuracy. Model performance was improved through hyperparameter tuning and architectural modifications.


## Repository Structure

```text
Diabetes-Progression-Prediction-ANN/
│
├── ANN.ipynb
├── README.md
└── requirements.txt
```

## Key Learning Outcomes

- Data preprocessing and normalization
- Exploratory Data Analysis
- Artificial Neural Networks
- Regression using Deep Learning
- Model evaluation and performance improvement


This project was developed as part of the Deep Learning Module End Assignment for academic purposes.
