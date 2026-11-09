# Machine Learning & AI Projects

A portfolio of machine learning, deep learning, data analysis, and generative AI projects implemented in Jupyter notebooks.

## Projects

| Project | Focus |
|---|---|
| [Client Project](./Client-Project/README.md) | ITSM data analysis using a MySQL data source |
| [Handwritten Digit Recognition](./Handwritten-Digit-Recognition/README.md) | Image classification and classifier comparison |
| [Flight Price Prediction](./Flight-Price-Prediction/README.md) | Regression models for flight fare estimation |
| [Customer Transaction Prediction](./Customer-Transaction-Prediction/README.md) | Imbalanced binary classification and threshold tuning |
| [Rainfall Time Series Forecasting](./New-AI-Projects.zip) | Monthly rainfall and maximum daily rainfall forecasting |
| [Indian Sign Language Recognition](./New-AI-Projects.zip) | MobileNetV2 transfer learning for ISL image recognition |
| [AI Technical Documentation Assistant](./New-AI-Projects.zip) | RAG chatbot with embeddings, ChromaDB, and Groq |

## Newly added project bundle

Download [New-AI-Projects.zip](./New-AI-Projects.zip) and extract it to access the three notebooks and their individual project READMEs:
- Rainfall Time Series Forecasting (PRAICP-1004)
- Indian Sign Language Recognition (PRAICP-1000)
- AI-Powered Technical Documentation & Support Assistant (RAG)

The notebooks have been cleaned for publication: execution outputs were cleared and machine-specific dataset paths were replaced with project-relative paths. The required datasets, documentation PDFs, and API credentials are not included.

## Existing repository projects

```
ML-PROJECTS/
├── Client-Project/
├── Handwritten-Digit-Recognition/
├── Flight-Price-Prediction/
├── Customer-Transaction-Prediction/
└── New-AI-Projects.zip
```

## Tools and libraries

Python, Jupyter Notebook, pandas, NumPy, Matplotlib, scikit-learn, TensorFlow/Keras, LangChain, Hugging Face, ChromaDB, and Groq.

## Running the notebooks

1. Clone this repository.
2. Extract `New-AI-Projects.zip` if you want to use one of the three newly added notebooks.
3. Install the libraries imported by the notebook you want to run.
4. Open the notebook in Jupyter or Google Colab.
5. Provide the required dataset, documentation PDFs, or API credentials. Datasets and credentials are not included unless explicitly documented.

## Notes

Notebook execution outputs were cleared before publishing. Local machine-specific paths were replaced with project-relative dataset paths where applicable. The Client Project notebook reads its database password from the `DB_PASSWORD` environment variable rather than embedding a password in source code. The RAG assistant expects `GROQ_API_KEY` to be configured in a local `.env` file; do not commit secrets.
