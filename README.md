# Cholesterol Prediction Without a Clinical Test
### Authors/Contributors: [Shimona Narang](https://github.com/shimonanarang), Zehui Lin, Esmond Tang, [Dylan Mendonca](https://github.com/mdylan2)


## Description
This repository contains the the notebooks and presentation for a final project for CHE1147 (Data Mining in Engineering) taken at the University of Toronto in Winter 2020. The goal of the project was to assess whether a person might have a high or low level of cholesterol by using features that are either (a) known beforehand (age, gender, etc.) or (b) can easily be measured at home (weight, arm thickness, etc.). The motivation behind this project was to create a model that could be deployed on an app as a survey to alleviate the financial burden of having to take a cholesterol test (this survey could act as a precursor to taking a lab test).

## Files
Here's a list of files in the directory:


The repository contains the following files:
- `Cholesterol Prediction.ipynb`: Contains all the code and models used
- `Business Model Presentation.pdf`: Contains the slide deck for my project presentation

## Dataset

The project used data taken from [National Health and Nutrition Examination Survey](https://www.kaggle.com/cdc/national-health-and-nutrition-examination-survey) (2014). Features are extracted from datasets related to diet, demographics, examinations (height, weight, BMI, etc.) and a questionnaire (questions about exercise/eating habits, background, etc.). Supervised Machine Learning Techniques are used to classify cholesterol as high or normal.


## Workflow
The project is broken has been broken down into various sections:
1. __**Feature Selection:**__ Selecting salient features based on personal discretion
2. __**Data Pre-processing:**__ Imputing missing values in the dataset
3. __**Exploratory Data Analysis (EDA):**__ Exploring the data through visualizations and PCA
4. __**Model Development and Fine Tuning:**__ Both linear and non-linear approaches (L1/L2 Logistic Regression, K-Nearest Neighbors, XG Boost, Random Forest, SVMs)
5. __**Designing for Deployment:**__ Using feature importance to extract the 10 most important features, using those results to build final models. These 10 features could be implemented in an app

## Questions/Contributions
- Myself and the rest of the team are not actively pursuing this project at the moment
- If you'd like to chat about this project, please reach out to me or any of my team members on GitHub
