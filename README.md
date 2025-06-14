# Breast Cancer Predictor

A machine learning project for predicting breast cancer diagnosis using Logistic Regression in Jupyter Notebook. This project demonstrates the process of data exploration, preprocessing, model building, and evaluation for the Breast Cancer Wisconsin dataset.

> **Note:** This project results in a trained model only. It does not provide a user interface or scripts to take new input and return predictions.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

The **Breast Cancer Predictor** uses Logistic Regression to classify breast cancer tumors as malignant or benign based on features from the Breast Cancer Wisconsin dataset. The model is built, trained, and evaluated in a single Jupyter Notebook, with a focus on educational clarity and reproducibility.

## Dataset

The project uses the [Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+%28diagnostic%29):

- **Features:** 30 numeric features (e.g., radius, texture, perimeter, area, smoothness, etc.)
- **Target:** Diagnosis (Malignant or Benign)
- **Samples:** 569

## Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature visualization and correlation analysis
- Implementation of Logistic Regression classifier
- Model training and evaluation

## Evaluation

The model is evaluated using:

- **Accuracy Score**: Measures the proportion of correct predictions.
- **Classification Report**: Includes precision, recall, and F1-score for each class.

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/tanishqkumar700/Breast-Cancer-Predictor.git
   cd Breast-Cancer-Predictor
   ```

2. **Install dependencies**
   Make sure you have Python 3.x and pip installed.

   ```bash
   pip install -r requirements.txt
   ```

   Or, install key packages manually:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn jupyter
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

## Usage

- Open the notebook file (e.g., `Breast_Cancer_Predictor.ipynb`) in Jupyter.
- Run the cells sequentially to:
  - Load and explore the data
  - Preprocess and visualize features
  - Train the Logistic Regression model
  - Evaluate the model with accuracy score and classification report

**Note:**  
This notebook does not include functionality to input new data and return predictions. It is intended for demonstrating the workflow of training and evaluating a machine learning model.

## Results

Example output from evaluation:

```
Accuracy: 97%
Classification Report:
              precision    recall  f1-score   support

           0       0.98      0.96      0.97        72
           1       0.96      0.98      0.97        72

    accuracy                           0.97       144
   macro avg       0.97      0.97      0.97       144
weighted avg       0.97      0.97      0.97       144
```
*Actual results may vary depending on random state and data split.*

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for enhancements or bug fixes.

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Author:** [tanishqkumar700](https://github.com/tanishqkumar700)
