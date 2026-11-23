# RAG PDF Chatbot

A Retrieval-Augmented Generation (RAG) app that answers questions from a PDF
using LangChain, Google Gemini, and the FAISS vector database.

## How it works
PDF -> chunks -> embeddings -> FAISS -> retrieve top 4 chunks -> Gemini -> answer

## Tech stack
Python, LangChain, Gemini API, FAISS, PyPDF

## Run it
1. Open `rag_project.ipynb` in Google Colab
2. Add your key in Colab Secrets (key icon) as `GOOGLE_API_KEY`
3. Upload `notes.pdf` (or your own PDF) to Colab
4. Run all cells and ask questions

## Example questions
- How much is the course fee?
- Are the recordings available? For how long?
