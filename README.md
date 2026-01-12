# Structured Data Classification

## Project Overview
This repository contains a group coursework project focusing on supervised classification using structured tabular data.

The task is to classify rice grain varieties based on morphological features, with an emphasis on comparing single classifiers and ensemble methods under a consistent evaluation framework.

## Dataset
- Modified UCI Rice dataset
- 1,400 samples with 7 numerical features
- Binary classification task (Cammeo vs Osmancik rice varieties)

## Methods
The project evaluates multiple classification approaches, including:
- Decision Tree
- Bagging (Decision Tree base learners)
- AdaBoost (decision stumps)
- Gradient Boosting

All models were evaluated using stratified 10-fold cross-validation to ensure fair comparison and robustness.

## My Contribution
This was a group coursework project.

My primary contributions focused on **ensemble-based classification models**, including:
- Implementing and evaluating Decision Tree classifiers
- Building Bagging ensembles to reduce variance
- Implementing AdaBoost and Gradient Boosting models
- Analysing and interpreting model performance using cross-validation metrics
- Contributing to the comparison between single models and ensemble methods

## Results
Ensemble methods demonstrated improved robustness and predictive performance compared to single decision trees. Bagging and Gradient Boosting achieved strong cross-validation accuracy, highlighting the benefits of ensemble learning for structured datasets.

## Tools & Technologies
Python, NumPy, Pandas, scikit-learn, Jupyter Notebook

## Notes
This repository reflects a coursework-based analytical project.
It contains final code and reports rather than a production-level pipeline.
