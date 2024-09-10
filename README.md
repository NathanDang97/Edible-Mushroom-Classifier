# Edible Mushroom Classifier

## Overview 

This project is part of 2024 Kaggle Playground Series! The goal of this competition is to predict whether a mushroom is edible or poisonous based on its physical characteristics. The dataset for this competition (both train and test) was generated from a deep learning model trained on the [UCI Mushroom dataset](https://archive.ics.uci.edu/dataset/73/mushroom). The training set contains 3116945 data points; the test set contains 2077964 data points; and there are a total of 22 features. Feature distributions are close to, but not exactly the same, as the original. Feel free to use the original dataset as part of this competition, both to explore differences as well as to see whether incorporating the original in training improves model performance.

More information about the competition can be found [here](https://www.kaggle.com/competitions/playground-series-s4e8/overview)

## Data Description

Below is the description of each attached data files in this project. The files can be found under the Data folder in this repository.

- train.csv - the training set containing 3116945 data points, each with 22 features
- test.csv - the test set containing 2077964 data points

**Note:** Unlike many previous Tabular Playground datasets, data artifacts in this Playground Competition have not been cleaned up. There are categorical values in the dataset that are not found in the original. 

## Implementation 

We implemented a Random Forest Classifier which achieved an accuracy score of 0.9872. Full implementation with all steps (EDA, Feature Engineering, Model Devlopment, and Evaluation) can be found under the Main Folder in this repository.
