# Assignment 1 - Logistic Regression

Authors: 
- Max Ardito - maxwell.ardito@mail.mcgill.ca
- Edwin Meriaux - edwin.meriaux@mail.mcgill.ca
- Ohood Sabr - ohood.sabr@mail.mcgill.ca

## How To Run

The provided notebook `logistic-regression.ipynb` can be run using Google Collab and
contains markdown and annotations that will guide you through reproducing the results 
of the assignment.

Note that when reaching the *File Upload* section, running the cell will prompt you to 
upload a `.csv` file. The name of the `.csv` file which you decide to upload MUST match 
the name of the file provided in the `io.BytesIO()` function.

## Table of contents

The notebook is organized in the following sections

1. __Regression Class__: Class that implements a binary logistic regression with
additional support for L1 and L2 regularization
2. __Evaluation Class__: Class that provides various tools for analyzing performance
metrics, including accuracy rating and confusion matrix generation.
3. __K-Fold Cross Validation Class__: Class that performs K-Fold cross validation
on different variations on the Regression class.
4. __File Upload__: Upload your air quality or liver disease csv files here
5. __Dataset Analysis__: Some plots that show histograms of the features of the two datasets
6. __Main Program: Base Model__: The base logistic regression model run on 10-fold
cross validation with no additional features
7. __Main Program: Normalized Model__: The optimal model discussed in the report: 
a variation on the base model using a normalization step implemented on the dataset 
before training, a feature reduction, a feature expansion, and 11 different PCA sets 
cross-validated with each other using 10-fold. The optimal number of principal components depends on the dataset being used.
8. __Main Program: Regularized Model__: The optimal model from above with an additional 
L1 and L2 regularization step.
