# AI Semantic Search Engine

Search documents using natural language. AI finds relevant content based on meaning, not just keywords.

## 🚀 [Try it Live!](https://huggingface.co/spaces/dakota-stpierre/SEMANTIC_SEARCH_ENGINE?logs=container)

## 🛠️ Tech Stack
- **Embeddings:** Sentence Transformers (all-MiniLM-L6-v2)
- **Vector Search:** FAISS (Facebook AI Similarity Search)
- **Interface:** Gradio
- **Framework:** Python

## 📊 Features
- Semantic search based on meaning, not keywords
- Add unlimited documents to search index
- Fast similarity search using FAISS
- Returns top-K most relevant results
- Adjustable number of results

## 🧠 How It Works
1. Documents are converted to vector embeddings using Sentence-BERT
2. Embeddings stored in FAISS index for fast retrieval
3. User query is converted to same vector space
4. FAISS finds nearest neighbor documents
5. Results ranked by semantic similarity

## 🎯 Use Cases
- Document Q&A systems
- Knowledge base search
- Content recommendation
- RAG (Retrieval-Augmented Generation) pipelines

## 💻 Run Locally
```bash
pip install -r requirements.txt
python app.py
```

## 📝 What I Learned
- Vector embeddings and semantic similarity
- FAISS for efficient similarity search
- Building search systems with transformers
- Foundation for RAG applications

Part of my AI/ML portfolio showcasing NLP and vector search capabilities.
