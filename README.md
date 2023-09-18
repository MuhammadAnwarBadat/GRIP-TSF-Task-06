# Iris Flower Classification Using Decision Tree Algorithm

This repository contains a Jupyter Notebook (GRIP TSF Task-06.ipynb) that demonstrates the use of a Decision Tree Algorithm for predicting iris flower species based on their features. The task involves loading the IRIS dataset, splitting the data, training a Decision Tree Classifier, making predictions, evaluating the classifier's performance, and visualizing the Decision Tree.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Loading the IRIS Dataset](#loading-the-iris-dataset)
- [Splitting Data for Training and Testing](#splitting-data-for-training-and-testing)
- [Creating and Training the Decision Tree Classifier](#creating-and-training-the-decision-tree-classifier)
- [Making Predictions](#making-predictions)
- [Evaluating the Classifier](#evaluating-the-classifier)
- [Visualizing the Decision Tree](#visualizing-the-decision-tree)
- [Conclusion](#conclusion)

## Introduction

This project demonstrates the use of a Decision Tree Algorithm for classifying iris flowers into different species based on their sepal and petal measurements. The code is implemented in Python and utilizes libraries such as NumPy, pandas, matplotlib, and Scikit-Learn.

## Getting Started

To run this project, you can use a Jupyter Notebook environment. The notebook is self-contained and can be executed cell by cell. The code is also hosted on Google Colab, making it easy to run and experiment with. You can access the original notebook at [this link](https://colab.research.google.com/drive/1u642cANlIjC0cVO7_jRCb2KqXiyNLzS6).

## Loading the IRIS Dataset

In this step, the IRIS dataset is loaded, which contains measurements of iris flowers' sepal length, sepal width, petal length, and petal width, along with their corresponding species labels. The dataset is then split into features (`X`) and target labels (`y`).

## Splitting Data for Training and Testing

The dataset is split into training and testing sets to train the Decision Tree Classifier and evaluate its performance. This ensures that the model's performance can be assessed independently.

## Creating and Training the Decision Tree Classifier

A Decision Tree Classifier is created with random state set to ensure reproducibility. The classifier is then trained using the training data.

## Making Predictions

The trained Decision Tree Classifier is used to make predictions on the testing data. The predicted labels are stored for evaluation.

## Evaluating the Classifier

The classifier's performance is evaluated using accuracy as a metric. The `accuracy_score()` function from Scikit-Learn is used to compute the accuracy of the model's predictions compared to the true labels.

## Visualizing the Decision Tree

A graphical visualization of the Decision Tree is created using the `tree.plot_tree()` function. This visualization helps in understanding how the classifier makes decisions based on feature values.

## Conclusion

This project demonstrates the use of a Decision Tree Algorithm to classify iris flowers based on their features. The visualization of the Decision Tree provides insights into the decision-making process of the classifier. You can further analyze the tree for insights and adapt the code for similar classification tasks.

---

You can create a README.md file in your GitHub repository and paste this content to provide an explanation of your project and how to use it.
