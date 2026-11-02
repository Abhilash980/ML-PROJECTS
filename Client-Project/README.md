# Client Project

A Jupyter notebook for working with client ITSM data from a MySQL database.

## Workflow
- Connect to the configured MySQL database.
- Inspect available tables.
- Load the `dataset_list` table into pandas.
- Continue the analysis in the notebook.

## Requirements
- Python
- pandas
- SQLAlchemy
- PyMySQL

## Configuration
Set the database password in an environment variable named `DB_PASSWORD` before running the connection cell. Do not commit credentials or private client data.

## Notebook
[Open Client_Project.ipynb](./Client_Project.ipynb)

The notebook's saved outputs were cleared before publication.