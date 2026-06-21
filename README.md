# 📚 BookRAG Assistant

BookRAG Assistant is a Retrieval-Augmented Generation (RAG) application that allows users to upload PDF documents and ask questions in natural language. It uses LangChain, Mistral AI, ChromaDB, and Streamlit to provide context-aware answers from the uploaded documents.

## 🚀 Features

- Upload PDF documents
- Semantic search with vector embeddings
- MMR-based retrieval
- Context-aware answers using Mistral AI
- Streamlit web interface
- ChromaDB vector storage

## 🛠 Tech Stack

- Python
- LangChain
- Mistral AI
- ChromaDB
- Streamlit
- PyPDF

## 📂 Project Structure

```text
BookRAG-Assistant/
│
├── app.py
├── main.py
├── requirements.txt
├── .env
├── chroma_db/
└── README.md
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/BookRAG-Assistant.git
cd BookRAG-Assistant
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Create a `.env` file:

```env
MISTRAL_API_KEY=your_api_key
```

## ▶️ Run

```bash
streamlit run app.py
```

## 🔄 Workflow

```text
PDF
 ↓
Chunking
 ↓
Embeddings
 ↓
ChromaDB
 ↓
MMR Retriever
 ↓
Mistral AI
 ↓
Answer
```

## Example Questions

- Summarize Chapter 1
- Explain GRU architecture
- What are the advantages of LSTM?
- Give key points from the document

## Future Improvements

- Multiple PDF support
- Chat history
- Source citations
- Hybrid search
- Streaming responses

## Author

**Priyansh Gautam**

Built with LangChain, Mistral AI, ChromaDB, and Streamlit.
