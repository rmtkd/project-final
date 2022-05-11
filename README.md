# project-final
# Table of Contents
1. [Installation](https://github.com/rmtkd/project-1/blob/main/README.md#installation)
2. [Project Motivation](https://github.com/rmtkd/project-1/blob/main/README.md#project-motivation)
3. [File Descriptions](https://github.com/rmtkd/project-1/blob/main/README.md#file-descriptions)
4. [Results](https://github.com/rmtkd/project-1/blob/main/README.md#results)
5. [Licensing](https://github.com/rmtkd/project-1/blob/main/README.md#licensing)

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

- [ETL Pipeline Preparation.ipynb](https://github.com/rmtkd/project-2/blob/main/ETL%20Pipeline%20Preparation.ipynb) _ETL pipeline preparation_
- [ML Pipeline Preparation.ipynb](https://github.com/rmtkd/project-2/blob/main/ML%20Pipeline%20Preparation.ipynb) _ML pipeline preparation_


# Results

The ML pipeline had a better result using Logistic Regression, with a 77% accuracy and 64% f1-score. For this project, it is more important to have a high f1-score, as it represents the churn hits on an unbalanced base (few churns compared to the whole base)


# Licensing

Credits to Udacity for providing the templates for the project and the dataset used for the analysis and prediction.
