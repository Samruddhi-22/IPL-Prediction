
## IPL First Innings Score Predictor

A machine learning model to predict the first innings score in IPL matches using historical match data.


## Table of Contents





Overview



Features



Dataset



Installation



Usage



Model Performance



Technologies Used



Contributing



License



Contact
## Overview



The IPL First Innings Score Predictor is a machine learning project that predicts the final score of the first innings in Indian Premier League (IPL) matches. Using historical match data from 2008 to 2017, the project employs regression models to forecast scores based on features like batting/bowling teams, overs, runs, wickets, and recent performance (last 5 overs). The best-performing model, Linear Regression, achieves a Mean Absolute Error (MAE) of ~12 runs, demonstrating reliable predictions for cricket analytics.

This project is ideal for data science enthusiasts, sports analytics researchers, and developers interested in machine learning and predictive modeling.



## Feature


Score Prediction: Predicts first innings scores using team, overs, runs, wickets, and recent performance metrics.



Data Preprocessing: Cleans IPL dataset by removing inconsistent teams, early overs (<5), and irrelevant columns.



Multiple Models: Evaluates Linear Regression, Decision Tree, Random Forest, and AdaBoost for optimal performance.



Real-World Testing: Trained on IPL seasons 2008–2016, tested on 2017, and predicts for 2018–2019 matches.



Extensible: Easy to integrate new features (e.g., player stats, weather) or advanced models.
