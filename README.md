# Machine Learning Projects

A portfolio of machine learning and data analysis projects, implemented in Jupyter notebooks.

## Projects

| Project | Focus |
|---|---|
| [Client Project](./Client-Project/README.md) | ITSM data analysis using a MySQL data source |
| [Handwritten Digit Recognition](./Handwritten-Digit-Recognition/README.md) | Image classification and classifier comparison |
| [Flight Price Prediction](./Flight-Price-Prediction/README.md) | Regression models for flight fare estimation |
| [Customer Transaction Prediction](./Customer-Transaction-Prediction/README.md) | Imbalanced binary classification and threshold tuning |

## Repository structure

```
ML-PROJECTS/
├── Client-Project/
├── Handwritten-Digit-Recognition/
├── Flight-Price-Prediction/
└── Customer-Transaction-Prediction/
```

## Tools and libraries

Python, Jupyter Notebook, pandas, NumPy, Matplotlib, and scikit-learn. Individual notebooks document their own workflow and dependencies.

## Running the notebooks

1. Clone this repository.
2. Install the libraries imported by the notebook you want to run.
3. Open the notebook in Jupyter or Google Colab.
4. Provide the required dataset or database access. Datasets and credentials are not included in this repository unless explicitly documented.

## Notes

Notebook execution outputs were cleared before publishing. The Client Project notebook was adjusted to read its database password from the `DB_PASSWORD` environment variable rather than embedding a password in source code.
