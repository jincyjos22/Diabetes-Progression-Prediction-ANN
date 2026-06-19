Diabetes Progression Prediction using Artificial Neural Network (ANN)
Project Overview

This project uses an Artificial Neural Network (ANN) to model and predict the progression of diabetes using the Diabetes dataset available in the Scikit-learn library. The goal is to understand how various health-related factors influence diabetes progression and to build a predictive model using Deep Learning techniques.

Objective
Load and preprocess the Diabetes dataset.
Perform Exploratory Data Analysis (EDA).
Build and train an ANN model using TensorFlow/Keras.
Evaluate model performance using regression metrics.
Improve the model through experimentation with different architectures and hyperparameters.
Dataset

The dataset is provided by the Scikit-learn library.

Features:

Age
Sex
Body Mass Index (BMI)
Blood Pressure
Six Blood Serum Measurements

Target:

Quantitative measure of diabetes progression one year after baseline.
Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
TensorFlow / Keras
Project Workflow
1. Data Loading and Preprocessing
Loaded the Diabetes dataset from Scikit-learn.
Checked for missing values.
Normalized feature values using StandardScaler.
2. Exploratory Data Analysis (EDA)
Visualized feature distributions.
Examined correlations between features and target variable.
Generated plots for better understanding of the dataset.
3. ANN Model Development
Created a Sequential Neural Network model.
Added hidden layers with ReLU activation.
Used a linear output layer for regression.
4. Model Training
Split data into training and testing sets.
Used Adam optimizer.
Used Mean Squared Error (MSE) loss function.
Trained the model on training data.
5. Model Evaluation

Performance was evaluated using:

Mean Squared Error (MSE)
R² Score
6. Model Improvement
Experimented with additional hidden layers.
Tuned neurons and learning rate.
Compared model performance before and after improvements.
Results

The ANN model successfully learned patterns from the dataset and predicted diabetes progression with reasonable accuracy. Performance improvements were achieved through hyperparameter tuning and architecture modifications.The ANN model successfully learned patterns from the dataset and predicted diabetes progression with reasonable accuracy. Performance improvements were achieved through hyperparameter tuning and architecture modifications.

