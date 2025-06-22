# AgenticRag_Langgraph

 🔹 Project Description 🔹
LangGraph is a framework designed for building stateful, agent-centric applications with Large Language Models (LLMs).
It lets you create custom semantic graphs powered by LLMs — allowing for complex, mult-step conversations, tool usage, and orchestration of knowledge — all within a Streamlit UI.

🔹 Core Functionalities 🔹
Chatbot Application with Streamlit UI
Provides a convenient, interactive UI for users to chat with their agent.

Graph-Based Orchestration
Uses GraphBuilder to construct and manage a semantic graph, linking nodes to enable mult-step and context-aware conversations.

Customizable Large Language Model (LLM)
Supports a custom LLM (Groq) through GroqLLM.
Provides mechanisms for choosing, configuring, and integrating your preferred language model.

Modular and Extensible
The project’s structure allows adding new nodes, tools, or UI components without affecting core functionality.

🔹 How it Works 🔹
The Streamlit UI (app.py) lets users chat with the agent.

The selected use case guides the GraphBuilder to construct a semantic graph.

The GroqLLM serves as the large language model.

The constructed graph handles the flow of messages and maintains state across conversations.

<img width="941" alt="Streamlit_Chatbot" src="https://github.com/user-attachments/assets/4a174ee7-9fcf-4c90-bc56-ba2b66a9772b" />

LangSmith Tracing:
<img width="940" alt="LangSmith_Tracing" src="https://github.com/user-attachments/assets/d774c5a3-3e84-462c-b226-4a4b72e18f88" />


