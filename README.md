# MediBuddy
# 🏥 Medical Chatbot – Python & Generative AI 🤖

Build a fully functional medical chatbot using Python, LangChain, and vector databases. This project demonstrates the end-to-end implementation of a telehealth AI assistant capable of answering medical queries using custom knowledge bases.

## Features

- Extracts and processes medical data from PDFs  
- Implements semantic search with vector databases (Pinecone)  
- Integrates Hugging Face embeddings for accurate understanding  
- Uses OpenAI language models for intelligent responses  
- Modular project structure for maintainability and scalability  
- Ready for deployment as a cloud-based service  

## Tech Stack

- Python  
- LangChain  
- Pinecone  
- Hugging Face  
- OpenAI API  
- Jupyter Notebook

## 🔑 API Keys Configuration

Before running the chatbot, you need to set your API keys in .env file:

```python
PINECONE_API_KEY = "<your_pinecone_api_key>"
GOOGLE_API_KEY = "<your_google_gemini_api_key>"  # Gemini API as Google API
