Session Kickoff
Live session after a long break; audio confirmation and engagement requested.

A 3-day workshop focused on building an end-to-end Agentic AI project with LLM Ops integration.

📋 Agenda Overview
Day 1: Problem statement + environment + folder structure setup.

Day 2 & 3: Full project implementation and deployment.

All sessions are interactive and will be recorded and shared.

Emphasis on modular coding, LLM Ops fundamentals, and project deployment.

🧠 Prerequisites
Python (modular coding: classes, inheritance, functions).

Familiarity with LangGraph (video tutorials available).

Knowledge of NLP, deep learning, Generative AI is helpful.

Use of UV package for modern environment management (faster than pip/conda).

🧭 Problem Statement
Build an AI-based Trip Planner using agentic AI and real-time data.

Key Features:

Realtime weather info

Tourist attractions and activities

Hotel costs

Currency conversion

Itinerary planning

Expense calculation

Summary generation as a document (txt, PDF, etc.)

🛠️ Tools, Libraries, and Setup
UV: used to manage environments, install packages.

VS Code: preferred IDE for implementation.

LangGraph: to model agent workflows using nodes, edges, and state graphs.

Open-source models like Grok may be used.

Optional deployment on AWS or other cloud platforms.

Logger & custom exception handling implemented using Python best practices.

🧱 Folder & File Structure
agent/: Agentic workflow logic

tools/: Modular tools (e.g., weather, currency, attractions, arithmetic ops)

prompt_library/: Prompt templates for each agent

config/: YAML configuration files

utils/: Model loaders, config loaders, currency converters, etc.

notebook/: Jupyter notebooks for experiments

logger/: Custom logging implementation

exception/: Custom exception classes

app.py / main.py: Streamlit or FastAPI backend

requirements.txt, setup.py, pyproject.toml: Dependency and project setup

.env: Environment variables (e.g., API keys)

🔐 API Keys Used
OpenAI / Groq API key

Google API key (including G-Places key)

Tably (for realtime information)

OpenWeatherMap API

ExchangeRate API (currency conversion)

FourSquare API (alternative to G-Places)

Langsmith API (for logging/tracking flows)

🧪 Demonstration
Live walkthrough of:

Creating project with uv init

Creating and activating a UV virtual environment

Installing packages with uv pip install

Folder and file creation, modular design explanation

Explanation of LangGraph’s node-edge-state structure

Environment and dependency setup with setup.py

📦 Key Packages Installed
langchain

langgraph

fastapi

Others as needed (added on the fly via uv add or requirements file)

🔁 Code Management
GitHub repository created and shared.

All setup commands and folder templates added in the README.

.env file contents (excluding secrets) shared as a reference.

📣 Announcements
LLM Ops Live Batch starting July 12, 2–5 PM (4–5 months duration).

Projects: RAG apps, e-commerce assistant, document analysis, semantic image search, MCP integration, etc.

Live and recorded access with Udemy coupons provided.

20% discount currently active.

✅ Closing Remarks
Session praised by participants.

Tomorrow (Day 2) will continue with development.

Emphasis on industrial relevance and building real-world, scalable GenAI systems.
