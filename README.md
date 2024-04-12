# Titanic-Machine-Learning-Survival

This project aims to predict survival on the Titanic using various machine learning models. The Titanic dataset contains information about passengers, including their age, sex, ticket class, and whether they survived or not.

## Table of Contents

- [Introduction](#introduction)
 - [Models Used](#ModelsUsed)
 - [Evaluation Metrics](#EvaluationMetrics)
- [Usage](#usage)

  
## Introduction

The Titanic dataset offers insights into passengers aboard the RMS Titanic. This project aims to predict survival based on factors like age, sex, and ticket class using machine learning. Through algorithms such as logistic regression, decision trees, and ensemble methods. Evaluation metrics like accuracy and F1 score guide our model selection, while techniques like GridSearchCV optimize performance.


## Models Used

- **Logistic Regression (Perceptron):** A classic linear classification algorithm modeling the probability of a binary outcome.
  
- **Decision Tree:** Decision trees recursively split the data based on features to create a tree-like structure.
  
- **Support Vector Machine (SVM):** SVM finds the hyperplane that best separates classes in the feature space.
  
- **RandomForestClassifier:** RandomForestClassifier constructs a multitude of decision trees and outputs the mode of the classes for classification tasks.
  
- **GradientBoostingClassifier:** Gradient boosting produces an ensemble of weak prediction models, typically decision trees.
  
- **AdaBoostClassifier:** AdaBoost fits a sequence of weak learners on different weighted training data, adjusting the weights of incorrectly classified instances.

## Evaluation Metrics

For evaluating model performance, two metrics were used:

- **Accuracy:** Measures the overall correctness of the model's predictions.
  
- **F1 Score:** Provides a balance between precision and recall.

## Additional Information

- **GridSearchCV:** Used for finding the best parameters for the SVM model, optimizing its performance on the given dataset.

## Usage

1. Clone this repository.
2. Ensure you have Python and necessary libraries installed.
3. Run the provided scripts or integrate the models into your Python environment.
4. Analyze the results and fine-tune the models as needed.

