# project-final
# Table of Contents
1. [Installation](https://github.com/rmtkd/project-final#installation)
2. [Project Motivation](https://github.com/rmtkd/project-final#project-motivation)
3. [File Descriptions](https://github.com/rmtkd/project-final#file-descriptions)
4. [Results](https://github.com/rmtkd/project-final#results)
5. [Licensing](https://github.com/rmtkd/project-final#licensing)

# Installation

The project successfully ran in the Udacity workspace with python 3.6.3.

# Project Motivation

In this project, we will explore a dataset of user events within a music streaming platform (like Spotify, Deezer, and Amazon Music) and generate a model to predict churn, which is a big and common problem for SaaS (Software as a Service) companies. The full dataset is 12GB but for this project, a smaller dataset was used to perform the analysis and training of the model.

For this project, we will use Spark to manipulate large datasets through Spark Dataframes and use the machine learning API with Spark ML to build and tune the models, all of this integrated with the skills obtained in the Data Scientist Nanodegree course. Below are the steps that were taken on the project:
1. Load and Clean
2. Exploratory Analysis
3. Feature Engineering
4. Modeling

# File Descriptions

- [udacity_sparkfy.ipynb](https://github.com/rmtkd/project-final/blob/main/udacity_sparkfy.ipynb) _Sparkfy project notebook_


# Results

The ML pipeline had a better result using Logistic Regression, with a 81,4% accuracy and 64,9% f1-score for the test set. For this project, it is more important to have a high f1-score, as it represents the churn hits on an unbalanced base (few churns compared to the whole base).
The model could be improved with the addition of new features, such as:
- days on the platform after user creation
- average daily login after user creation

As we don't have exactly the information on user creation cohorts, we were not able to calculate these features, which might be useful in the model.



# Licensing

Credits to Udacity for providing the templates for the project and the dataset used for the analysis and prediction.
