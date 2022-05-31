# MSCA 31009 - Mushroom Poisonousness Detection Project
This repository is used to hold any files related to the MSCA 31009 final project.

## Description
The purpose of this project is to analyze features of mushrooms to predict if the mushroom is edible.
* This project utilizes the Mushroom dataset from Kaggle. The data includes data about the appearance, smell, population, and habitat of various mushroomsm, and marked to be edible or not.
* The analysis will include feature selection, PCA and MCA, supervised and unsupervised machine learning, and a nerual network.

## Data
* The data was downloaded from [Kaggle](https://www.kaggle.com/datasets/uciml/mushroom-classification).     
* The data is in CSV format, has 8124 columns and 23 rows.

## Methodology and Tools
* Dimensional Reduction
  * MCA
  * PCA
* Traditional Supervised ML model
  * Logistic Regression
  * SGD Classifier
  * Support Vector Classification
* Traditional Unsupervised Learning
  * K-Modes (Clustering)
* Deep Learning
  * Neural Network
* Tools
  * Cloud Platform: Google Collaboratory
  * Data Storage: Google Drive 

## Files
* mushrooms.csv
  * Contains the original data downloaded from Kaggle. 
* Mushroom_base.ipynb
  * Data cleanring, visulization and EDA in Python. Baseline models without any techniques applied.
* Mushroom_Feature_Engineering.ipynb
  * Feature engineering process and re-run models afterwards. 
* data_feature_engineering.csv
  * Feature engineering output stored in a CSV file. 
* Mushroom_PCA_MCA.ipynb
  * Two dimentional reduction techniques applied, re-run and re-evaluate models afterwards. 
* Mushroom_NN.ipynb
  * Deep learning: neural network applied to the mushroom data. 
