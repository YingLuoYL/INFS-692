# INFS-692
The project implemented three model using R markdown on the dataset 'radiomics.csv' which contains 197 rows and 431 columns, with 'Failure.binary' as the binary labels to predict:
1. Model 1: Ensemble classification model
2. Model 2: Network-based classification model
3. Model 3: Unsupervised learning models (K-Means, Hierarchical, and Model Based)

Setup packages includes:
1. Model 1: caret, rsample, recipes, h2o
2. Model 2: keras, caret, rsample, recipes
3. Model 3: dplyr, ggplot, stringr, gridExtra; and modeling packages: tidyverse, cluster, factoextra

Specific data preprocessing:
1.	Model 1: standardization for features 
2.	Model 2: one hot encoding for the labels
3.	Model 3: standardization for features and removing the label from the original dataset for unsupervised learning
