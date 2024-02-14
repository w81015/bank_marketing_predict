[中文版本](README_zh.md)
# Bank Marketing Strategy Analysis

## Project Introduction

This project focuses on analyzing and improving bank marketing strategies. By preprocessing data and applying logistic regression models, it aims to predict which customers might be interested in the bank's term deposit products. The script uses `pandas` for data analysis, `matplotlib` and `seaborn` for data visualization, and `sklearn`'s SVM for model training and prediction.

## Installation Guide

To run this script, ensure Python and the following packages are installed:

- pandas
- matplotlib
- seaborn
- sklearn

## Program Content and Results

The script begins with preprocessing the bank marketing dataset, including cleaning data, handling missing values and outliers, and visualizing the data to better understand the distribution and relationship between features. Then, SVM models are trained and used for prediction, aiming to forecast customer responses to the bank's term deposit offerings.

### Data Preprocessing
1. Data Inspection: Load the data and perform basic checks, including displaying the head of the dataset and overviewing statistical information.
2. Data Visualization: Use matplotlib and seaborn to visualize key features such as customer age distribution and job categories, providing insights into the data characteristics.

### Model Training and Evaluation
1. Model Construction: Build a SVM model.
2. Model Evaluation: Evaluate the models using confusion matrix.

### Outcome Analysis
Through data analysis and model training, identify characteristics of customer groups highly responsive to the bank's term deposit products, thereby helping the bank more accurately target potential customers, improving marketing efficiency and success rate.

## References

- [Bank Marketing Dataset](https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset)
