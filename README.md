# AI Project 1: Conversational AI Agent

This project is a simple conversational AI agent built with Python. The agent can chat with users, perform basic calculations, and greet users using custom tools. It demonstrates how to integrate OpenAI's language models with custom logic and tools using modern Python AI frameworks.

## Features

- **Conversational AI:** Chat with the assistant in natural language.
- **Custom Tools:** 
  - Calculator for basic arithmetic operations.
  - Greeting tool for personalized messages.
- **Streaming Responses:** The assistant responds in real-time as it generates answers.

## Tools & Libraries Used

- [![OpenAI](https://img.shields.io/badge/OpenAI-API-blue?logo=openai)](https://platform.openai.com/) &nbsp; For natural language understanding and generation.
- [![LangChain](https://img.shields.io/badge/LangChain-Framework-yellowgreen?logo=python)](https://python.langchain.com/) &nbsp; Framework for building applications with language models and tools.
- [![LangGraph](https://img.shields.io/badge/LangGraph-Agent%20Execution-orange?logo=python)](https://github.com/langchain-ai/langgraph) &nbsp; For agent execution and streaming.
- [![python-dotenv](https://img.shields.io/badge/python--dotenv-Env%20Vars-green?logo=python)](https://pypi.org/project/python-dotenv/) &nbsp; To manage environment variables securely.

## Setup Instructions

1. **Clone the repository** and navigate to the project folder.
2. **Install dependencies** (using [uv](https://github.com/astral-sh/uv) or pip):
   ```
   uv pip install -r requirements.txt
   ```
   or
   ```
   pip install -r requirements.txt
   ```
3. **Set up your OpenAI API key:**
   - Create a `.env` file in the project directory.
   - Add your API key:
     ```
     OPENAI_API_KEY=your-openai-api-key
     ```

4. **Run the project:**
   ```
   uv run main.py
   ```
   or
   ```
   python main.py
   ```

## How It Works

- The agent uses OpenAI's language model to interpret user input.
- Custom tools (calculator, greeting) are registered and can be called by the agent when appropriate.
- The conversation continues until the user types `quit`.

## Example Usage

```
Welcome! I'm your AI assistant. Type 'quit' to exit.
You can ask me to perform calculations or chat with me.

You: What is the sum of 5 and 7?
Assistant: The sum of 5 and 7 is 12

You: Say hello to John
Assistant: Hello John, I hope you are well today
```

## Credits

- Built with [LangChain](https://python.langchain.com/) and [OpenAI](https://platform.openai.com/).
- Inspired by modern conversational AI agent architectures.

---
Feel free to modify and extend this project for your own use!