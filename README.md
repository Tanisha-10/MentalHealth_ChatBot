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
![image](https://github.com/user-attachments/assets/df1a9810-1592-4c5f-b2af-b3f73e61de77)
![Screenshot 2025-04-04 121621](https://github.com/user-attachments/assets/a723333d-e754-4132-86b4-48f6f3eecda7)
![Screenshot 2025-04-04 121728](https://github.com/user-attachments/assets/bdd3da29-49d3-4f62-a976-70f8bb23c8d9)
![Screenshot 2025-04-04 121827](https://github.com/user-attachments/assets/c8209607-bfe2-4383-a2c6-1251ebe3f254)


## License
MIT License to uploaded soon!!

✍️ Author
Tanisha Jaiswal

Happy coding!


 
