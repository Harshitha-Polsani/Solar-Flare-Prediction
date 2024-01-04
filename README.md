# Solar Flare Prediction Using Machine Learning
# Overview
This project aims to predict solar flares using a machine learning-based approach. It leverages various ensemble methods to analyze and classify solar flare events based on their intensity. The project focuses on predicting four classes of solar flares (B, C, M, X) using key physical parameters and data provided by the Space Weather HMI Active Region Patches (SHARP).

# Dataset
The dataset consists of important SHARP physical parameters extracted from X-ray flare catalogs provided by the National Centers for Environmental Information (NCEI) and solar images available at the Joint Science Operations Center (JSOC). The data includes:

845 samples from 472 active regions.

13 selected SHARP physical features for analysis.

Classes B, C, M, and X, with varying magnitudes of flares.

# Methodology
The project involves several key steps:

Data Preprocessing and Feature Selection: Using univariate feature selection to identify the top 13 SHARP parameters.
Model Training and Testing: Employing machine learning models like Random Forest, K Nearest Neighbors, Naive Bayes, Support Vector Machines, Bagging Classifier, Gradient Boosting Classifier, and others.

# Results
The system achieved high accuracy in predicting solar flares, demonstrating the effectiveness of ensemble methods in handling this complex classification task. The project provides insights into predicting solar flare occurrences, aiding in better understanding and forecasting space weather events.
