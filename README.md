# Heart-Disease-Prediction-using-ML-Models
This project utilizes several machine learning models to predict the likelihood of heart disease based on patient data. The dataset is processed with scaling and label encoding, and the models used include Logistic Regression, Decision Tree, Random Forest, and Support Vector Machine (SVM). Various evaluation metrics and cross-validation techniques are applied to ensure accuracy and robustness. The project also demonstrates feature selection using pipelines and visualizes model performance.

## Project Overview
This project applies machine learning techniques to predict heart disease using a publicly available dataset. Several models, including Logistic Regression, Decision Tree, Random Forest, and Support Vector Machine (SVM), are trained and evaluated to identify the best performing model.

## Dataset
The dataset used contains patient health records, including various risk factors for heart disease. The target variable is binary, representing the presence or absence of heart disease.

## Models Used
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **Support Vector Machine (SVM)**

## Feature Engineering
The project preprocesses the dataset by handling categorical variables, scaling features, and selecting relevant features. A pipeline was created to streamline the process for certain models.

## Model Evaluation
Each model is evaluated using cross-validation and accuracy scores on test data. Classification reports are generated to analyze precision, recall, and F1-scores.

## Results
The best performing model is identified based on cross-validation accuracy, and the model performance is visualized through comparison charts.

## Installation and Setup
To run this project, ensure you have the following installed:

- Python 3.x
- Libraries: `pandas`, `scikit-learn`, `matplotlib`, `numpy`

```bash
pip install pandas scikit-learn matplotlib numpy
