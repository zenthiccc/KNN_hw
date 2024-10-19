Heart Methody Castanares\
Joseph Duron Jr.


## Getting started
This code demonstrates how to use the K-Nearest Neighbors (KNN) algorithm for classification on a heart disease dataset. 
The dataset was extracted and edited from a larger dataset linked herein: https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction. For a more convenient and easier way, we deleted columns/features that were categorical in value 
and not numerical. This is so that we can compute the k-nearest neighbors through euclidean distances. 

This code uses the scikit-learn library to train a KNN classifier, test it with new instances, and evaluate how the classifier performs when the number of neighbors (k) is varied.

## Files attached:
* **heart-extracted.csv** - This dataset contains instances of heart disease-related data. It is split into:
    - **Features** (Columns 0-5): Various attributes representing heart health measurements.
    - **Labels** (Column 6): The target label indicating the presence or absence of heart disease. In this label, 1 indicated the person has a heart disease, while 0 indicates they do not.

* **heart-new-instance.csv** - This file contains a new instance of heart data, which will be used to test the model by predicting its label based on the KNN algorithm.

* **KNN_hw.ipynb** - The Python script to train, test, and evaluate the KNN classifier.

## Imports
* **pandas** - Used for reading and manipulating the CSV files.
* **numpy** - Utilized for numerical operations and transformations.
* **scikit-learn**:
    - **KNeighborsClassifier**: For building and evaluating the KNN model.
    - **StandardScaler and OneHotEncoder**: For data preprocessing (if necessary).
    - **confusion_matrix and accuracy_score**: For evaluating the model’s performance.





