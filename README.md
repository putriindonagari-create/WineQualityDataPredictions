# Modelling Wine Quality Data Predictions
Created by : Putri Indo Nagari

This project focuses on building a robust classification model to predict the quality score of wine (on a scale of 0 to 10) based on its physicochemical properties. The model was trained using a dedicated training set (data_training.csv) and was used to generate quality predictions for the unlabelled testing set (data_testing.csv).

The dataset consists of two files:
data_training.csv: Used for model training, containing 11 physicochemical features and the target variable, quality.
data_testing.csv: Used for final predictions, containing only the physicochemical features and the Id column.
The features include variables such as fixed acidity, volatile acidity, citric acid, alcohol, and more.

The final predictions are stored in the following CSV file:
hasilprediksi_072.csv: Contains the predicted quality score for each corresponding Id from the testing dataset.
