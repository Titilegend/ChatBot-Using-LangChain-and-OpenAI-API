# ChatBot-Using-LangChain-and-OpenAI-API


A minimal chatbot built with **LangChain** and the **OpenAI API**.  
It accepts user questions and returns answers using a LangChain chain (Prompt → LLM → Output Parser).  
The notebook also includes tests with 5 sample queries and an interactive chat loop.

## Features
- LangChain chain (LCEL): `prompt | llm | output_parser`
- 5 sample test queries
- Interactive chatbot

## Tech Stack
- Python 3
- LangChain
- langchain-openai

## Setup (Google Colab)
### 1) Install dependencies
Run the install cell in the notebook:
```bash
pip install -U langchain langchain-openai
```

## 2) Add OpenAI API Key (Colab Secrets)

In Google Colab:

Open the left sidebar → Secrets

Add a new secret:

Name: OPENAI_API_KEY

Value: your OpenAI API key
