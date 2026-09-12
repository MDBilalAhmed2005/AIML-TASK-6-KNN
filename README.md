# Task 6 - K-Nearest Neighbors (KNN) Classification

## Objective

The objective of this task is to understand and implement the K-Nearest Neighbors (KNN) algorithm for classification.

## Dataset

The Iris dataset from Scikit-learn was used.

It contains:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The dataset contains three classes:
- Setosa
- Versicolor
- Virginica

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Steps Performed

1. Loaded the Iris dataset.
2. Converted the dataset into a Pandas DataFrame.
3. Checked the dataset for missing values.
4. Separated features and target values.
5. Split the dataset into training and testing data.
6. Normalized the features using StandardScaler.
7. Implemented K-Nearest Neighbors using KNeighborsClassifier.
8. Tested different values of K.
9. Compared accuracy for different K values.
10. Selected the best K value.
11. Evaluated the final model using accuracy.
12. Created a confusion matrix.
13. Visualized the KNN decision boundary.

## Results

Different K values were tested and their accuracies were compared.

The KNN model achieved high classification accuracy on the Iris dataset.

The confusion matrix shows the classification performance for the three Iris classes.

## Visualizations

The project includes:

- `knn_accuracy.png` - Accuracy for different K values
- `confusion_matrix.png` - Confusion matrix of the final model
- `decision_boundary.png` - KNN decision boundary visualization

## What I Learned

- KNN is a simple, instance-based machine learning algorithm.
- KNN classifies data using the nearest data points.
- Feature normalization is important because KNN uses distance calculations.
- The value of K affects model performance.
- KNN can handle multi-class classification.
- Accuracy and confusion matrix can be used to evaluate classification models.

## Interview Questions

### 1. How does KNN work?

KNN finds the K nearest data points to a new data point and assigns the class based on majority voting.

### 2. How do you choose the right K?

Different K values can be tested and the value giving the best validation performance can be selected.

### 3. Why is normalization important in KNN?

KNN uses distance calculations. Normalization prevents features with larger numerical values from dominating the distance.

### 4. What is the time complexity of KNN?

KNN has very little training cost because it mainly stores the training data. Prediction can be computationally expensive because distances must be calculated to training points.

### 5. What are the advantages and disadvantages of KNN?

Advantages:
- Simple to understand
- Easy to implement
- Works for classification and regression

Disadvantages:
- Prediction can be slow for large datasets
- Sensitive to feature scaling
- Sensitive to noise
- Choosing the correct K is important

### 6. Is KNN sensitive to noise?

Yes. Especially when a small value of K is used, noisy data can affect the prediction.

### 7. Can KNN handle multiple classes?

Yes. KNN can classify data into multiple classes using majority voting.

### 8. What is the role of distance metrics?

Distance metrics determine how close two data points are. Common examples include Euclidean distance, Manhattan distance, and Minkowski distance.