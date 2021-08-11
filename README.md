# Machine Learning Homework - Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, you will create machine learning models capable of classifying candidate exoplanets from the raw dataset.

---

### Preprocess the Data

- Preprocessed the dataset prior to fitting the model.
- Perform feature selection and remove unnecessary features.
- Used `MinMaxScaler` to scale the numerical data.
- Separated the data into training and testing data.
- Used pipeline for operational efficiency.

### Tune Model Parameters

- Used `GridSearch` to tune model parameters.
- Tune and compared two different classifiers Tree and SVM.

---

### Model selection and comparison

In terms of accuracy, SVM performs better than the Tree model

![Model_comparison.png](Images/Model_comparison.png)

Confusion Matrix comparison.

![SVM_Model.png](Images/SVM_Model.png)

![Tree_Model.png](Images/Tree_Model.png)

## CodeBase

- [Tree Model](starter_code/decession_tree.ipynb)
- [SVM Model](starter_code/SVM.ipynb)

## Models

- [Tree](starter_code/M1_Rajesh_Decision_Tree.sav)
- [SVM](starter_code/M2_Rajesh_SVM.sav)
