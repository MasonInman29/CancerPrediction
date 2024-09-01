# Cancer Data Analysis Project

This project is designed to analyze and classify cancer data using machine learning models. The dataset used in this project contains various features related to cancer diagnoses, and the goal is to build a model that can accurately predict the diagnosis based on these features.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Description](#data-description)
- [Graphs, Data, and  Predictions](#graphs,-data,-and-predictions)

## Project Overview

This project involves:

- Loading and preprocessing cancer data.
- Performing data checks to ensure data quality.
- Implementing machine learning models to classify cancer types.
- Evaluating model performance using various metrics.

## Data Description

The dataset `Cancer_Data.csv` contains the following key columns:

- `id`: Unique identifier for each sample.
- `diagnosis`: The target variable, indicating whether the cancer is malignant or benign.
- `radius_mean`, `texture_mean`, `perimeter_mean`, `area_mean`, etc.: Features related to the physical characteristics of the cell nuclei.

The data was sourced from: [Kaggle Cancer Data](https://www.kaggle.com/datasets/erdemtaha/cancer-data?resource=download) and is placed in the `./data/` directory, but not pushed to the repo due to the size of the file.

## Graphs, Data, and Predictions
![Model](https://github.com/MasonInman29/CancerPrediction/blob/main/graphs/diagnosis_distribution.png?raw=true)

Prediction Results
![Model](https://github.com/MasonInman29/CancerPrediction/blob/main/graphs/confusionMatrixLR.png?raw=true)
![Model](https://github.com/MasonInman29/CancerPrediction/blob/main/graphs/confusionMatrixRF.png?raw=true)

Receiver Operating Characteristic (ROC) Curve:
![Model](https://github.com/MasonInman29/CancerPrediction/blob/main/graphs/ROC_curve.png?raw=true)

