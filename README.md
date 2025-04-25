# IrisFlowerClassification
Project using Machine Learning

## Description

The **Hello World** of Machine Learning:  
**Iris Flower Classification**

### Classes of flowers (species):
- *Iris-setosa*
- *Iris-versicolor*
- *Iris-virginica*

### Features for each flower:
- Sepal length
- Sepal width
- Petal length
- Petal width

### Machine Learning Category:
**Supervised Learning**  
Using an algorithm called **Support Vector Machine (SVM)** (*Support Vector Network*).

---

## How SVM Works
- SVM analyzes data for **classification** and **regression** tasks.
- It approximates a separating **hyperplane** (a line in 2D, a plane in 3D, and a higher-dimensional surface beyond that) between classes.
- It identifies **support vectors** — the points closest to the hyperplane.
- It selects the hyperplane with the **largest possible margin** between the two classes.

---

## Handling Multi-Class Classification
SVM is originally designed for **binary classification**.  
For multi-class problems, it is broken down into multiple binary classifications:

- **One-vs-Rest**:
  - Class 1 vs All other classes
- **One-vs-One**:
  - Class 1 vs Class 2
  - Class 1 vs Class 3
  - Class 2 vs Class 3

## Goal
Train a model that can accurately classify new iris flower observations into their correct species!

---

## Requirements
- Python 3.x
- scikit-learn
- pandas helps to load data 
- matplotlib for data visualization 
- numpy for computational operations 
- seaborn for data visualization 

> Install all dependencies using:
> ```bash
> pip install -r requirements.txt
> ```

---
