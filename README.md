# Machine Learning & AI Projects

A portfolio of machine learning, deep learning, data analysis, and generative AI projects implemented in Jupyter notebooks.

## Projects

| Project | Focus |
|---|---|
| [Client Project](./Client-Project/README.md) | ITSM data analysis using a MySQL data source |
| [Handwritten Digit Recognition](./Handwritten-Digit-Recognition/README.md) | Image classification and classifier comparison |
| [Flight Price Prediction](./Flight-Price-Prediction/README.md) | Regression models for flight fare estimation |
| [Customer Transaction Prediction](./Customer-Transaction-Prediction/README.md) | Imbalanced binary classification and threshold tuning |
| [Rainfall Time Series Forecasting](./Rainfall-Time-Series-Forecasting.zip) | Monthly rainfall and maximum daily rainfall forecasting |
| [Indian Sign Language Recognition](./Indian-Sign-Language-Recognition.zip) | MobileNetV2 transfer learning for ISL image recognition |
| [AI Technical Documentation Assistant](./AI-Technical-Documentation-Assistant.zip) | RAG chatbot with embeddings, ChromaDB, and Groq |

## Newly added projects

Download and extract each project archive to access its Jupyter notebook and project README:

- [Rainfall Time Series Forecasting (PRAICP-1004)](./Rainfall-Time-Series-Forecasting.zip)
- [Indian Sign Language Recognition (PRAICP-1000)](./Indian-Sign-Language-Recognition.zip)
- [AI-Powered Technical Documentation & Support Assistant](./AI-Technical-Documentation-Assistant.zip)

The notebook copies were cleaned for publication: execution outputs were cleared, and machine-specific dataset paths were replaced with project-relative paths. The required datasets, documentation PDFs, and API credentials are not included.

## Existing repository projects

```
ML-PROJECTS/
├── Client-Project/
├── Handwritten-Digit-Recognition/
├── Flight-Price-Prediction/
├── Customer-Transaction-Prediction/
├── Rainfall-Time-Series-Forecasting.zip
├── Indian-Sign-Language-Recognition.zip
└── AI-Technical-Documentation-Assistant.zip
```

## Tools and libraries

Python, Jupyter Notebook, pandas, NumPy, Matplotlib, scikit-learn, TensorFlow/Keras, LangChain, Hugging Face, ChromaDB, and Groq.

## Running the notebooks

1. Clone this repository.
2. Download and extract the project archive you want to run.
3. Install the libraries imported by that notebook.
4. Open the notebook in Jupyter or Google Colab.
5. Provide the required dataset, documentation PDFs, or API credentials. Datasets and credentials are not included unless explicitly documented.

## Notes

Notebook execution outputs were cleared before publishing. Local machine-specific paths were replaced with project-relative dataset paths where applicable. The Client Project notebook reads its database password from the `DB_PASSWORD` environment variable rather than embedding a password in source code. The RAG assistant expects `GROQ_API_KEY` to be configured in a local `.env` file; do not commit secrets.
