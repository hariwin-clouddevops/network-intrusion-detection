# Network Intrusion Detection

## Project Overview

This project is a machine learning-based Network Intrusion Detection system.

The project uses network traffic data to identify possible anomalous or suspicious network activity. A Random Forest machine learning model is trained using network-related features and saved as a `.pkl` file for later use.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook
- Random Forest
- Machine Learning

## Project Files

### `Network_Intrusion_Detection_ipynb.ipynb`

Jupyter Notebook containing the data loading, preprocessing, model training, and network intrusion detection process.

### `network_anomaly_rf_model.pkl`

Trained Random Forest model saved using Python pickle format.

## Dataset

The project uses network traffic data containing features related to network connections, such as:

- Duration
- Protocol type
- Service
- Flag
- Source bytes
- Destination bytes
- Network traffic statistics

The dataset is used to train and evaluate the machine learning model.

## Machine Learning Model

A Random Forest classifier is used to detect network anomalies.

Random Forest is an ensemble machine learning algorithm that combines multiple decision trees to make predictions.

## Workflow

1. Load the network traffic dataset.
2. Explore and preprocess the data.
3. Prepare the features for machine learning.
4. Train the Random Forest model.
5. Evaluate the model.
6. Save the trained model as a `.pkl` file.
7. Use the trained model for network anomaly detection.

## Objective

The main objective of this project is to demonstrate how machine learning can be applied to network security for detecting suspicious or anomalous network traffic.

## Author

Hariwin

GitHub: https://github.com/hariwin-clouddevops
