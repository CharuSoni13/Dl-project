# 📚 Research Paper Analysis using Deep Learning & NLP

A Deep Learning and Natural Language Processing project that analyzes research papers by extracting structured information, generating summaries, identifying technical entities, and visualizing relationships through a knowledge graph.

The project aims to automate several time-consuming tasks involved in reading and understanding academic papers.

---

## ✨ Features

- 📄 Download research papers directly from arXiv
- 📑 Extract and preprocess text from PDF files
- 📚 Detect paper sections (Abstract, Introduction, Methodology, Results, Conclusion, etc.)
- 🔍 Custom Technical Named Entity Recognition (NER)
  - Models
  - Frameworks
  - Libraries
  - Datasets
  - Optimizers
  - Evaluation Metrics
  - Programming Languages
  - Hardware
- 📊 Extract hyperparameters and evaluation metrics
- 📝 Generate paper-level and section-wise summaries using Transformer models
- 🔑 Keyword extraction using KeyBERT
- 🏷️ Research domain classification
- 💡 Basic novelty analysis based on common and emerging AI techniques
- 🕸️ Knowledge graph visualization
- ❓ Question Answering over research papers
- 🤝 Similar paper recommendation using semantic embeddings

---

## 🚀 Tech Stack

- Python
- Google Colab
- PyTorch
- Hugging Face Transformers
- FLAN-T5
- Sentence Transformers
- spaCy
- KeyBERT
- NetworkX
- Matplotlib
- PyPDF
- Requests
- Pandas

---

## 📂 Project Workflow

```
Research Paper PDF
        │
        ▼
PDF Text Extraction
        │
        ▼
Text Cleaning & Preprocessing
        │
        ▼
Section Detection
        │
        ▼
Technical NER
        │
        ▼
Information Extraction
        │
        ├────────► Hyperparameters
        ├────────► Metrics
        ├────────► Keywords
        ├────────► Topic Classification
        ├────────► Novelty Detection
        │
        ▼
Transformer-based Summarization
        │
        ▼
Knowledge Graph
        │
        ▼
Question Answering
        │
        ▼
Similar Paper Recommendation
```

---

## 📌 Key Highlight

One of the main features of this project is the **Custom Technical Named Entity Recognition (NER)**.

Unlike traditional NER models that primarily identify entities such as **Person**, **Organization**, and **Location**, this project extracts AI-specific entities including:

- Machine Learning Models
- Frameworks
- Libraries
- Datasets
- Optimizers
- Evaluation Metrics
- Programming Languages
- Hardware Platforms

This makes the pipeline more suitable for technical research papers.

---

## 📷 Sample Outputs

The project generates:

- Paper Summary
- Section-wise Summaries
- Extracted Technical Entities
- Hyperparameters
- Evaluation Metrics
- Keywords
- Research Domain
- Novelty Analysis
- Knowledge Graph
- Question Answering Results
- Similar Research Papers

---

## 📁 Repository Structure

```
Research-Paper-Analysis/
│
├── Research_Paper_Analysis.ipynb
├── README.md
├── requirements.txt
└── sample_outputs/
```

---

## 📈 Future Improvements

- Support additional research repositories
- Improved technical entity extraction using custom models
- Better summarization for long documents
- Retrieval-Augmented Generation (RAG)
- Interactive knowledge graph
- Research paper comparison
- Citation recommendation
- Web-based interface

---

