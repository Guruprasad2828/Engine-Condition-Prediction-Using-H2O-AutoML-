# Engine Condition Classification with H2O AutoML

This project demonstrates the application of H2O AutoML, an advanced automated machine learning platform, to efficiently classify engine conditions using sensor data. The process involves loading, preprocessing, and preparing a substantial automotive dataset, including encoding categorical features and splitting the data into stratified training and testing sets. H2O is initialized to leverage distributed computing for rapid and scalable model training.

Using H2O AutoML, multiple machine learning models and stacked ensembles are trained with balanced class settings to address data imbalance. A leaderboard ranks the models based on evaluation metrics such as AUC, facilitating the selection of the best-performing models. The chosen models are then evaluated using hold-out test data to ensure robust performance with metrics including accuracy and ROC AUC.

Further improvements are achieved by fine-tuning top models with hyperparameter optimization and feature engineering. The project also emphasizes the benefits of GPU acceleration to speed up training and handle complex model architectures effectively. This workflow exemplifies how modern AutoML platforms can democratize machine learning, reduce development time, and deliver scalable solutions for predictive maintenance in the automotive domain.


Dataset : https://www.kaggle.com/datasets/parvmodi/automotive-vehicles-engine-health-dataset?select=engine_data.csv

H20: https://h2o.ai/
