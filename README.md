# Liithium-Ion-Battery-SOC-Prediction

This project analyzes the Oxford Battery Degradation Dataset using various machine learning techniques to predict battery capacity degradation. The steps include data loading, preprocessing, exploratory data analysis, feature engineering, model training, hyperparameter tuning, and a theoretical deployment plan using KServe in a Kubeflow environment.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Feature Engineering](#feature-engineering)
- [Model Training](#model-training)
- [Hyperparameter Tuning](#hyperparameter-tuning)
- [Model Evaluation](#model-evaluation)

## Introduction

This project aims to predict the degradation of battery capacity over time using the Oxford Battery Degradation Dataset. The dataset contains information on battery cycles, and the analysis involves training a machine learning model to predict capacity degradation.

## Dataset

The Oxford Battery Degradation Dataset is used in this project. It includes data on various battery cycles and their corresponding capacities. The dataset is preprocessed and normalized to extract meaningful features for the machine learning model.

## Installation

To run this project, you need to have the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- lightgbm
- kubeflow

## Data Preprocessing

The data preprocessing step involves loading the dataset, normalizing the data, and extracting relevant features. The following steps are performed:

- Loading the dataset
- Normalizing the data
- Feature extraction

## Exploratory Data Analysis

Exploratory Data Analysis (EDA) is performed to understand the underlying patterns in the data. Various plots are used to visualize the data, including:

- Histograms
- Scatter plots
- Line plots

### EDA Images

![Exploratory Data Analysis 1](https://github.com/OmarKavita/Liithium-Ion-Battery-SOC-Prediction/blob/main/Images/image1.png)
![Exploratory Data Analysis 2](https://github.com/OmarKavita/Liithium-Ion-Battery-SOC-Prediction/blob/main/Images/image2.png)
![Exploratory Data Analysis 3](https://github.com/OmarKavita/Liithium-Ion-Battery-SOC-Prediction/blob/main/Images/image3.png)

## Feature Engineering

Feature engineering is performed to extract meaningful features from the dataset. Domain-specific knowledge is used to create new features that are relevant for predicting battery capacity degradation.

## Model Training

The data is split into training and test sets, and a machine learning model (e.g., LightGBM) is trained on the data. The model is evaluated using metrics like Mean Absolute Error (MAE).

## Hyperparameter Tuning

Hyperparameter tuning is performed using techniques like GridSearchCV to find the best hyperparameters for the model.

## Model Evaluation

The final model is evaluated on the test set, and the results are analyzed using various plots and metrics.

### Model Prediction

![Model Prediction](https://github.com/OmarKavita/Liithium-Ion-Battery-SOC-Prediction/blob/main/Images/predictionimage.png)



