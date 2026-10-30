AI Knowledge Assistant

An AI-powered PDF knowledge assistant that uses semantic search and document embeddings to retrieve relevant information from uploaded documents.

Project Overview

This project allows users to upload a PDF and ask questions about its content. It finds the most relevant text passages using semantic similarity.

Features

- PDF text extraction
- Automatic text chunking
- Sentence embeddings using "all-MiniLM-L6-v2"
- Semantic similarity search
- Top 3 relevant passages retrieval
- Interactive Gradio interface

Tech Stack

- Python
- Google Colab
- Sentence Transformers
- FAISS (installed for vector search)
- LangChain Text Splitters
- Gradio
- PyPDF

How It Works

1. Upload a PDF document.
2. Extract text from the PDF.
3. Split the text into smaller chunks.
4. Convert chunks into vector embeddings.
5. Search for relevant chunks based on the user's question.
6. Display the most relevant passages.

Run the Project

Open "AI_Knowledge_Assistant.ipynb" in Google Colab and run the notebook cells in order. Upload a PDF when prompted.

Current Status

Working prototype: retrieves relevant passages from uploaded PDF documents through a Gradio interface.

Future Improvements

- Add LLM-based answer generation
- Improve source citations
- Support multiple PDF documents
- Deploy as a hosted web application

Author

AIML Student | AI & Machine Learning Projects
