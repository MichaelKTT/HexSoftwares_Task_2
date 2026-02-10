🌸 Iris Flower Classification Project
📌 Project Overview

This project demonstrates a complete machine learning workflow using the famous Iris dataset.
The goal is to build a model that can classify iris flowers into their correct species based on their physical measurements.

The project covers:

Data exploration

Data preprocessing

Model training

Model evaluation

Visualization of results

📊 Dataset Description

The Iris dataset is a classic dataset in machine learning and statistics.

Dataset characteristics:

150 flower samples

4 numerical features:

Sepal length

Sepal width

Petal length

Petal width

3 target classes:

Setosa

Versicolor

Virginica

The dataset was loaded using Seaborn.

🧠 Model Used

Algorithm: Logistic Regression
Library: Scikit-learn

Why Logistic Regression?

Simple and easy to interpret

Good baseline classification model

Performs well on small, structured datasets

⚙️ Project Workflow
1. Data Exploration

Loaded the dataset.

Checked the structure of the data.

Verified missing values.

Visualized feature distributions using:

Histograms

Boxplots

Pairplots

2. Data Preparation

Separated features (X) and target (y).

Split the dataset into:

80% training data

20% testing data

3. Model Training

Trained a Logistic Regression model using the training data.

4. Model Evaluation

The model was evaluated using:

Accuracy

Precision

Recall

Confusion Matrix

Classification Report

📈 Results
Overall Performance

The model achieved:

Accuracy: ~95% – 100%

High precision and recall across all classes

Key Observations

Setosa is classified almost perfectly because it is clearly distinct.

Versicolor and Virginica show slight overlap, causing minor misclassifications.

Petal features were the most important for classification.

🔍 Confusion Matrix

The confusion matrix shows:

Most predictions on the diagonal → correct classifications.

Very few off-diagonal values → low error rate.

This indicates strong model performance.

🧾 Classification Report

The classification report provides:

Precision

Recall

F1-score

Support (number of samples per class)

All classes achieved high scores, confirming the effectiveness of the model.

🛠️ Technologies Used

Python

Pandas

Seaborn

Matplotlib

Scikit-learn
