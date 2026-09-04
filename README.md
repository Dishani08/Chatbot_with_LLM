# Chatbot with LLM

A simple AI chatbot built using Python, LangChain, Streamlit, and an LLM.

## Features

- Chat with an AI using natural language
- LLM integration using LangChain
- Tool calling with LangChain
- Wikipedia search tool
- Tavily web search tool
- Mathematical operations using custom tools
- Streamlit-based chatbot interface

## Technologies Used

- Python
- LangChain
- Streamlit
- LLM
- Wikipedia API
- Tavily
- Git & GitHub

## Project Structure

    Chatbot_with_LLM/
    │
    ├── LangchainBasics/
    │   ├── langchainbasics.ipynb
    │   ├── qachatbot.py
    │   └── tool.ipynb
    │
    ├── src/
    │   └── chatbot_with_llm/
    │
    ├── .gitignore
    ├── .python-version
    ├── requirements.txt
    ├── pyproject.toml
    ├── uv.lock
    └── README.md

## How It Works

The chatbot uses an LLM to understand the user's question.

Depending on the question, the LLM can decide whether a tool is required. For example:

- Mathematical questions → Calculator tools
- Information about a topic → Wikipedia tool
- Web-related queries → Tavily search tool

The tool result is then passed back to the LLM, which generates the final response.

## Learning Outcomes

Through this project, I learned:

- Basics of LangChain
- LLM integration
- Tool calling
- Working with AI messages and tool messages
- Connecting external tools with an LLM
- Building a simple LLM-based application
- Managing a Python project using Git and GitHub

## Author

**Dishani Chauhan**

GitHub: [Dishani08](https://github.com/Dishani08)
