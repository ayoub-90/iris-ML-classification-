# Iris Classification Project

## Overview
This project implements a machine learning model to classify iris flowers based on their features using the Iris dataset. The model utilizes the K-Nearest Neighbors (KNN) algorithm to predict the species of iris flowers.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model](#model)
- [Evaluation](#evaluation)
- [Contributing](#contributing)

## Installation
To run this project, you'll need to have Python installed along with the required libraries. You can install the necessary packages using pip:

```bash
pip install pandas scikit-learn seaborn matplotlib
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/ayoub-90/iris-ML-classification-.git
   cd iris-classification
   ```

2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook sample.ipynb
   ```

## Data
This project uses the Iris dataset, which is available at the UCI Machine Learning Repository. The dataset includes the following features:
- **Sepal Length**: Length of the sepal in centimeters.
- **Sepal Width**: Width of the sepal in centimeters.
- **Petal Length**: Length of the petal in centimeters.
- **Petal Width**: Width of the petal in centimeters.
- **Class**: Species of iris (Setosa, Versicolor, Virginica).

## Model
The project implements the K-Nearest Neighbors (KNN) algorithm for classification. The model is trained on 70% of the data and tested on the remaining 30%. The model's performance is evaluated using accuracy, confusion matrix, and classification report.

## Evaluation
The model's performance is assessed through:
- **Accuracy**: The proportion of correct predictions.
- **Confusion Matrix**: A table that summarizes the performance of the classification model.
- **Classification Report**: Detailed metrics including precision, recall, and F1-score for each class.

## Contributing
Contributions are welcome! If you have suggestions for improvements or want to report issues, please create an issue or submit a pull request.
```