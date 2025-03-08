Project Overview

This project aims to predict the type of crop suitable for a given soil based on various soil properties. It utilizes logistic regression, a machine learning algorithm, to analyze soil features and determine the most influential factor in predicting crop suitability.
Dataset

The dataset used in this project is soil_measures.csv, which contains multiple soil characteristics and their corresponding crops.
Dataset link:  https://in.docworkspace.com/d/sIEOPl83BAbGosb4G

The key features in the dataset include:

N: Nitrogen content
P: Phosphorus content
K: Potassium content
ph: Soil pH level

crop: The target variable representing the type of crop

Project Structure

The project follows these steps:

Data Loading and Preprocessing: The dataset is loaded, and missing values are checked.
Feature Selection and Splitting: The dataset is split into training and testing sets.
Model Training: Logistic regression is applied to each feature individually to determine its predictive power.
Performance Evaluation: F1-scores are calculated for each feature to find the best predictor.
Best Feature Selection: The feature with the highest F1-score is used to train a final model.
Crop-wise Performance Analysis: The best predictive feature is used to determine the most suitable crop for a given soil sample.

Implementation Details
The project is implemented in Python using the following libraries:
pandas: For data manipulation and analysis
scikit-learn: For model training, evaluation, and splitting data
