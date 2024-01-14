# Introductory Machine Learning Challenge

## Overview

Check out the ml challenge file, and ignore the other two files. The ML project was an introductory exercise in machine learning, focusing on training, testing, optimizing, and analyzing the performance of a classification model using a methodology of my choice. The dataset used for this challenge is the randomly generated moons dataset.

## Implementation

In this notebook, I utilized Python packages such as Pandas, NumPy, Matplotlib, and scikit-learn to create models to fit the 'make_moons' dataset provided by scikit-learn.

### Dataset

The dataset is generated using the 'make_moons' function, which creates two interleaving half-moons. It consists of 500 samples, with 50 samples in one class and 450 samples in another. We've introduced noise to make the task more challenging.

### Workflow

1. **Training**: I split the dataset into training and testing sets using a test size of 20%. I train two classification models: KNeighborsClassifier and RandomForestClassifier.

2. **Testing / Optimization**: I visualized the decision boundaries of both models and examined their performance.

3. **Performance Analysis**: I calculated and displayed the training accuracy for both models and provide classification reports for each model on the testing data. Both models did pretty well!

