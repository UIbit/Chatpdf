# My Personal PDF Chatbot

## Overview
This is a custom PDF Chatbot that allows you to interact with your PDF documents using natural language. It uses Retrieval Augmented Generation (RAG) to provide accurate answers based on the content of your uploaded files.

## Features
- **Intelligent Q&A**: Ask questions and get answers directly from your PDFs.
- **Multiple Document Support**: Upload and chat with multiple PDFs at once.
- **Conversation History**: Keeps track of your conversation for contextual answers.

## How to Use
1. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
2. **Set Up Environment**: Create a `.env` file and add your `OPENAI_API_KEY`.
3. **Run the App**:
   ```bash
   streamlit run app.py
   ```
4. **Upload & Chat**: Use the sidebar to upload your PDFs, click "Process", and start chatting!

## Technical Stack
- **Framework**: Streamlit
- **LLM**: GPT-3.5 Turbo (OpenAI)
- **Embeddings**: HuggingFace all-MiniLM-L6-v2
- **Vector Database**: FAISS
- **Orchestration**: LangChain
