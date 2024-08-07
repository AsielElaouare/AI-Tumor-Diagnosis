
# Cancer Tumor Detection Project

[![Python](https://img.shields.io/badge/Language-Python-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Library-Pandas-green?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![TensorFlow](https://img.shields.io/badge/Library-TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Google Colab](https://img.shields.io/badge/IDE-Google%20Colab-F9AB00?style=for-the-badge&logo=google-colab&logoColor=white)](https://colab.research.google.com/)

This project utilizes Python and TensorFlow to build a machine learning model capable of detecting cancer tumors based on a given dataset. The model is trained to classify tumors as malignant (M) or benign (B) using a neural network.

## Dataset
The dataset used for this project is a CSV file named cancer.csv. It contains various features of tumors, and a column diagnosis(1=m, 0=b) indicating whether the tumor is malignant (1) or benign (0).

## Project Structure
The project consists of the following main steps:

Data Loading and Preprocessing: Load the dataset and split it into features (x) and labels (y).
Data Splitting: Split the data into training and testing sets.
Model Building and Training: Define and train the neural network model.
Model Evaluation: Evaluate the model's performance on the testing set.
