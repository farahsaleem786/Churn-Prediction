# Customer Churn Prediction Model

This project involves building a machine learning model to predict customer churn in a telecommunications company using customer data. The model uses a neural network built with TensorFlow and Keras to classify whether a customer will churn (leave the service) or not.

## Project Overview

- **Objective**: Predict customer churn based on various features such as tenure, monthly charges, and contract type.
- **Data**: The dataset contains information about customers including demographic details, usage statistics, and churn status.
- **Approach**: The model is a binary classification neural network, designed to predict the likelihood of customer churn.

## Key Features

- **Data Preprocessing**:
  - Handles missing or malformed data by coercing non-numeric values in the `TotalCharges` column.
  - Encodes categorical variables such as `Gender`, `InternetService`, `Contract`, and `PaymentMethod` using one-hot encoding and label encoding.
  - Scales numerical features such as `Tenure`, `MonthlyCharges`, and `TotalCharges` to improve model performance.

- **Model**:
  - Built with TensorFlow and Keras.
  - The model uses a fully connected neural network architecture with one hidden layer and an output layer using sigmoid activation.
  - Optimized using the Adam optimizer and binary cross-entropy loss function for binary classification tasks.

- **Evaluation**:
  - The model is evaluated on a test dataset, with results including accuracy, precision, recall, F1-score, and confusion matrix.
  - Visualizations such as a confusion matrix heatmap are generated to evaluate model performance.

## Requirements

To run this project, you need to have the following Python packages installed:

- Python 3.x
- TensorFlow
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn


