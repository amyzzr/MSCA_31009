# MSCA 31009 - Mushroom Poisonousness Detection Project
This repository is used to hold any files related to the MSCA 31009 final project.

|Team Member|
|:---:|
|[**Amy Zhang**](https://github.com/amyzzr)|
|[**Chang Gao**](https://github.com/ZoeeeG)|
|[**Jason Lee**](https://github.com/jasonwlee1219)|
|[**Yifan Jiang**](https://github.com/yifanj72)|

|Team Member|
|:---:|
|[**Amy Zhang**](https://github.com/amyzzr)|[**Chang Gao**](https://github.com/ZoeeeG)|[**Jason Lee**](https://github.com/jasonwlee1219)|[**Yifan Jiang**](https://github.com/yifanj72)|


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
* Traditional Supervised ML Model
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

## Findings and Conclusions
* Given our goal of maximizing recall, SVC was the best model because it returns the highest recall after feature engineering. It’s performance after PCA and MCA is also more stable compared to other models.
* Odor is the most important feature. While in the wild, you'll have a better chance picking an edible mushroom if it doesn’t have any odor.
* Neural Network is too complicated in this application.
* Feature importance ranking for different models is more diverse after feature engineering. We start to see differences in the ranking from different models.
* Dimensional reduction helps to resolve the highly correlated variables in selective cases. For decision tree and random forest, model performance is improved after dimensional reduction.

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
