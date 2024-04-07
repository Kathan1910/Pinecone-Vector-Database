# Chat with Your PDFs Using Pinecone and OpenAI


## Introduction

This project introduces a Conversational PDF Interface that allows users to interact with the content of PDF documents in a conversational manner. By utilizing the `langchain` library for natural language processing and Pinecone as the vector database (VB) for efficient indexing and retrieval, it enables querying PDF documents dynamically.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Dependencies](#dependencies)
- [Configuration](#configuration)
- [Documentation](#documentation)
- [Examples](#examples)
- [Troubleshooting](#troubleshooting)


## Installation

To set up your environment to run the project, follow these steps:



```bash
pip install -r requirements.txt
```


This will install all necessary dependencies, including `langchain` and `python-dotenv`, as well as any additional libraries required for interacting with Pinecone.

## Usage

To use this interface, perform the following steps:

1. Ensure all dependencies are installed.
2. Configure your Pinecone API key by setting it in an `.env` file or your environment variables.
3. Run the Jupyter Notebook to index your PDF documents into Pinecone.
4. Interact with the notebook's conversational interface to query the PDF content.

## Features

- Conversational interface for querying PDF documents.
- Integration with Pinecone for efficient document indexing and retrieval.
- Use of `langchain` for natural language understanding and processing.

## Dependencies

- OpenAI Key
- langchain
- python-dotenv
- Additional libraries for interacting with Pinecone and processing PDFs.

## Configuration

Place your OPENAI API key in a `.env` file using the following format:

```bash
OPENAI_API_KEY=your_api_key_here
```

This ensures secure access to Pinecone services for indexing and querying operations.

## Documentation

The primary documentation for this project is contained within the Jupyter Notebook, providing step-by-step instructions for setting up the conversational interface, indexing PDFs, and querying them.

## Examples

The notebook includes examples of how to process PDF documents, index their content into Pinecone, and interact with the indexed data through a conversational interface.

## Troubleshooting

If you encounter issues with Pinecone connectivity or indexing, ensure your API key is correctly set and that you have an active internet connection. For problems related to `langchain` or PDF processing, verify that all dependencies are correctly installed and up to date.


