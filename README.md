# CS 5542 — Week 1 Lab
**Mini-RAG System: Transformers, Embeddings & Vector Retrieval**  
GitHub → Colab → Hugging Face → FAISS

## Objectives
By the end of this lab, you will:
- Use GitHub for collaborative workflows (repo, commit, PR)
- Run a Jupyter notebook in Google Colab
- Load a Transformer encoder model and dataset from Hugging Face Hub
- Build an embedding-based **vector retrieval** system (the backbone of RAG)

## GenAI Systems Context (Why this matters)
This lab implements the **retrieval layer** used in enterprise GenAI systems:
- **Embeddings** map documents into vectors (meaning space)
- **Vector retrieval** finds relevant context for a query
- **LLMs** generate answers using retrieved context (reducing hallucination)

---

## Information
- Name: Immanuel Olaoye
- Major: Computer Science
- Project Interest: undecided

## Checklist

### GitHub
- [ ] Fork the course repository
- [ ] Edit `README.md` with your name, major, and project interest
- [ ] Commit changes
- [ ] Open a Pull Request

### Google Colab
- [ ] Open `week1_embeddings.ipynb` from GitHub
- [ ] Install required libraries
- [ ] Run all cells successfully

### Hugging Face
- [ ] Find the model: `all-MiniLM-L6-v2`
- [ ] Find the dataset: `ag_news`

### Retrieval Task
- [ ] Run `search("artificial intelligence in healthcare")`
- [ ] Observe retrieved documents

---

## Exit Ticket
Post a GitHub Issue titled:
> **Reflection — Retrieval before Generation (Mini-RAG)**

Write 1–2 sentences explaining how embeddings + retrieval support grounded generation in GenAI systems.
