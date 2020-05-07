# TRIAD Data Scientist Challenge

The repository contains the analysis and results from the TRIAD Data Scientist challenge project. 

## Goal 

The goal of the project is to develop a model to predict whether a student will pass an important test. The data set includes demographic information about each student, including sex, age, language and country, as well as information about studying habits and participation in a Dojo class and test prep class. 

## Part 1 - Analysis

Part one of and project analyses the impact of the demographic features on whether a student passes the test. Based on the analysis, only the age and sex of the student affects the probability that the student will pass the test. The analysis of demographic features can be found in the file analysis.ipynb. Selecting the file opens a static version of a Jupyter Notebook with the code and output for each step of the analysis.  

## Part 2 - Model Selection

Part two of the project involves selecting the best model to predict whether a student passes the test using the features available in the dataset. A variety of classification models were fit to the data. Cross validation using mean accuracy as the selection critera selected a random forest as the best model for prediction. The selection of the best model can be found in the file model_selection.ipynvb. Selecting the file opens a static version of a Jupyter Notebook with the code and output for each step of the analysis. 

## Part 3 - Reporting

Part three of the project involves reporting the results of the model and developing a simple piece of software that will allow an external user to run and verify the accuracy of the selected model. The model can be run by clicking on the Binder badge below. After clicking the badge, a new window will open in the browser with a Jupyter Notebook that can be run on the selected model. Note that it may take a few minutes for the Jupyter Notebook to open. The model can be run by selecting `Cell > Run All` from the Menu.  

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/akhullar001/triad-challenge/master?filepath=model_run.ipynb)


