# RAG with Langchain

## Ingestion Pipeline

### 01. Document structure and Data Parsing

- Setup a project with requirements below:

```
langchain
langchain-core
langchain-community
pypdf
pymupdf
ipykernel
```

- Generate files with python code
- Documents have important values: page_content, metadata
- Load text files with TextLoader
- Load directory as a whole with DirectoryLoader
- Load PDF files with PyMuPDFLoader, PyPDFLoader

### 02. Chunking

- Read documents inside a directory and load them into document structures using DocumentLoader, PyPDFLoader, PyMuPDFLoader
- Once loading documents into structures, Split them into chunks with chunk_size, chunk_overlap, separators, length_functions, etc.
