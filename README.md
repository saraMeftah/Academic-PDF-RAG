# Academic PDF RAG

A RAG chatbot that answers questions using information retrieved from academic PDF documents.

## How it works

1. Extract text from PDF files.
2. Split the text into chunks.
3. Convert chunks into embeddings.
4. Store the embeddings in a FAISS index.
5. Retrieve relevant chunks for each question.
6. Use Qwen to generate an answer from the retrieved context.

## Tools

- PyMuPDF
- Sentence Transformers
- FAISS
- Qwen2.5-3B-Instruct
- Gradio
- Google Colab

## Run the project

1. Open `rag.ipynb` in Google Colab.
2. Run the notebook cells in order.
3. Upload your academic PDF files when prompted.
4. Wait for the index and language model to load.
5. Open the Gradio interface and ask questions about your PDFs.

## Example questions

- `c quoi rag`
- `how rag works`
