# ECS171FinalProject: Predicting Combat Outcomes between Pokemon using Various Machine Learning Models

## Pokémon Battle Outcome Prediction
This project applies machine learning techniques to predict the winner of a Pokémon battle using combat and attribute data. We compare multiple classifiers, including Logistic Regression, Multilayer Perceptron (MLP), and Support Vector Classifier (SVC), to evaluate performance and identify the most accurate model.

## How to Run Notebooks
If needed look at requirements.txt to install dependencies

## To Download Pokemon Datasets
Navigate to https://www.kaggle.com/datasets/tuannguyenvananh/pokemon-dataset-with-team-combat?resource=download and download 'pokemon.csv' and 'combats.csv'

## Why are the datasets not in the repo?
- GitHub has file size limits: Max ~100MB per file
- Large datasets can bloat the repo and slow down cloning, pushing, and fetching
- Datasets are usually static inputs, not source code so it doesn't need version control
- Git tracks changes line by line — which doesn’t make sense for large .csv files
- Keeps the repo lightweight and source-code–focused which improves readability
- Instead download and store datasets locally and makesure they are included in .gitignore so that they are not pushed

## Team Members
- Surinder - Research Paper and Demo
- Wenqian - Logistic Regression Model
- Helen - MLP model
- Yasmin and Jeanette - SVC model