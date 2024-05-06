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

## Notebooks

### Part 1: langchain-intro.ipynb

This notebook provides a gentle introduction to Langchain's capabilities, including initializing a model, changing inference parameters, using templates, chains, and loading documents.

### Part 2: langchain-summarization.ipynb

This notebook focuses on summarization of large amounts of text, which involves more intricate processes.

## Instructions for Workshop Participants

- If attending a workshop, instructors will provide the URL for JupyterHub.
- Sign up to set your password, then log in.
- Follow the instructions provided in the respective notebooks.
- If needed, refer to step 7 above to acquire values for environment variables.

## Support

For any issues or queries, feel free to contact [Baren Baruna Harahap](https://www.linkedin.com/in/barenbarunaharahap/) on LinkedIn or via email at barenbarunaharahap@gmail.com.
