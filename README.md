# Chat with Multiple PDFs 

RAG Implementation using Langchain, FAISS, Google Gemini Pro-1.5

## Setup

This project is initialized using `pdm`. To learn more about `pdm` please refer to [pdm documentation](https://pdm-project.org/en/latest/)

- Install `pdm` using the command: `pip install pdm`
- Then initialize a blank project using the command `pdm init`. This will provide a bunch of prompts to fill, after which a template is created for you.


## Requirements

- You will have to create a `.env` file in the root of your repo and include the following

`GOOGLE_API_KEY = <YOUR_API_KEY>`

## Executing the project

- After installing the required packages, run `pdm run streamlit run app.py` to run the streamlit app.

## References

- [Google API Docs](https://ai.google.dev/gemini-api/docs/document-processing?lang=python)