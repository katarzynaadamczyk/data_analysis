# Is it possible to predict diabetes?
Analysis of diabetes.csv (found on Kaggle https://www.kaggle.com/uciml/pima-indians-diabetes-database). 
Project made for workshop organized by Women In Technology Poland. Then developed more by myself.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Status](#status)
* [Inspiration](#inspiration)

## General info
Purpose of the project was to learn how to analyse the data and make my first analysis. The goal has been achieved. 
The project contains two analysis. Diabetes_1 is the first one and the result is satisfying. Diabetes_2 is the second one and it is based on the first. I wanted to compare what happens if I remove two columns with poor quality data from the dataset. 
Recently, I thought of some improvement of this project and that is why there is a file diabetes_3. It contains both approached from diabetes_1 and diabetes_2, consolidates them and add new features - comparison between not only two datasets preparations, but also between 3 different machine learning algorithms - KNN, decision trees and KMeans. 

## Technologies
* Jupyter Notebook - version 7.0.8 
* Python 3 - version 3.11.7
* Pandas - version 2.1.4
* NumPy - version 1.26.4
* Scikit-learn - version 1.2.2
* Matplotlib - version 3.8.0
* Seaborn - version 0.13.2

## Setup
You need to have Python 3 and Jupyter Notebook installed on your computer to see the analysis.

## Status
Notebook diabetes_1 - finished in 2021, my first attempt to make a data analysis and model testing project.
Notebook diabetes_2 - same as diabetes_1 but working on data with excluded nans. In conclusion there is a comparison to diabetes_1.
Notebook diabetes_3 - finished in 2025 - comparison between two datasets - nans replaced by medians and dataset excluding all nans. As well as comparison between KNN, decision tree and KMeans algorithms performance. 

## Inspiration
As I have a risk to suffer in the future from diabetes it is interesting topic for me. When I found the database on Kaggle, I immediately knew that I would like to analyse this dataset.
