# Agent Based LLM

- Utilised Ollama to interact with the Llama 3.1 8B Instruct model to create a decision making agent.
- The Agent has to decide how to answer the user query, provided it has access to the following tools:
  1. To make a DB call (used SQLite to create a synthetic database)
  2. To use a XYZ company's documents as a vector database (RAG System)
  3. To use its own general knowledge.
 
- Tools used;
  1. Ollama - to utilise the LLM
  2. Langchain - for creating a retrieval chain
  3. SQLite - for hosting a summy dataset


