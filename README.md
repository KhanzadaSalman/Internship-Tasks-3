# 🌸 Iris Flower Classification (Task 3)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Type](https://img.shields.io/badge/Type-Classification-purple)
![Status](https://img.shields.io/badge/Status-Completed-green)

This repository contains the source code for **Task 3: Iris Flower Classification**. This project focuses on Advanced Exploratory Data Analysis (EDA) and high-accuracy classification.

## 📌 Objective
To classify Iris flowers into three species (*Setosa, Versicolor, Virginica*) based on sepal and petal measurements.

## 🔍 Advanced Features
This project goes beyond basic modeling to include deep visual analysis:
* **Visual Context:** Displaying real images of the flower species.
* **Violin Plots:** Analyzing the density and distribution of Petal Length.
* **3D Scatter Plots:** Visualizing clusters in a 3-dimensional feature space.

## 🛠️ Technologies Used
* **Scikit-Learn:** For loading the built-in dataset and training KNN/Logistic Regression.
* **Seaborn:** For Pairplots and Violin plots.
* **Matplotlib (mplot3d):** For 3D plotting.

## 📊 Results
* **Accuracy:** 100% (Perfect Classification).
* **Why?** The dataset is linearly separable. The feature "Petal Length" provides a distinct boundary between *Setosa* and the other species, allowing the model to make perfect predictions.

## 🚀 How to Run
1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
