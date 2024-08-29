# classification-challenge
#### Danielle Dejean 
AI Bootcamp - Module Challenge #13,
28 August 2024
## Overview
This code compares the accuracy of two supervised Machine Learning (ML) models - Logistic Reression and Random Forest Classifier - with respect to identifying spam in an Internet Service Provider's dataset.

## Functionality Implemented
* Jupyter Lab
* Installs and library imports: pandas, train_test_split, accuracy_score, RandomForestClassifier, Logistic Regression and StandardScaler from sklearn
* Functions: pd.read_csv, shape, info, copy drop, value_counts, train_test_split, StandardScaler, transform, LogisticRegression, fit, score, RandomForestClassifier, predict, feature_importances, sorted
* Other code: scaling (normalizing) data, feature importances attributed to each feature

## Set Up
* The files wihtin the classification-challenge repo were updated using Python version 3.10.14, in Jupyter Lab. To run it, please download the most recent version of [Python](https://www.python.org/downloads/), as well as a code editor that runs Python ([Visual Studio Code](https://code.visualstudio.com/download), [PyCharm](https://www.jetbrains.com/pycharm/download/?section=mac), etc.). 
## Run Instructions:
In Terminal (Mac) or GitBash (Windows):
* Ensure that you're running the correct version of Python (see Set Up above)
* Ensure that you're in the directory containing the file before running
* The program will create and analyse the accuracy of each model, and summarize the results. 
## References
* The spam_detector.ipynb starter file was downloaded from the AI-PT-WEST-MAY-052824_MTTH Module 13 Challenge files and edited to analyze the data.
