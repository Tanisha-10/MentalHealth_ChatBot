# Mental Health Chatbot

A compassionate AI-powered mental health chatbot that leverages advanced NLP models to provide supportive and thoughtful conversations. Built using LangChain, Gradio, ChromaDB, and HuggingFace models.

## Features
- **Contextual Chatting:** Uses a vector database for context-aware responses.
- **Persistent Database:** Stores and retrieves conversation history using ChromaDB.
- **Custom Prompting:** Tailored prompt to make the chatbot empathetic and responsive.
- **User-Friendly Interface:** Built using Gradio Blocks for seamless interaction.
- **Scalable:** Can be deployed on HuggingFace Spaces or other cloud platforms.

## Installation
```bash
pip install langchain gradio chromadb sentence-transformers
pip install langchain_groq
```

## Usage
1. Clone this repository:
```bash
git clone <repository_url>
cd <repository_directory>
```
2. Place your PDF files in the `/data` folder.
3. Run the Python script:
```bash
python mental_health_chatbot.py
```

## File Structure
```
- mental_health_chatbot.py     # Main application code
- /data                       # Folder containing PDF files
- /chroma_db                  # Directory to save the vector database
```

## Requirements
- Python 3.10.10
- langchain
- gradio
- chromadb
- sentence-transformers
- langchain_groq

## Deployment
To deploy on Hugging Face Spaces:
```bash
gradio deploy
```

## Screenshots
(Include screenshots of your chatbot interface here)

## License
This project is licensed under the MIT License.


 
