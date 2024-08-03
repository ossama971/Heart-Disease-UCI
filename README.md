# Heart Disease Prediction

This repository contains a Jupyter notebook that details the exploratory data analysis (EDA) and classification model development for predicting heart disease. The goal of this project is to build a machine learning model that can accurately predict the presence of heart disease in patients based on various health metrics.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#Contributors)

## Introduction

Heart disease is a significant health issue worldwide. Early prediction and diagnosis can lead to better treatment and improved patient outcomes. This project involves building a machine learning model to predict heart disease using a detailed EDA and various classification algorithms.

## Dataset

The dataset used in this project includes various health metrics such as:

- `age`
- `sex`
- `cp` (chest pain type)
- `trestbps` (resting blood pressure)
- `chol` (serum cholesterol)
- `fbs` (fasting blood sugar)
- `restecg` (resting electrocardiographic results)
- `thalach` (maximum heart rate achieved)
- `exang` (exercise induced angina)
- `oldpeak` (ST depression induced by exercise relative to rest)
- `slope` (the slope of the peak exercise ST segment)
- `ca` (number of major vessels colored by fluoroscopy)
- `thal` (thalassemia)
- `target` (presence of heart disease, 0 or 1)

## Installation

To run this project, ensure you have Python and Jupyter Notebook installed. Follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/ossama971/Heart-Disease-UCI
    ```
2. Navigate to the project directory:
    ```bash
    cd Heart-Disease-UCI
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Open the Notebook:**
    - Launch Jupyter Notebook:
        ```bash
        jupyter notebook
        ```
    - Open the `heart_disease_prediction.ipynb` file.

2. **Run the Notebook:**
    - Execute the cells sequentially to perform data preprocessing, exploratory data analysis, model training, and evaluation.

## Exploratory Data Analysis

The EDA section covers:
- Data cleaning and preprocessing
- Univariate and bivariate analysis
- Visualization of key features
- Insights and observations

## Model Training

The model training section includes:
- Data splitting (train-test split)
- Training various classification algorithms (e.g., Logistic Regression, Decision Trees, Random Forest, XGBoost)
- Hyperparameter tuning
- Model evaluation

## Evaluation

The evaluation section provides:
- Confusion matrix
- Classification report
- Feature importance analysis

## Results

The final model of XGBoost achieved the following performance metrics:
- Accuracy: 86.9%
- Precision: 87.3%
- Recall: 86.6%
- F1 Score: 86.8%
  
 ## Contributors <a name = "Contributors"></a>

<table>
  <tr>
    <td align="center">
    <a href="https://github.com/Omarnbl" target="_black">
    <img src="https://avatars.githubusercontent.com/u/104171903?v=4" width="150px;" alt="Omar Nabil"/>
    <br />
    <sub><b>Omar Nabil</b></sub></a>
    </td>
  <td align="center">
    <a href="https://github.com/AliBadran716" target="_black">
    <img src="https://avatars.githubusercontent.com/u/102072821?v=4" width="150px;" alt="Ali Badran"/>
    <br />
    <sub><b>Ali Badran</b></sub></a>
    </td>
     <td align="center">
    <a href="https://github.com/ahmedalii3" target="_black">
    <img src="https://avatars.githubusercontent.com/u/110257687?v=4" width="150px;" alt="Ahmed Ali"/>
    <br />
    <sub><b>Ahmed Ali</b></sub></a>
    </td>
<td align="center">
    <a href="https://github.com/ossama971" target="_black">
    <img src="https://avatars.githubusercontent.com/u/40814982?v=4" width="150px;" alt="Hassan Hussein"/>
    <br />
    <sub><b>Osama Badawi</b></sub></a>
    </td>
      </tr>
 </table>

