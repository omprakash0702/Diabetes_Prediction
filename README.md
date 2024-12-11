# Diabetes Prediction using SVM

## Overview
This project leverages a Support Vector Machine (SVM) to predict the likelihood of diabetes based on clinical data. The notebook provides a comprehensive guide, covering all steps from data preprocessing to model evaluation.

## Features
- Importing and exploring the dataset
- Data Cleaning and Preprocessing, including handling missing values
- Feature scaling using StandardScaler
- Model training using SVM
- Performance evaluation using metrics such as Accuracy, Precision, Recall, and F1-Score

## Dataset
The dataset used in this project is the PIMA Indians Diabetes Dataset, which is publicly available from [Kaggle](https://www.kaggle.com/). It includes the following features:
- Pregnancies
- Glucose levels
- Blood Pressure
- Skin Thickness
- Insulin levels
- BMI
- Diabetes Pedigree Function
- Age

Ensure the dataset is stored in the same directory as the notebook or update the file path in the notebook code accordingly.

## Prerequisites
- Python 3.x
- Google Colab or Jupyter Notebook
- Required Python libraries:
  - pandas
  - numpy
  - matplotlib
  - scikit-learn

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/diabetes-prediction-svm.git
   ```
2. Navigate to the project directory:
   ```bash
   cd diabetes-prediction-svm
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the notebook in Google Colab or locally:
   - For Google Colab:
     - Upload the notebook file `Diabetes_Prediction_using_svm.ipynb` to your Google Drive.
     - Open the notebook in Colab and set the runtime to include GPU if needed.
   - For local setup:
     ```bash
     jupyter notebook Diabetes_Prediction_using_svm.ipynb
     ```
2. Follow the steps in the notebook:
   - Load the dataset and explore its structure
   - Perform data preprocessing (e.g., handling missing values, scaling features)
   - Train the SVM model
   - Evaluate the model using the test dataset

## Results
- The SVM model achieves robust performance with significant accuracy and well-balanced precision and recall metrics.

