# Machine-Learning-Project1
This project implements a comparison of several machine learning models to classify data. It uses the following classifiers:

(i) Linear Discriminant Analysis (LDA)

(ii) Decision Tree Classifier

(iii) k-Nearest Neighbors (k-NN)

(iv) Support Vector Machine (SVM)

This project includes data preprocessing, dimensionality reduction using PCA, model training and performance evaluation using confusion matrices and error rate visualization.

The code requires the following Python libraries:

(i) pandas: For data manipulation with DataFrames

(ii) numpy: For numerical operations, like array manipulation

(iii) scikit-learn: For various machine learning models and metrics

(iv) matplotlib: For plotting results and visualizations

# Classifiers and PCA Implementation:

1. Linear Discriminant Analysis (LDA) is applied to the training data to create a linear decision boundary that maximizes class separability. The model is trained and evaluated based on error rates and confusion matrices.

2. Decision Tree Classifier is trained using the training data. The model's performance is evaluated on the test data with an error rate calculation and confusion matrix.

3. k-Nearest Neighbor (k-NN) is applied for different values of k (1,3,5,10). The modle is evaluated for each value of k to determine which provides the best performance.

4. Support Vector Machine (SVM) classifier is used to find an optimal separating hyperplane. Model performance is evaluated on the test data.

5. Dimensionality Reduction with PCA is used to reduce the feature dimensions for the classifiers. The classifiers are retrained on reduced datasets (n_components values of 5,10,15) to analyze performance changes due to dimensionality reduction.

# How to run the code:

Download the Training and Testing data and place them inthe smae directory as the code.

We utilized Google Colab to run the project.
