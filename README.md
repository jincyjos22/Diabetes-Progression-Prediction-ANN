# 🩺 Diabetes Progression Prediction Using Artificial Neural Network (ANN)

## 📖 Project Overview

This project implements an Artificial Neural Network (ANN) using TensorFlow and Keras to predict diabetes disease progression based on patient medical data. The objective is to build and evaluate neural network models capable of estimating disease progression using various clinical features.

The project includes data preprocessing, exploratory data analysis (EDA), model development, training, evaluation, and performance comparison between different ANN architectures.

---

## 📋 Table of Contents

- [📖 Project Overview](#-project-overview)
- [🎯 Objective](#-objective)
- [📂 Dataset](#-dataset)
- [🛠 Technologies Used](#-technologies-used)
- [📊 Exploratory Data Analysis](#-exploratory-data-analysis)
- [🏗 Model Architecture](#-model-architecture)
- [🚀 Installation](#-installation)
- [📋 Requirements](#-requirements)
- [▶️ Usage](#️-usage)
- [📈 Results](#-results)
- [📊 Performance Metrics](#-performance-metrics)
- [📁 Repository Structure](#-repository-structure)
- [🔮 Future Improvements](#-future-improvements)
- [👩‍💻 Author](#-author)

---

## 🎯 Objective

The primary objective of this project is to:

- Understand and implement Artificial Neural Networks.
- Perform exploratory data analysis on the Diabetes dataset.
- Train ANN models for regression tasks.
- Compare different ANN architectures.
- Evaluate model performance using regression metrics.

---

## 📂 Dataset

The project uses the Diabetes dataset available in Scikit-learn.

### Dataset Characteristics

- Number of Samples: 442
- Number of Features: 10
- Target Variable: Quantitative measure of diabetes progression one year after baseline

### Features

- Age
- Sex
- Body Mass Index (BMI)
- Blood Pressure (BP)
- S1
- S2
- S3
- S4
- S5
- S6

Dataset Source:

https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_diabetes.html

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

- Dataset overview
- Statistical summary
- Missing value check
- Feature distributions
- Correlation heatmap
- Scatter plots
- Feature relationship analysis

Visualizations help understand feature importance and relationships within the dataset.

---

## 🏗 Model Architecture

### Basic ANN Model

Input Layer

↓  

Dense Layer (64 neurons, ReLU)

↓  

Dense Layer (32 neurons, ReLU)

↓  

Output Layer (1 neuron)

---

### Improved ANN Model

Input Layer

↓  

Dense Layer (128 neurons, ReLU)

↓  

Dense Layer (64 neurons, ReLU)

↓  

Dense Layer (32 neurons, ReLU)

↓  

Output Layer (1 neuron)

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/jincyjos22/Diabetes-Progression-Prediction-ANN.git
```

Navigate to project directory:

```bash
cd Diabetes-Progression-Prediction-ANN
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 📋 Requirements

Create a file named `requirements.txt` containing:

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

Open Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
ANN.ipynb
```

Run all cells sequentially to:

- Load the dataset
- Perform preprocessing
- Train ANN models
- Evaluate performance
- Visualize results

---

## 📈 Results

The models were evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

The improved ANN architecture achieved better predictive performance compared to the basic ANN model.

---

## 📊 Performance Metrics

Metrics used:

### Mean Squared Error (MSE)

Measures average squared prediction error.

### Root Mean Squared Error (RMSE)

Provides error in the same units as the target variable.

### R² Score

Measures how well the model explains the variance in the target variable.

---

## 📸 Sample Outputs

Include screenshots of:

- Training Loss Curve
- Validation Loss Curve
- Correlation Heatmap
- Actual vs Predicted Values Plot

Store images in:

```text
images/
```

Example:

```text
images/
├── loss_curve.png
├── heatmap.png
├── predictions.png
```

---

## 📁 Repository Structure

```text
Diabetes-Progression-Prediction-ANN/
│
├── ANN.ipynb
├── README.md
├── requirements.txt
│
└── images/
    ├── loss_curve.png
    ├── heatmap.png
    └── predictions.png
```


## 🔮 Future Improvements

- Hyperparameter tuning
- Early stopping
- Dropout regularization
- Cross-validation
- Model deployment using Flask or Streamlit
- Comparison with other machine learning algorithms

---
## ⭐ Acknowledgements

- Scikit-learn Diabetes Dataset
- TensorFlow Documentation
- Keras Documentation
- Open-source Machine Learning Community

---

If you found this project useful, please consider giving it a ⭐ on GitHub.
