# Analysis of Second Hand Car Sales Data with Supervised and Unsupervised Learning Models

## Project Overview
This project aims to predict car prices using various machine learning techniques, including regression models and clustering algorithms. The analysis focuses on understanding how different factors, such as the year of manufacture, mileage, and engine size, influence car prices.

## Table of Contents
- [Introduction](#introduction)
- [Data](#data)
- [Models](#models)
  - [Single Numerical Feature Regression Models](#single-numerical-feature-regression-models)
  - [Multiple Numerical Features Regression Models](#multiple-numerical-features-regression-models)
  - [Incorporating Categorical Variables](#incorporating-categorical-variables)
  - [Artificial Neural Network (ANN) Model](#artificial-neural-network-ann-model)
  - [Clustering Analysis](#clustering-analysis)
  - [Comparing Clustering Algorithms](#comparing-clustering-algorithms)
- [Conclusion](#conclusion)

## Introduction
Predicting the price of a car is a challenging task due to various influencing factors. This study analyzes the effectiveness of different machine learning models in predicting car prices using a dataset with numerical and categorical features. 

## Data
The dataset used in this analysis contains various features related to second-hand car sales, including numerical variables (e.g., year of manufacture, mileage) and categorical variables (e.g., make, model).

## Models

### Single Numerical Feature Regression Models
Evaluated regression models (linear and polynomial) using single features: year of manufacture, mileage, and engine size.

### Multiple Numerical Features Regression Models
Combined multiple numerical features to assess predictive accuracy, focusing on the Gradient Boosting Regressor (GBR).

### Incorporating Categorical Variables
Trained a Random Forest Regressor using both numerical and categorical features to evaluate the impact of including relevant variables.

### Artificial Neural Network (ANN) Model
Developed an ANN model to predict car prices, achieving significant accuracy improvements through hyperparameter tuning.

### Clustering Analysis
Implemented k-Means clustering to identify potential groupings within the car sales data.

### Comparing Clustering Algorithms
Applied BIRCH clustering and compared its performance to k-Means, revealing distinct patterns in the data.

## Conclusion
This study demonstrates that advanced regression models and ANN significantly enhance predictive accuracy for car prices. Additionally, clustering analysis provides insights into data patterns, informing potential business strategies.
