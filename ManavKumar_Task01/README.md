# Iris Flower Classification using Machine Learning

## Overview

This project focuses on the classification of Iris flower species using Machine Learning. The model is trained on the famous Iris dataset and predicts the species of a flower based on its sepal and petal measurements.

The dataset contains three different Iris species:

* Iris Setosa
* Iris Versicolor
* Iris Virginica

The objective is to build a classification model that can accurately identify the species from the given flower measurements.

---

## Dataset Features

The model uses the following input features:

| Feature      | Description              |
| ------------ | ------------------------ |
| Sepal Length | Length of the sepal (cm) |
| Sepal Width  | Width of the sepal (cm)  |
| Petal Length | Length of the petal (cm) |
| Petal Width  | Width of the petal (cm)  |

Target Variable:

* Species

---

## Project Workflow

1. Data Collection and Loading
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Train-Test Split
5. Model Training
6. Model Evaluation
7. Species Prediction

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Machine Learning Algorithm

The project uses the **Random Forest Classifier**, an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

## Model Evaluation

The model performance is evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix (Optional)

The trained model achieves high classification accuracy on the test dataset.

---

## Sample Prediction

Input:

```text
Id: 1
Sepal Length: 5.1
Sepal Width: 3.5
Petal Length: 1.4
Petal Width: 0.2
```

Predicted Output:

```text
Iris Setosa
```

---

## Learning Outcomes

Through this project, the following concepts were explored:

* Data preprocessing using Pandas
* Data visualization
* Feature selection
* Supervised Machine Learning
* Classification algorithms
* Model evaluation and performance analysis

---

## Future Enhancements

* Deploy the model using Flask or Streamlit
* Build a web-based prediction interface
* Experiment with additional classification algorithms
* Perform hyperparameter tuning for improved performance

---

## Author

Manav Kumar

Project completed as part of the Machine Learning Internship Program.
