🤖 Chatbots with LangGraph – Basic & Tool-Enhanced Agents

This project demonstrates how to build conversational AI agents using LangGraph, a graph-based orchestration framework from LangChain, powered by Groq's Gemma2-9b-It model for ultra-fast and intelligent responses. The implementation includes two key notebooks:

1. Basic Chatbot with LangGraph
This notebook builds a minimal conversational agent using LangGraph and StateGraph. It defines a simple flow where user input is passed to an LLM and the response is returned in real time. Ideal for learning the core concepts of LangGraph like nodes, edges, and message state handling.

2. LangGraph Chatbot with Tools (Wikipedia & Arxiv)
The second notebook showcases a tool-augmented LangGraph agent, which can:

    o Search Wikipedia for factual information.

    o Query Arxiv for academic papers.

    o Automatically invoke external tools when required using LangGraph’s ToolNode and tools_condition.

Key features:

->🧠 Uses Groq-hosted Gemma2-9b-It for low-latency inference.

->🔁 Built using LangGraph’s dynamic message-passing architecture.

->🔧 Integrates external tools for factual lookups.

->📊 Optional Mermaid diagram visualization of the chatbot flow.

These notebooks are excellent for anyone looking to explore modular, graph-based LLM orchestration, especially for building intelligent assistants that combine language modeling with real-world tools.
