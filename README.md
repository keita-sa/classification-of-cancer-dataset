# Classification of Cancer Dataset by Logistic Regression

## Overview

This is an example of a machine learning implementation using logistic regression for classification. In this case, a dataset consisting of 569 instances of cancer is employed to predict whether each instance is malignant (labeled 0) or benign (labeled 1), based on 30 features of each instance. This problem is referred to as a two-class problem, given its task of distinguishing between malignant and benign cases.

## Installation

### Prerequisites
- Jupyter Notebook
- NumPy
- Pandas
- scikit-learn

### Setup
From the `<> code` bottun, you can download the ipynb file in JSON format. Then open it in Jupyter Notebook, you can reproduce exactly the same outputs.

## Method
First, the dataset is split into training and test data. Next, created a classifier and trained using the training data. Here, we create a logistic regression classifier. Based on the training outputs, we make predictions on the test data. We then check how well the predictions match the original test data.

Statistical learning is performed using feature values such as cancer radius and surface textures, enabling predictions to be made for unknown data, such as whether it is malignant.

## Result
In this example, 8 out of 171 were found to be wrong. Since the accuracy seems to be quite high, it seems that there were good features to begin with and the classification problem was not that difficult.



## References
"Machine-Learning by Python; An introduction to classification with scikit-learn", Toru Tamaki (2020), Udemy.



