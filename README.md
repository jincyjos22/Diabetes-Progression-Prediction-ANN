# Diabetes Progression Prediction using Artificial Neural Network (ANN)

## Overview

This project develops an Artificial Neural Network (ANN) model to predict diabetes progression using the Diabetes dataset from Scikit-learn. The model analyzes various patient-related features and estimates disease progression using deep learning techniques.

## Objective

- Load and preprocess the Diabetes dataset.
- Perform Exploratory Data Analysis (EDA).
- Build an ANN model using TensorFlow/Keras.
- Train and evaluate the model.
- Improve model performance through experimentation with different hyperparameters and architectures.

## Dataset

This project uses the Diabetes dataset available in the Scikit-learn library.

### Features

- Age
- Sex
- Body Mass Index (BMI)
- Blood Pressure
- Six Blood Serum Measurements

### Target Variable

- Quantitative measure of diabetes progression after one year.

## Dataset Source

This project uses the Diabetes dataset provided by the Scikit-learn library.

Dataset Link:
https://scikit-learn.org/stable/datasets/toy_dataset.html#diabetes-dataset

```

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
- Normalized the features using StandardScaler.
- Prepared the data for training and testing.

### 2. Exploratory Data Analysis (EDA)

- Examined dataset structure and summary statistics.
- Visualized feature distributions.
- Analyzed relationships between features and target variable.
- Generated correlation heatmaps and plots.

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

- Experimented with different hidden layers.
- Tuned the number of neurons.
- Adjusted epochs and learning rates.
- Compared model performance before and after improvements.

## Results

The ANN model successfully learned patterns from the Diabetes dataset and predicted disease progression with reasonable accuracy. Model performance was improved through hyperparameter tuning and architecture modifications.

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
- Exploratory Data Analysis (EDA)
- Artificial Neural Networks (ANN)
- Deep Learning for Regression
- Model evaluation using MSE and R² Score
- Hyperparameter tuning and model improvement


## License

This project was developed as part of the Deep Learning Module End Assignment for academic purposes.
