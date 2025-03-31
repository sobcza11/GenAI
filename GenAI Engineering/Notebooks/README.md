# Notebooks

This directory contains a single Jupyter Notebook demonstrating how to build a retrieval-augmented question-answering system using IBM Watsonx and LangChain.

## Notebook Summary

**🔍 `pdf_loader.ipynb`**  
This notebook walks through the end-to-end pipeline of:
- Ingesting a research paper PDF
- Splitting it into manageable text chunks
- Embedding those chunks with Watsonx
- Indexing them with ChromaDB
- Using a Watsonx LLM to answer natural language queries over the document

Ideal for those exploring Retrieval-Augmented Generation (RAG) or integrating GenAI into document-based workflows.

## Disclaimer
This notebook was created for educational and portfolio purposes. It does not represent a production-ready implementation and is not affiliated with IBM. All API keys and credentials should be handled securely using environment variables or tools like getpass.

