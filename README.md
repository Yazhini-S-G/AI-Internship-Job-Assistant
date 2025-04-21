# AI-Internship-Job-Assistant
# AI Resume Parser & Code Assistant (RAG-based)

This project is a **Retrieval-Augmented Generation (RAG)** powered application that parses resumes (PDFs), extracts information, and allows users to query job-related or technical questions using **LLM + Vector Search**. It also includes a **Code Assistant** that explains backend/frontend stack requirements interactively.

---

##  Features

-  Upload and parse resumes (PDFs) using **PyMuPDF**
-  Embed documents using **SentenceTransformers**
-  Perform fast semantic search using **FAISS**
-  Ask technical questions (RAG with HuggingFace Transformers)
-  Get code stack explanations (e.g., Backend/Frontend dev)
-  Powered by **Streamlit UI** for interactivity

---

##  Technologies Used

- Python 3.12+
- Streamlit
- PyMuPDF (fitz)
- FAISS (CPU)
- SentenceTransformers
- Transformers (HuggingFace)
- scikit-learn
- pandas, numpy

---

##  Installation

1. **Clone the repository**:

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
