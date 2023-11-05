# Iris-Flower-Classification
![Capture](https://github.com/Adnan079/Iris-Flower-Classification/assets/96575336/ee1bb45f-8fa5-44bb-ab25-5e7c6a4461de)
This program applies basic machine learning (classification) concepts on Fisher's Iris Data to predict the species of a new sample of Iris flower.

# Software and Libraries

Python 3.6.0
Anaconda 4.3.0 (32 bit)
scikit-learn 0.18.1

# Introduction
The dataset for this project originates from the UCI Machine Learning Repository. The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by the British statistician and biologist Ronald Fisher in his 1936 paper The Use of multiple measurements in Taxonomic Problems as an example of Linear Discriminant Analysis.

The data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica, and Iris versicolor).
Four features were measured from each sample (in centimeters):
Length of the sepals
Width of the sepals
Length of the petals
Width of the petals

# Working of the iris_decision_tree_classifier

The program takes data from the load_iris() function available in sklearn module.
The program then creates a decision tree based on the dataset for classification.
The user is then asked to enter the four parameters of his sample and a prediction about the species of the flower is printed to the user.

# Working on the support vector machine algorithm

The program takes data from the load_iris() function available in sklearn module.
The program then divides the dataset into training and testing samples in an 80:20 ratio randomly using train_test_learn() function available in sklearn module.
The training sample space is used to train the program and predictions are made on the testing sample space.
The Accuracy score is then calculated by comparing it with the correct results of the training dataset.
