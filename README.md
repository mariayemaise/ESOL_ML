# Estimated Solubility Prediction Project
## Introduction
Solubility is a crucial property in drug discovery and material science, and accurate prediction of solubility can save significant time and resources. This project applies several machine learning models to predict the solubility of molecules based on their physical and chemical descriptors.

## Data
The dataset used in this project is a publicly available dataset from the Delaney Solubility Dataset. It contains the following molecular descriptors:

MolLogP: Molecular LogP (partition coefficient)

MolWt: Molecular weight

NumRotatableBonds: Number of rotatable bonds

AromaticProportion: Proportion of aromatic atoms

logS: Solubility (target variable)

## Models 
The following machine learning models are used in this project:

1. Linear Regression
   
2. Decision Tree Regressor
   
3. Random Forest Regressor

## Libraries

pandas

numpy

matplotlib

scikit-learn

## Steps

1. Data loading and preprocessing
   
2. Training various machine learning models
   
3. Evaluating model performance using metrics such as Mean Squared Error (MSE) and R² score

4. Visualization

## Result

The Linear Regression model has the lowest Test MSE and the highest Test R² score, making it the most accurate model for predicting solubility in this project. 
