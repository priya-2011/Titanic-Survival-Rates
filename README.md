# Titanic-Survival-Rates


The sinking of the Titanic is one of history's most notorious maritime disasters. On April 15, 1912, during its maiden voyage, the RMS Titanic—often touted as "unsinkable"—struck an iceberg and tragically sank. With insufficient lifeboats available, 1,502 of the 2,224 passengers and crew lost their lives. Although survival had an element of chance, certain groups appeared to have a higher likelihood of surviving than others. The training dataset provides details on a subset of the passengers (891 individuals), including whether they survived. The test dataset, comprising 418 passengers, contains similar details but does not reveal the survival outcome. This project applies a machine learning approach to analyze various passenger features—such as age, sex, and ticket class—to predict survival outcomes, shedding light on the factors that influenced survival.

## Dataset


The dataset used in this project contains information about passengers aboard the Titanic, including details such as age, sex, passenger class, fare, and survival status (0 = did not survive, 1 = survived). The dataset is derived from the Titanic dataset, which is publicly available and widely used for machine learning practice.

The dataset can be found here:

1. https://www.kaggle.com/datasets/yasserh/titanic-dataset
2. https://www.kaggle.com/datasets/ashishkumarjayswal/titanic-datasets

## Preprocessing

The following preprocessing steps were performed on the dataset:

- Handling missing values (e.g., filling missing age data).
- Encoding categorical variables (e.g., Sex, Embarked).
- Scaling numerical features (e.g., Age, Fare).
- Dropping irrelevant columns (e.g., Name, Ticket, Cabin).

## Models Implemented


Supervised learning techniques were employed to predict survival status. The algorithms implemented include:

1. Logistic Regression - A simple yet powerful classifier for binary outcomes.
2. Random Forest Classifier - An ensemble learning method for improved accuracy.
3. Support Vector Machine (SVM) - A robust classifier with kernel functions.
4. Decision Tree Classifier - A tree-based model for clear decision paths.
5. K-Nearest Neighbors (KNN) - A non-parametric algorithm based on proximity.

## Setup
Create new Python environment
```
conda create -n pyenv python=3.9
```
Activate the environment.
```
conda activate pyenv
```
