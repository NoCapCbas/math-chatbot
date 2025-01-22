# Dog Breed Assistant Chatbot

This is a chatbot using Llama 2, Sentence Transformers, CTransformers, Langchain, and Streamlit.

A Streamlit-based chatbot that helps users learn about different dog breeds. Built with:
- Streamlit for the web interface
- Mistral 7B (via Ollama) for the language model
- FAISS for vector storage
- LangChain for the conversation chain

## How to run the app

1. Clone the repository
2. Run `python -m venv venv`
3. Run `source venv/bin/activate`
4. Run `pip install -r requirements.txt`
5. Run `streamlit run app.py`
6. Open the app in your browser at `http://localhost:8501`