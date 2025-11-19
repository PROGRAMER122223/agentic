# 🚀 Python Project with LangGraph, LangChain, and Google Vertex AI

This project demonstrates how to integrate **LangGraph**, **LangChain**, and **Google Vertex AI** into a Python workflow.  
It uses environment variables for authentication and runs a simple test query against the Gemini model.

---

## 📦 Installation ## Env



Initialize your project and install dependencies using [uv](https://github.com/astral-sh/uv):

```bash
uv add langgraph langchain
uv add "langchain[google-vertexai]"
uv add python-dotenv

## Env
GOOGLE_APPLICATION_CREDENTIALS=path/to/your/service_account.json
PROJECT_ID=your-gcp-project-id
LOCATION=us-central1
