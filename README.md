# Regression---Bike-Sharing-Demand-Prediction---Almabetter--Project
  This repository contains a machine learning project aimed at predicting the demand for bikes in a bike sharing system. Accurately forecasting bike demand can help optimize inventory and pricing strategies for bike rental companies. In this project, we develop a regression supervised machine learning model to predict bike demand in a given time period.

_**Dataset**__

The original dataset used in this project is obtained from a bike sharing company and includes information such as the number of bikes rented, the date and time of the rental, and various weather and seasonality features. Additionally, relevant factors that could impact bike demand, such as holidays and functioning or non-functioning days, are included.

_Approach__

The following steps were followed in the project:

Data Preprocessing: The dataset was preprocessed and cleaned to handle missing values, outliers, and any inconsistencies in the data.

Data Split: The preprocessed data was split into training and test sets. The training set was used to train our machine learning model, while the test set was used for evaluation.

Model Training: Several different machine learning model architectures and hyperparameter settings were experimented with. The models were trained using the training data, and their performances were evaluated using various metrics.

Model Evaluation: The performance of the trained models was evaluated using metrics such as mean absolute error, root mean squared error, and R-squared. The model that performed the best on the test data was selected.

Feature Importance: Ablation studies were conducted to understand the impact of individual features on the model's performance. The analysis revealed the significance of temperature, weather conditions, and seasonality features in predicting bike demand.

Model Deployment: The selected model was deployed in a live production setting, where it could make real-time predictions of bike demand. The model's performance was monitored over time to ensure its accuracy and usefulness.


