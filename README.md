# Breast Cancer-prediction
The goal is to classify whether the breast cancer is benign or malignant and predict the recurrence and non-recurrence of malignant cases after a certain period.

# Introduction
The aim of this notebook is to understand the process of EDA and Data-preparation, selection of features, implementing machine learning tools. Later, will comparing and improving the best models.

# About Dataset
Dataset: Breast Cancer Wisconsin (Diagnostic) Data Set <a href='https://www.kaggle.com/uciml/breast-cancer-wisconsin-data'>here</a>

The features from the data set describe characteristics of the cell nuclei and are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. As described in UCI Machine Learning Repository, the attribute informations are: The dataset contains 569 samples of malignant and benign tumor cells.

The first two columns in the dataset store the unique ID numbers of the samples and the corresponding diagnosis (M=malignant, B=benign), respectively.
The columns 3-32 contain 30 real-value features that have been computed from digitized images of the cell nuclei, which can be used to build a model to predict whether a tumor is benign or malignant.
The mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.
