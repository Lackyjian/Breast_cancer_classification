# Breast Cancer Classification

![Breast Cancer](https://images.pexels.com/photos/1632474/pexels-photo-1632474.jpeg)

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Models](#models)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

## Introduction
This project aims to classify breast cancer using machine learning models. Breast cancer is a significant health concern, and early detection plays a crucial role in improving patient outcomes. Machine learning can help in automating the diagnosis process and making it more accurate.

## Dataset
The dataset used in this project was obtained from Kaggle and can be found at [Breast Cancer Dataset](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset). It contains various features related to breast cancer tumors, including attributes like radius, texture, perimeter, area, and more. The target variable is the classification of the tumor as malignant (0) or benign (1).

## Models
We have trained multiple machine learning models to classify breast cancer. The following models were used:
- Logistic Regression
- Random Forest Classifier
- Support Vector Classifier (SVC)
- XGBoost Classifier

These models were trained on the dataset to predict whether a given tumor is malignant or benign. The individual predictions from these models were then combined using a stacking classifier to improve the overall accuracy.

## Usage
To use this project, follow these steps:
1. Clone this repository to your local machine.
2. Download the dataset from [Breast Cancer Dataset](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset) and place it in the project directory.
3. Install the required Python libraries listed in the `requirements.txt` file.
4. Install the libraries used in the project.
5. Run the Jupyter notebook or Python script provided to train the models and make predictions.

## Results
The final accuracy achieved by this project is an impressive 99.3%. This high accuracy indicates the potential of machine learning in breast cancer classification. The stacking classifier effectively combined the predictions from multiple models to improve the overall accuracy.

## Contributing
Contributions to this project are welcome. If you have ideas for improving the models, optimizing the code, or adding new features, please feel free to submit a pull request.
