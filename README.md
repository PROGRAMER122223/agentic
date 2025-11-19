# 🚀 Python Project with LangGraph, LangChain, and Google Vertex AI

This project demonstrates how to integrate **LangGraph**, **LangChain**, and **Google Vertex AI** into a Python workflow.  
It uses environment variables for authentication and runs a simple test query against the Gemini model.

---

## 📦 Installation 

Initialize your project and install dependencies using [uv](https://github.com/astral-sh/uv):

```bash
uv add langgraph langchain
uv add "langchain[google-vertexai]"
uv add python-dotenv

## Env

Make sure you have enabled Vertex AI API in your Google Cloud project.

Notes
- init_chat_model is a LangGraph helper that uses your environment variables for authentication.
- GenerativeModel is the direct Vertex AI client for Gemini models.
- Ensure your service account has the correct permissions (roles/aiplatform.user).

📚 References
- LangChain Documentation
- LangGraph Documentation
- Google Vertex AI
