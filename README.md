# Iris Classification Project

## Introduction
This project is focused on classifying the species of iris plants into one of three species (setosa, versicolor, or virginica) based on measurements of their petals and sepals. The dataset used is the famous Iris flower dataset, which is often used for such classification problems.

## Methods
The classification has been performed using four different machine learning algorithms:
- Linear Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- XGBoost

## Dependencies
- Python 3
- NumPy
- pandas
- scikit-learn
- XGBoost
- Jupyter Notebook

For a complete list of dependencies, refer to the `requirements.txt` file.

## Installation
To run this project, you need to install the necessary dependencies. It is recommended to use a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
```

## Data
The dataset contains 150 observations of iris plants. There are four features: sepal length, sepal width, petal length, and petal width. The goal is to predict the species of the iris plant.

## Usage
To run the project, open the main.ipynb Jupyter notebook and execute the cells. The notebook includes detailed steps and explanations for each of the classification methods used.

## Results
The performance of each model has been evaluated and compared. The results are summarized in the Jupyter notebook in terms of accuracy, precision, recall, and F1-score.

## Conclusion
This project showcases the use of different machine learning algorithms to solve a classification problem. The comparison reveals insights into the effectiveness of each method for this particular dataset.
