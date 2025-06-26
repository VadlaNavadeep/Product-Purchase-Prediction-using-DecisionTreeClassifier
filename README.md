# 🛒 Product Purchase Prediction using Decision Tree

This project demonstrates how to use a **Decision Tree Classifier** to predict whether a person will buy a product based on their **Age** and **Income**. It's a simple machine learning example using a small sample dataset.

---

## 🎯 Objective

Given a person’s `Age` and `Income`, predict whether they are likely to **Buy** a product (`Yes` or `No`) using a **Decision Tree** algorithm.

---

## 📊 Dataset

A small, hardcoded dataset is used with the following features:

| Age | Income | Buy |
|-----|--------|-----|
| 22  | 25000  | No  |
| 25  | 32000  | No  |
| 47  | 85000  | Yes |
| 52  | 90000  | Yes |
| 46  | 60000  | Yes |
| 56  | 95000  | Yes |
| 55  | 75000  | Yes |
| 60  | 62000  | No  |

- `Age`: Age of the person
- `Income`: Annual income in currency units
- `Buy`: Whether the person bought the product (`Yes` or `No`)

---

## 🧰 Libraries Used

```python
import pandas as pd
from sklearn.tree import DecisionTreeClassifier
from sklearn import tree
import matplotlib.pyplot as plt
