# 💎 AI-Consultant for Jewelry with RAG and LangChain

This project presents an intelligent AI assistant for the jewelry business. The assistant is capable of answering questions about jewelry characteristics, care, and selection, as well as providing recommendations based on specific client requests. The system uses **Retrieval-Augmented Generation (RAG)** and the **LangChain** library to extract information from a knowledge base and generate responses.

## 🚀 Key Features

* **Product Search based on client requests**: smart selection of jewelry taking into account characteristics, price, and use.
* **Multimodal Search Support**: text queries are processed with high accuracy.
* **Autonomous Agents**: request processing, recommendation generation, and interaction management.
* **Use of Vector Knowledge Bases**: searching the database using FAISS and ChromaDB.
* **Context-Based Response Generation**: utilizes large language models (LLMs).

## 🛠 Technology Stack

* **Language Models**:
    * `saiga_llama3_8b`
* **LangChain**: for creating processing chains and integrating with databases
* **FAISS and ChromaDB**: storing and retrieving vector data
* **OpenAI Whisper**: transcription for call analysis (optional)
* **Unstructured API**: for parsing various document formats
* **Local or Cloud Deployment**: supports AWS, Azure, and other platforms
* **Tools**:
    * Python

## 📦 Project Structure

1.  **Data Preparation**:
    * Creation of a jewelry catalog in JSON format.
    * Transformation of data into vector representations using Sentence Transformers.
2.  **Knowledge Base Creation**:
    * Vectorization of product descriptions and saving to FAISS/ChromaDB.
    * Integration of the knowledge base with the recommendation system.
3.  **Text Generation Models**:
    * Fine-tuning of the `saiga_llama3_8b` model.
    * Generation of responses to queries considering context and the knowledge base.
4.  **Interaction Interface**:
    * Autonomous agent for processing questions and formulating responses.
    * Possibility of integration via API.

## 🌟 Use Cases

* **Question**: "How to care for silver jewelry?"
    * **Answer**: Detailed description of care, including recommendations for storage and cleaning.
* **Question**: "Help me choose a diamond ring under 50,000 rubles."
    * **Answer**: Suggestion of suitable products from the database with description, link, and price.

## 📈 What does this project offer?

* **Client Experience Optimization**: reduced time for product search.
* **Increased Sales**: thanks to accurate recommendation selection.
* **Automation**: reduced employee workload through the AI assistant.

## 📋 How to Run the Project

1.  Run each line of code in the notebook sequentially.
2.  Prepare the catalog data in JSON format.
3.  Use queries for interaction:
    * "How to care for gold jewelry?"