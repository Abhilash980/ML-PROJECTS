# Customer Transaction Prediction

A binary classification notebook that predicts whether a customer will make a transaction.

## Dataset
The notebook was developed with a dataset containing 200,000 rows and 200 numeric input features, plus an ID and binary target. The target classes are imbalanced.

## Workflow
- Load and inspect the dataset.
- Check missing values, duplicates, and class distribution.
- Split data into training and validation sets.
- Compare Logistic Regression, Decision Tree, Random Forest, and HistGradientBoosting.
- Evaluate precision, recall, F1-score, ROC-AUC, and the confusion matrix.
- Tune the classification threshold.

## Recorded final evaluation
The notebook work recorded a threshold of 0.65 and an F1-score of 0.5389, with ROC-AUC of 0.8858. Results depend on the supplied dataset and split.

## Tools
Python, pandas, NumPy, Matplotlib, and scikit-learn.

## Notebook
[Open Customer_Transaction_Prediction.ipynb](./Customer_Transaction_Prediction.ipynb)

The dataset is not included. Update the dataset path or upload the required data before running the notebook. Saved outputs were cleared before publication.