# 🎨 Color Prediction Model Using RGB Values

## Overview

This project is a Machine Learning application that predicts the name of a color based on its RGB (Red, Green, Blue) values. The model is trained using a dataset containing RGB color values and corresponding color names.

The goal of this project is to understand the complete Machine Learning workflow, including:

* Loading datasets
* Data preprocessing
* Splitting data into training and testing sets
* Training a machine learning model
* Evaluating model performance
* Predicting color names from custom RGB inputs

---

## Dataset

The dataset contains color information in the following format:

| Red | Green | Blue | Color Name |
| --- | ----- | ---- | ---------- |
| 255 | 0     | 0    | Red        |
| 0   | 255   | 0    | Green      |
| 0   | 0     | 255  | Blue       |

Features used:

* Red (8 bit)
* Green (8 bit)
* Blue (8 bit)

Target:

* Color Name

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* VS Code

---

## Machine Learning Algorithm

This project uses the **K-Nearest Neighbors (KNN)** classification algorithm.

### Why KNN?

KNN is well-suited for color prediction because colors that are close together in RGB space often belong to similar color categories.

Example:

RGB(255, 0, 0) → Red

RGB(250, 10, 10) → Red

RGB(245, 20, 20) → Red

The model predicts the color based on the nearest RGB values present in the training dataset.

---

## Project Structure

```text
ColorPredictionModelUsingRGB/
│
├── color_names.csv
├── model.py
└── README.md
```


The model will:

1. Load the dataset
2. Split the dataset into training and testing sets
3. Train the KNN model
4. Evaluate model accuracy
5. Save the trained model

---


## Author

Developed as a Machine Learning practice project to understand color classification using RGB values and the K-Nearest Neighbors algorithm.
