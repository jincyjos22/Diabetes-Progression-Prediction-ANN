# 🩺 Diabetes Progression Prediction Using Artificial Neural Network (ANN)

## 📖 Project Overview

This project implements an Artificial Neural Network (ANN) using TensorFlow and Keras to predict diabetes progression based on patient clinical data. The objective is to develop and evaluate neural network models capable of estimating disease progression using multiple health-related features.

The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model development, training, evaluation, and comparison of ANN architectures.

---

## 📋 Table of Contents

* [📖 Project Overview](#-project-overview)
* [🎯 Objective](#-objective)
* [📂 Dataset](#-dataset)
* [🛠 Technologies Used](#-technologies-used)
* [📊 Exploratory Data Analysis](#-exploratory-data-analysis)
* [🏗 Model Architecture](#-model-architecture)
* [🚀 Installation](#-installation)
* [📋 Requirements](#-requirements)
* [▶️ Usage](#️-usage)
* [📈 Results](#-results)
* [📊 Performance Metrics](#-performance-metrics)
* [📁 Repository Structure](#-repository-structure)
* [✅ Conclusion](#-conclusion)
* [🔮 Future Improvements](#-future-improvements)
* [⭐ Acknowledgements](#-acknowledgements)

---

## 🎯 Objective

The primary objectives of this project are:

* Understand and implement Artificial Neural Networks.
* Perform exploratory data analysis on the Diabetes dataset.
* Apply data preprocessing techniques.
* Train ANN models for regression tasks.
* Compare different ANN architectures.
* Evaluate model performance using standard regression metrics.
* Analyze the effectiveness of neural networks in predicting diabetes progression.

---

## 📂 Dataset

The project uses the Diabetes dataset available in Scikit-learn.

### Dataset Characteristics

* Number of Samples: 442
* Number of Features: 10
* Target Variable: Quantitative measure of diabetes progression one year after baseline

### Features

* Age
* Sex
* Body Mass Index (BMI)
* Blood Pressure (BP)
* S1
* S2
* S3
* S4
* S5
* S6

### Dataset Source

https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_diabetes.html

---

## 🛠 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* TensorFlow
* Keras
* Jupyter Notebook

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

* Dataset inspection
* Statistical summary
* Missing value verification
* Feature distribution analysis
* Correlation heatmap
* Scatter plot visualization
* Feature relationship analysis

These visualizations help identify patterns and relationships between variables that may influence diabetes progression.

---

## 🏗 Model Architecture

### Basic ANN Model

Input Layer

↓

Dense Layer (64 Neurons, ReLU)

↓

Dense Layer (32 Neurons, ReLU)

↓

Output Layer (1 Neuron)

---

### Improved ANN Model

Input Layer

↓

Dense Layer (128 Neurons, ReLU)

↓

Dense Layer (64 Neurons, ReLU)

↓

Dense Layer (32 Neurons, ReLU)

↓

Output Layer (1 Neuron)

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/jincyjos22/Diabetes-Progression-Prediction-ANN.git
```

Navigate to the project directory:

```bash
cd Diabetes-Progression-Prediction-ANN
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 📋 Requirements

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
tensorflow
keras
jupyter
```

Install using:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
ANN.ipynb
```

Run all cells sequentially to:

* Load the dataset
* Preprocess the data
* Train ANN models
* Evaluate model performance
* Visualize results

---

## 📈 Results

The ANN models were evaluated using regression metrics including:

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

The improved ANN architecture demonstrated better predictive performance compared to the basic ANN model.

---

## 📊 Performance Metrics

### Mean Squared Error (MSE)

Measures the average squared difference between actual and predicted values.

### Root Mean Squared Error (RMSE)

Measures prediction error in the same units as the target variable.

### R² Score

Measures how well the model explains the variance in the target variable.

---

## 📁 Repository Structure

```text
Diabetes-Progression-Prediction-ANN/
│
├── ANN.ipynb
├── README.md
├── requirements.txt
├── diabetes_ann_model.h5
└── scaler.pkl
```

---

## ✅ Conclusion

This project successfully developed and evaluated Artificial Neural Network (ANN) models for predicting diabetes progression using the Scikit-learn Diabetes dataset. The improved ANN architecture demonstrated enhanced predictive performance and highlighted the effectiveness of deep learning techniques for regression-based healthcare analytics.

---

## 🔮 Future Improvements

* Hyperparameter tuning
* Early stopping
* Dropout regularization
* Cross-validation
* Model deployment using Flask or Streamlit
* Comparison with other machine learning algorithms
* Integration with larger real-world healthcare datasets

---

## ⭐ Acknowledgements

* Scikit-learn Diabetes Dataset
* TensorFlow Documentation
* Keras Documentation
* Open-source Machine Learning Community

---

