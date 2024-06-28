# Soil Pollution Prediction using Machine Learning
## Overview
This project aims to enhance soil pollution prediction by integrating expert-defined risk zones with machine learning models. The study evaluates the impact of expert knowledge on predictive performance through systematic data preparation, model structuring, evaluation, and interpretation. Using the Netherlands as a case study, this research investigates various stages and methods of incorporating expert-defined risk zones to improve soil pollution assessments.

## Notebooks
The project comprises four main Jupyter Notebooks, each focusing on different aspects of the study:

### EDA.ipynb:
- Purpose: Conduct exploratory data analysis (EDA) to understand the datasets and their distributions.
- Contents: Data loading, visualization of soil pollution data, and statistical summaries.

### Hyper parameter Selection.ipynb:
- Purpose: Perform hyperparameter selection for the machine learning models using grid search.
- Contents: Setup of machine learning models, execution of grid search for hyperparameter tuning, and selection of the best models.

### RandomForest.ipynb:
- Purpose: Run the main models for both datasets.
- Contents: Setup for machine learning models, execution of random forest models.

### Analysis model runs.ipynb:
- Purpose: Analyze the performance of different model runs, comparing models with and without expert knowledge integration.
- Contents: Model evaluation metrics, feature importance analysis, generalizability assessment, and learning curve analysis.

## Requirements
To run the notebooks, you need to install the required Python libraries. Below is a list of the main libraries used:
- pandas==1.3.3
- numpy==1.21.2
- scikit-learn==0.24.2
- matplotlib==3.4.3
- seaborn==0.11.2

## Installation
git clone https://github.com/JasperBraakman/Thesis_JasperBraakman.git

## Install dependencies:
pip install -r requirements.txt
