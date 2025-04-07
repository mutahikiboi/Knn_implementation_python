K-Nearest Neighbors (KNN) Implementation for Iris Dataset Classification
Overview
This repository contains a Python implementation of the K-Nearest Neighbors (KNN) algorithm for classifying iris flowers into their species using the classic Iris dataset. The implementation demonstrates the fundamental concepts of the KNN algorithm from scratch, including distance calculation, neighbor selection, and majority voting.

Features
Manual implementation of KNN algorithm (without using scikit-learn's built-in KNN)

Data visualization of iris flower features

Train-test split functionality

Euclidean distance calculation

K-nearest neighbor selection

Prediction using majority voting

Confusion matrix for performance evaluation

Requirements
Python 3.6+

Required packages:

numpy

pandas

matplotlib

scikit-learn (for dataset loading and confusion matrix)

Install requirements with:

bash
Copy
pip install numpy pandas matplotlib scikit-learn
Code Structure
Data Loading: Uses scikit-learn's built-in iris dataset

Data Visualization: Plots sepal vs petal proportions by species

Data Splitting: 80-20 train-test split with random seed for reproducibility

Distance Calculation: Euclidean distance implementation

KNN Prediction:

Finds k-nearest neighbors

Uses majority voting for classification

Evaluation: Confusion matrix output

Usage
Run the script directly to see the KNN implementation in action:

bash
Copy
python knn_iris.py
The script will:

Load and visualize the iris dataset

Split the data into training and test sets

Classify test samples using KNN

Output predictions and confusion matrix

Results
The implementation demonstrates:

How KNN classifies flowers based on feature similarity

The effect of neighbor count (k) on predictions

Model performance through the confusion matrix

Author
Michael Kiboi

License
This project is licensed under the Apache 2.0 License - see the LICENSE file for details.