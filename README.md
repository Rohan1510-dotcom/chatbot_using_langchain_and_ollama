# chatbot_using_langchain_and_ollama

A simple interactive chatbot web app built using LangChain, Ollama (LLaMA2), and Streamlit. This project demonstrates how to connect a local LLM (running via Ollama) with LangChain prompt pipelines and deploy it as a lightweight web interface.

📌 Project Overview

This project allows users to:

Enter a question in a web UI

Send the prompt through a LangChain pipeline

Get a response from a locally running LLaMA2 model via Ollama

The chatbot runs completely locally, making it fast, private, and suitable for experimentation and learning.

🚀 Features

🔗 LangChain prompt chaining

🤖 Local LLaMA2 model using Ollama (no paid API required)

🌐 Interactive web UI using Streamlit

🧱 Modular structure with prompt templates and output parsers

⚡ Lightweight and beginner-friendly project

🛠️ Tech Stack

Python 3.10+

LangChain (prompt orchestration)

Ollama (local LLM runtime)

LLaMA2 model

Streamlit (web interface)

python-dotenv (environment variable management)

🧠 How It Works

User enters a question in the Streamlit UI

The input is passed into a LangChain ChatPromptTemplate

The chain sends the formatted prompt to the Ollama LLaMA2 model

The model generates a response

The response is displayed back in the UI

