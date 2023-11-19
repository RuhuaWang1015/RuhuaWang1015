# RAG QA with LangChain

This project leverages the LangChain library to enhance the Retrieval-Augmented Generation (RAG) model, focusing on improving document retrieval and question-answering capabilities. The experiments include optimizing chunk sizes, integrating MultiVector Retriever, and experimenting with Tree-of-Thought Prompting.

## Installation

Install the necessary dependencies for the project:

```bash
pip install -U langchain tiktoken openai chromadb langchainhub bs4 ragas
```

## Setup

Set up your OpenAI API key to access language models:

```python
import os
os.environ["OPENAI_API_KEY"] = "your_openai_api_key_here"
```

## Experiments

### Baseline RAG

Basic setup of the RAG model using LangChain, involving data loading, chunk splitting, vector store creation, retrieval, and answer generation.

### Improving RAG with MultiVector Retriever

Enhances retrieval by storing multiple vectors per document, incorporating smaller chunks, document summaries, and hypothetical questions embedding.

### Improving RAG with Tree-of-Thought Prompting

Explores the impact of Tree-of-Thought Prompting on the Baseline RAG + MultiVector model's performance.

## Results and Observations

The experiments are evaluated based on faithfulness, answer relevancy, and context relevancy scores. The findings are summarized in Markdown tables, providing insights into the impact of various techniques on the RAG model's performance.

## Conclusion

This project demonstrates the versatility of LangChain in enhancing RAG models and suggests potential areas for further experimentation and optimization.


Original Notebook: [RAG_QA.ipynb](https://colab.research.google.com/drive/1JAAMPOxjIXFcXe7YyuFjTX8kwZAWQtI1)


