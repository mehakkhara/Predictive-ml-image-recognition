# Predictive machine learning for image recognition and classification

The project focuses on an image recognition problem. It constructs a variety of machine learning models with the goal of generating predictive classifications.

## Introduction
This project is about image recognition using data from MNIST Fashion Database. Training data (60,000 rows) and testing data (10,000 rows) are all composed of information about 49 pixels of clothing pictures along with their labels. Our team trained 10 different machine learning models to generate predictive classifications of testing sets. We built these 10 models using 9 sample training sets with sizes 500, 1000 and 2000, and each of the size is randomly sampled from the whole training set for three times.  

Among the 10 models we built, 8 machine learning techniques are applied. Their details are shown as following.  

| Model | Technique | Model | Technique |
|------|------|------|------|
|1|Neural Networks|6|K Nearest Neighbours with K=5|
|2|Multinomial Logistic Regression|7|Random Forest- Ntree = 500|
|3|Ridge Regression|8|Random Forest - Ntree = 1000|
|4|LASSO Regression|9|Classification tree|
|5|K Nearest Neighbours with K=10|10|Ensemble model|

The purpose is to get as accurate predictive classifications of testing sets as possible, while limiting the size of training rows as well as computing time. We constructed points that reflect these three features of our models, and the goal is to obtain lower points - lower error, less time and smaller size.  

The code file also provides a brief overview and description of each of the models used
