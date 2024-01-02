# Cirrhosis-classification
Kaggle ran its last playground competition of 2023 as a multi class classification problem, aiming to predict types of liver Cirrhosis.

https://www.kaggle.com/competitions/playground-series-s3e26

My solution was amongst the top 2% of entries and this repository shares the work I did to achieve this. For ease of reading and a more modular presentation, I have divided my original notebook into the following three topics:

* Exploratory Data Analysis: A few visualisations showing the target variable distributed across the other fields.
* Model Selection: Baseline classifiers are fitted without hyperparameter tuning to decide which models will be selected in the final ensemble.
* Model Development: Top 3 baseline classifiers are fitted with hyperparameter tuning aiming to minimise logloss (the metric evaluating the competition)

