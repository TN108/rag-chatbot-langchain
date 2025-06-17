# 💬 RAG-Based Chatbot with LangChain, FAISS, and OpenAI

This project implements a **Retrieval-Augmented Generation (RAG)** chatbot that can answer user queries based on a custom document corpus. It uses **LangChain** to orchestrate retrieval and generation, **FAISS** for fast vector similarity search, and **OpenAI's LLMs** for natural language response generation.

> 🧠 Built as part of a lab assignment on Large Language Models, focusing on real-world applications of RAG architectures.

---

## 📌 Key Features

- 🔍 **Semantic Search with FAISS**  
  Efficiently retrieves relevant chunks of text from indexed documents using vector similarity.

- 🧱 **LangChain Integration**  
  Chains together retrieval and generation steps, handling prompt formatting and LLM invocation.

- 🤖 **LLM-Powered Response Generation**  
  Uses OpenAI (e.g., `gpt-3.5-turbo`) to generate coherent and relevant answers from retrieved context.

- 🎥 **YouTube Transcript Dataset**  
  Uses transcripts from a YouTube playlist as the knowledge base for question answering.

---

## 📂 Project Structure

