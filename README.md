# Simple Document Q&A System using RAG

## About the Project

This is a simple RAG (Retrieval-Augmented Generation) project built using LangChain.

The project loads PDF documents, splits them into smaller chunks, creates embeddings, stores them in ChromaDB, retrieves the most relevant information based on the user's question, and uses a Groq LLM to generate an answer.

## Technologies Used

* Python
* LangChain
* HuggingFace Embeddings
* ChromaDB
* Groq (Llama 3.1)
* PyPDF

## Project Steps

1. Load PDF documents
2. Split the documents into chunks
3. Create embeddings for each chunk
4. Store the embeddings in ChromaDB
5. Retrieve the top 3 relevant chunks for a user query
6. Generate the final answer using Groq LLM

## How to Run

1. Clone the repository.

2. Install the required packages.
pip install -r requirements.txt

3. Create a `.env` file and add your Groq API key.
GROQ_API_KEY=your_api_key


4. Run the project by executing every cell in the app.ipynb file.

## Sample Question

What is RAG?

## Sample Output

Retrieval-Augmented Generation (RAG) is a technique that retrieves relevant information from documents and uses it as context to generate accurate answers.