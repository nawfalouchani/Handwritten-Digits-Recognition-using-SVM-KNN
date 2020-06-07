# Handwritten-Digits-Recognition-using-SVM-KNN# Handwritten Digits Recognition using SVM & KNN
## Objective 
We will develop a model using Support Vector Machines and K-Nearest Neighbors which should correctly classify the handwritten digits from 0-9 based on the pixel values given as features. Thus, this is a 10-class classification problem.

## Data Description 
For this problem, we use the MNIST data which is a large database of handwritten digits. The 'pixel values' of each digit (image) comprise the features, and the actual number between 0-9 is the label.

Since each image is of 28 x 28 pixels, and each pixel forms a feature, there are 784 features.

## Project steps

We'll first explore the dataset a bit, prepare it (scale etc.) and then experiment with linear and non-linear SVMs with various hyperparameters, and finally experiment with KNN.

We'll divide the analysis into the following parts:

Data understanding and cleaning\
Data preparation for model building\
Building an SVM model - hyperparameter tuning, model evaluation etc.\
Building a KNN model - hyperparameter tuning, model evaluation etc.
