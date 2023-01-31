# KNN Classifier from Scratch in Python
This code implements the k-nearest neighbors (KNN) classifier algorithm from scratch in Python, using a sample training and test datasets. The goal is to predict the class of a new instance based on its proximity to the k-nearest instances in the training data. The distance between instances is computed using Euclidean distance.

The code is divided into several steps:

1. Load the training and test datasets using Pandas.
2. Initialize a distance matrix to store the Euclidean distance between each instance in the training data and each instance in the test data.
3. Fill the distance matrix by computing the Euclidean distance between each pair of instances.
4. For each test instance, find the indices of the k-nearest neighbors in the training data based on the distance matrix.
5. Compute the frequency of each class among the k-nearest neighbors and assign the class with the highest frequency to the test instance.
6. The code also includes a comparison with the KNN classifier from the scikit-learn library, which provides a more efficient implementation of the KNN algorithm.

## Prerequisites
The following packages must be installed to run the code:

1. numpy
2. pandas
3. scikit-learn
## Usage
The code can be run as a standalone script in a Python environment, using the sample training and test datasets provided. The k-nearest neighbors algorithm can be run using the following command:

"python knn_classifier.py"

## Example Output
The output of the code includes the predicted classes for each test instance, both for the KNN classifier from scratch and for the KNN classifier from scikit-learn.

## Note
The code is intended for educational purposes and is not optimized for large datasets. The scikit-learn implementation of KNN is much more efficient and scalable, and is recommended for real-world applications.
