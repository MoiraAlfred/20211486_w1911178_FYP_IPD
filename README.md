# 20211486_w1911178_FYP_IPD
Final Year Project Interim Progress Report - Graduate Academic Performance

## Overview

This repository contains the initial data preprocessing and visualization steps for an academic performance prediction project. The dataset is analyzed to prepare it for machine learning models by handling missing values, transforming features, and visualizing key distributions.

## Dataset

The dataset used contains student responses, including demographic details, academic history, and other factors that may influence academic performance. The target variable for prediction is Degree Classification.

## Preprocessing Steps

* Data Loading: The dataset is loaded using pandas.read_csv().

* Visualization: A pie chart is generated to observe class distribution for the target variable.

Statistical Analysis: Chi-square tests are performed on categorical variables to determine their significance in relation to the target variable.

* Feature Transformation: ColumnTransformer and FunctionTransformer are used for preprocessing selected features.

* Data Cleaning: Handling missing values and ensuring data consistency.

## Installation

To run this project, ensure you have the following dependencies installed:

pip install pandas numpy matplotlib seaborn scikit-learn scipy

## Contributions

Contributions are not welcome !

## License

This project is licensed under the Apache License.
