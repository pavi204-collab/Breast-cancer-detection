# Breast-cancer-detection
Breast Cancer Detection is a Python-based machine learning project that classifies breast tumor data into benign and malignant categories. The project uses data preprocessing, feature standardization, and Logistic Regression to train a classification model. Its performance is evaluated using accuracy, classification report, and confusion matrix.
# Breast Cancer Detection Using Machine Learning

## Project Overview

Breast Cancer Detection is a machine learning project developed using Python to classify breast tumor data into two categories: benign and malignant.

The project uses numerical measurements of breast tumor characteristics and applies Logistic Regression to predict the diagnosis. The data is standardized before training the model, and the model is evaluated using several classification metrics.

This project is intended for educational and academic purposes.

## Objectives

* To understand the breast cancer dataset.
* To analyze breast tumor features.
* To check and prepare the dataset for machine learning.
* To separate input features and the target variable.
* To train a classification model.
* To predict whether a tumor is benign or malignant.
* To evaluate the performance of the machine learning model.
* To visualize selected tumor features.

## Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn

## Machine Learning Algorithm

### Logistic Regression

The project uses Logistic Regression as the classification algorithm.

Logistic Regression is a supervised machine learning algorithm commonly used for binary classification problems.

In this project, the model predicts one of two classes:

* Benign
* Malignant

## Dataset

The project uses the Breast Cancer Wisconsin Diagnostic dataset.

The dataset contains numerical measurements related to breast tumor characteristics.

Examples of features include:

* Mean radius
* Mean texture
* Mean perimeter
* Mean area
* Mean smoothness
* Mean compactness
* Mean concavity
* Mean symmetry
* Fractal dimension

The target variable is:

`diagnosis`

## Project Workflow

The project follows these steps:

1. Load the breast cancer dataset.
2. Display the first five rows.
3. Check the dataset shape.
4. Check for missing values.
5. Display the distribution of diagnosis classes.
6. Separate features and target values.
7. Split the dataset into training and testing data.
8. Standardize the features.
9. Train the Logistic Regression model.
10. Generate predictions.
11. Calculate model accuracy.
12. Generate a classification report.
13. Generate a confusion matrix.
14. Predict an example tumor.
15. Visualize selected tumor features.

## Data Preparation

The dataset is loaded using Pandas.

The diagnosis column is separated from the remaining features.

The data is divided into:

* 80% Training Data
* 20% Testing Data

The split uses stratification so that the class distribution is maintained between the training and testing datasets.

## Feature Standardization

The numerical features are standardized using `StandardScaler`.

Standardization transforms the features so that they are on a comparable scale. This is useful for Logistic Regression because the model can be affected by differences in feature scales.

## Model Training

The Logistic Regression model is trained using the standardized training data.

The trained model is then used to predict the diagnosis of the test data.

## Model Evaluation

The project evaluates the model using the following metrics:

### Accuracy

Accuracy represents the percentage of correctly classified tumor samples.

### Classification Report

The classification report provides:

* Precision
* Recall
* F1-score
* Support

These metrics provide more detailed information about the classification performance.

### Confusion Matrix

The confusion matrix shows the number of correctly and incorrectly classified samples for each diagnosis category.

## Example Prediction

The project uses one sample from the test dataset as an example and passes it through the trained model.

The model predicts whether the tumor belongs to the benign or malignant category.

## Data Visualization

The project creates a scatter plot using:

* Mean Radius
* Mean Texture

The visualization helps examine the relationship between these two tumor features and the diagnosis classes.

The generated image is saved as:

`breast_cancer_features.png`

## Project Structure

```text
Breast_Cancer_Detection/
│
├── breast_cancer_detection.py
├── breast_cancer.csv
├── requirements.txt
├── README.md
└── breast_cancer_features.png
```

The visualization image is generated when the Python program is executed.

## Installation

Make sure Python is installed on your computer.

Install the required libraries using:

```bash
pip install -r requirements.txt
```

The required libraries are:

```text
pandas
matplotlib
scikit-learn
```

## How to Run

Open Command Prompt or Terminal in the project folder.

Run the following command:

```bash
python breast_cancer_detection.py
```

The program will:

* Display the first five rows of the dataset.
* Display the dataset shape.
* Check for missing values.
* Display the diagnosis distribution.
* Train the Logistic Regression model.
* Calculate model accuracy.
* Display the classification report.
* Display the confusion matrix.
* Generate an example tumor prediction.
* Create the feature visualization.

## Applications

Machine learning-based tumor classification can be studied for applications such as:

* Medical data analysis
* Healthcare research
* Tumor classification research
* Pattern recognition
* Educational machine learning projects

## Limitations

* This project is designed for educational purposes.
* The model's predictions depend on the dataset and features used for training.
* Machine learning predictions should not be considered a substitute for professional medical evaluation.
* Additional validation and clinical testing would be required before any real-world medical application.

## Future Enhancements

The project can be improved by:

* Comparing multiple machine learning algorithms.
* Adding additional data visualization techniques.
* Performing feature selection.
* Using cross-validation.
* Tuning model parameters.
* Creating a web-based prediction interface.
* Developing an interactive dashboard.
* Comparing Logistic Regression with Random Forest, SVM, and other classification algorithms.

## Project Information

**Project Name:** Breast Cancer Detection Using Machine Learning

**Domain:** Machine Learning and Healthcare

**Programming Language:** Python

**Machine Learning Type:** Supervised Learning

**Problem Type:** Binary Classification

**Algorithm:** Logistic Regression

**Target Variable:** Diagnosis

## Important Note

This project is intended only for educational and academic purposes. It is not a medical diagnostic system and should not be used for clinical decision-making.
