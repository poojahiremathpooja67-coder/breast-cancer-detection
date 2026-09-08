# breast-cancer-detection
Breast Cancer Detection using Machine Learning is a machine-learning project designed to classify breast tumor data into two categories: Benign and Malignant. The project processes numerical tumor features, prepares the dataset, standardizes the data, and trains a Logistic Regression classification model. 

## 1 Project Overview

Breast Cancer Detection is a machine-learning project that predicts whether a breast tumor is **Benign** or **Malignant** based on numerical tumor characteristics.

The project uses **Logistic Regression**, a classification algorithm suitable for binary classification problems.

## 2 Objectives

* Understand and analyze breast tumor data.
* Check and prepare the dataset.
* Identify important tumor features.
* Split the dataset into training and testing data.
* Standardize numerical features.
* Train a Logistic Regression model.
* Predict tumor classification.
* Evaluate the performance of the model.

## 3 Technologies Used

* **Python**
* **Pandas** – Data handling and analysis
* **Matplotlib** – Data visualization
* **Scikit-learn** – Machine learning and model evaluation

## 4 Project Files

```text
Breast_Cancer_Detection/
│
├── breast_cancer_detection.py
├── breast_cancer.csv
├── requirements.txt
└── README.md
```

##  Dataset

The dataset contains numerical measurements related to breast tumors, including features such as:

* Mean radius
* Mean texture
* Perimeter
* Area
* Smoothness
* Compactness
* Concavity
* Symmetry
* Fractal dimension

The target variable is **diagnosis**, which contains two classes:

* **Benign**
* **Malignant**

## 5 Project Workflow

1. Load the dataset using Pandas.
2. Display the first few records.
3. Check the dataset shape and missing values.
4. Analyze the diagnosis distribution.
5. Separate input features and the target variable.
6. Split the data into training and testing sets.
7. Standardize the numerical features using `StandardScaler`.
8. Train a Logistic Regression model.
9. Generate predictions.
10. Calculate model accuracy.
11. Generate a classification report and confusion matrix.
12. Visualize selected tumor features.

## 6 Machine Learning Algorithm

### Logistic Regression

Logistic Regression is used to classify the tumors into two categories: **Benign** and **Malignant**.

The data is standardized before training so that features with different numerical scales can be handled effectively by the model.

## 7 Model Evaluation

The project evaluates the model using:

* **Accuracy Score**
* **Classification Report**
* **Confusion Matrix**

These metrics help measure how well the model performs on previously unseen test data.

## 8 Visualization

The program creates a scatter plot showing the relationship between:

* **Mean Radius**
* **Mean Texture**

The generated image is saved as:

```text
breast_cancer_features.png
```

## 9 Installation

Make sure Python is installed on your computer.

Install the required libraries using:

```bash
pip install -r requirements.txt
```

## 10 How to Run

Open a terminal in the project folder and run:

```bash
python breast_cancer_detection.py
```

The program displays:

* Dataset information
* Missing-value information
* Diagnosis distribution
* Model accuracy
* Classification report
* Confusion matrix
* Example prediction

It also generates a feature visualization.

