# Spaceship-Titanic
This repository contains my solution for the [Kaggle Spaceship Titanic Competition](https://www.kaggle.com/competitions/spaceship-titanic), where the goal is to predict whether passengers were **transported to an alternate dimension** based on their personal and travel records.

## 📌 Problem Statement

During the collision of the Spaceship Titanic with a spacetime anomaly, some passengers were teleported to another dimension. Using personal records, our task is to predict who got transported (`Transported = True`) and who didn't.


### Steps followed:

1. **Data Preprocessing**
2. **Feature Engineering**
3. **Modeling**
   - Used **XGBoost Classifier** with hyperparameter tuning.
4. **Evaluation**
   - Average CV Accuracy: ~82–85%
