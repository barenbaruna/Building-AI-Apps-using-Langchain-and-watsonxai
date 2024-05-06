# Lab 105: Building AI apps with Langchain and watsonx.ai

## About

Langchain is a framework designed to facilitate the development of complex AI-powered applications. It supports various language models and provides tools to manage intricate logic effectively, such as sending system and human instructions, dynamic prompts using templates, chaining, output parsing, and more.

Langchain Python module: [Langchain PyPI](https://pypi.org/project/langchain/)
Supports Python and Javascript / Typescript

In this lab, we utilize Langchain in conjunction with watsonx.ai and the IBM Watson Machine Learning SDK, specifically leveraging the SDK's Langchain extension. Langchain already supports over 70 LLMs, and it offers custom LLM functionality for additional support. 

## Prerequisites

Ensure Python >= 3.11 is installed. (Run `python3 --version`)

### Setup Instructions

1. Navigate to a suitable folder on your machine in the terminal.
2. Create a Virtual Environment: `python3 -m venv langchain`
3. Activate the environment:
    - MacOS + Linux: `source langchain/bin/activate`
    - Windows:
        - Command Prompt: `langchain\Scripts\activate.bat`
        - PowerShell: `langchain\Scripts\Activate.ps1`
4. Install requirements: `python3 -m pip install -r requirements.txt`
5. Download `env-test.ipynb` and start Jupyter Notebook with `jupyter notebook`.
6. Run `env-test.ipynb` to ensure there are no errors with your environment or dependencies.
7. Create an `.env` file in your folder based on `.env.example`.
8. Fill out the values in the `.env` file as per the instructions provided.

### Additional Notes

- ChromaDB may require C++ build tools. Follow platform-specific instructions if installation issues arise.

## Usage

To run these notebooks locally, make sure you have the necessary dependencies installed.

## Notebooks

### Introduction to Langchain (langchain-intro.ipynb)

This notebook serves as a comprehensive introduction to using Langchain programmatically with WatsonX.ai models. It covers:

- **Dependencies Setup**: Importing necessary libraries and setting up environment variables.
- **Initializing WatsonX Models**: Instantiating LLM models for text generation tasks.
- **Prompt Templates & Chains**: Implementing prompt templates and chains for text generation, including basic and sequential chains.
- **Loading & Processing Documents**: Demonstrating document loading and processing for NLP tasks, including PDF extraction.

### Document Summarization with Langchain (langchain-summarization.ipynb)

In this notebook, we delve into advanced document summarization tasks using Langchain. It includes:

- **Summarization Techniques**: Exploring techniques for summarizing lengthy documents via chunking and recursive strategies.
- **Dependencies Setup**: Setting up the environment and importing necessary dependencies for document summarization.
- **Document Summarization**: Performing document summarization using Langchain, covering 'stuff' and 'map reduce' approaches.
- **Advanced Summarization Techniques**: Implementing advanced summarization techniques with prompt templates and chains.
- **Efficient Summarization of Multiple Documents**: Showcasing efficient summarization of multiple documents using map-reduce strategies.

**Complete the lab by following the instructions in the notebook.**

## Support

For any issues or queries, feel free to contact [Baren Baruna Harahap](https://www.linkedin.com/in/barenbarunaharahap/) on LinkedIn or via email at barenbarunaharahap@gmail.com.
