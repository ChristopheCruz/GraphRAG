# GraphRAG-Based Knowledge Extraction with LangChain & Neo4j  

## Overview  

This project implements a **Graph Retrieval-Augmented Generation (GraphRAG)** system that extracts **entities** and **relationships** from text using **LangChain** and **Neo4j**. It supports **local LLMs via Ollama (Llama3)** and **cloud-based LLMs like OpenAI’s GPT models**.  

Unlike traditional **RAG**, which retrieves document chunks from vector databases, this **GraphRAG** approach structures knowledge as a **graph** for enhanced reasoning and retrieval.  

Developed in collaboration with **CB Laboratory**, this project showcases **LLMs + knowledge graphs** for improved NLP applications.  

## Features  

- **GraphRAG Implementation**: Enhances retrieval-augmented generation with graph-based reasoning.  
- **Local & Cloud LLM Support**:  
  - **Ollama (Llama3)** for offline processing.  
  - **OpenAI GPT models** via API.  
- **Entity & Relationship Extraction**: Uses **LangChain** to build a **knowledge graph** from text.  
- **Graph Storage & Retrieval**: Stores extracted knowledge in **Neo4j** and retrieves insights via **Cypher queries**.  
- **Graph Visualization**: Interactive visualization of entity relationships.  

## Technologies Used  

### Programming Languages:  
- **Python** – Core development language.  
- **Cypher** – Query language for Neo4j.  

### Development Environment:  
- **Google Colab & Local Machines** – Supports both cloud and local execution.  

### Database & Visualization:  
- **Neo4j** – Stores and queries structured knowledge.  

### Artificial Intelligence:  
- **Ollama (Llama3) for local processing**
-  **Gemini Pro – LLM used for knowledge extraction**
- **OpenAI GPT models (cloud API)**  

### Key Python Libraries:  
- `langchain_google_genai`  
- `langchain_community`  
- `langchain_experiment`  
- `neo4j`  
- `wikipedia`  
- `yfiles_jupyter_graphs`  
- `google.cloud.storage`  
- `pandas`  

## Installation  

1. **Clone the repository**:  
   ```sh
   git clone https://github.com/ChristopheCruz/GraphRAG.git
   cd GraphRAG
