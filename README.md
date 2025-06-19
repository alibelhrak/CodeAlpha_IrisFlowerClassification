# 🌸 Iris Flower Classification

This project is part of my internship at **CodeAlpha**. The goal is to build a machine learning model that can classify Iris flowers into three species: **Setosa**, **Versicolor**, and **Virginica**, based on their measurements.

## 📌 Task Description

- Use measurements of Iris flowers as input data.
- Train a machine learning model to classify the species.
- Utilize Scikit-learn for dataset access and model building.
- Evaluate model accuracy and performance.
- Gain a foundational understanding of classification in machine learning.

## 📊 Dataset

The classic **Iris dataset** is used for this task. It includes the following features:
- Sepal length
- Sepal width
- Petal length
- Petal width

Target: Iris species (`Setosa`, `Versicolor`, `Virginica`)

## 🛠️ Libraries Used

```python
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
from sklearn.preprocessing import LabelEncoder
from sklearn.model_selection import train_test_split
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.linear_model import SGDClassifier, LogisticRegression
from sklearn.metrics import accuracy_score
```


🚀 Models Trained
Two classifiers were implemented:

SGDClassifier

LogisticRegression

✅ Results
SGDClassifier Accuracy: 93.33%

Logistic Regression Accuracy: 100%

These results show that the Logistic Regression model performed exceptionally well on this dataset.

📈 Conclusion
This task helped in understanding the basic steps of a supervised classification problem using scikit-learn, including data loading, preprocessing, model training, and evaluation.
