# Spotify-Hit-Predictor

Overview
The Spotify Hit Predictor project leverages advanced data analytics and predictive modeling to forecast the success of songs using the "Spotify Hit Predictor Dataset" from Kaggle. This repository contains all necessary scripts, data, and documentation to understand and replicate the analysis that predicts whether a song will become a hit based on various audio features and metadata.

Key Features
Comprehensive Dataset: Utilizes a dataset of 6399 tracks released in 2010, with rich audio features and metadata.
Exploratory Data Analysis (EDA): Detailed EDA to uncover trends and correlations between song features and their success.
Predictive Modeling: Implements Support Vector Machine (SVM) models with different kernels (Radial, Linear, Polynomial) to classify songs as hits or flops.
Performance Metrics: Evaluation using ROC curves, AUC, accuracy, precision, recall, and F1-score to ensure robust model performance.
Actionable Insights: Provides valuable insights for artists, producers, and industry stakeholders to inform production and marketing strategies.

Usage
Data Preparation:
Load and preprocess the dataset.
Perform EDA to visualize and understand the data.
Model Training:
Train SVM models using different kernels.
Perform grid search for hyperparameter tuning.
Evaluation:
Evaluate model performance using various metrics.
Analyze ROC curves and AUC for model comparison.
Results and Insights
Songs with higher energy, danceability, loudness, and valence are more likely to be hits.
Shorter duration tracks have a higher probability of success.
Polynomial SVM model shows the best performance with near-perfect classification accuracy.
