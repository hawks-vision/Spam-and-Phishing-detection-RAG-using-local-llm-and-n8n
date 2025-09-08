# Spam-and-Phishing-detection-RAG-using-local-llm-and-n8n
Looking forward to creating a RAG for detecting targeted phishing mails for any organisation

***

# Phishing_RAG

This repository contains the **Phishing_RAG** n8n workflow and dataset, designed to automate phishing detection using Retrieval-Augmented Generation (RAG), vector stores, and AI-powered document analysis.

## Features

- **Document Embedding**: Converts uploaded documents into vector embeddings for semantic search and phishing detection.
- **Vector Store Integration**: Stores embeddings using a simple vector store for efficient retrieval.
- **AI-Powered Phishing Identification**: Uses an Ollama LLM and embedding models for analyzing and classifying potential phishing documents or messages.
- **Text Splitting & Preprocessing**: Automatically splits and processes documents into manageable chunks for better semantic matching.
- **End-to-End Automation**: Built entirely in [n8n.io](https://n8n.io), the workflow can be executed with a single click.
- **Customizable Nodes**: Modular steps including embedding, document loading, phishing detection, and vector store management for easy extension.

## Usage

1. **Import the Workflow**  
   - Open your local n8n instance.
   - Import the workflow file (`.json`) from this repository.

2. **Configure Embedding Model**  
   - Set your embedding model (currently uses Ollama integration).
   - Adjust vector store parameters as needed.

3. **Execute Workflow**  
   - Upload or submit a document/message.
   - The workflow will process input, generate embeddings, and attempt phishing identification.

## Nodes Overview

- **Embedding Node**: Generates vector embeddings.
- **Vector Store Creation Node**: Saves document vectors.
- **Phishing Identification Node**: Performs phishing detection using a chat model.
- **Text Splitter**: Pre-processes documents.
- **Dataset Submission & Logging**: Tracks submissions for review and evaluation.

## Requirements

- n8n (self-hosted/local or cloud)
- Ollama embedding models (adjust as needed for your infra)
- (Optional) Access to custom vector store plugins

## Future Improvements

- Integrate advanced phishing detection models.
- Add user authentication and access management.
- Support for more document formats.
- Dashboard for analytics and monitoring.

## Contributing

Feel free to fork, improve, and submit pull requests for enhancements!  
Issues, bugs, or feature requests? Open an issue on this repo.

## License

[MIT License](LICENSE)

***
