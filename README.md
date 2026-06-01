# Full Stack GenAI Bootcamp 1.0

A hands-on learning journey through Generative AI — from fundamentals to full-stack applications.

---

## About

This repository documents my progress through the Full Stack GenAI Bootcamp. It covers core concepts in large language models, retrieval-augmented generation, embeddings, and building real-world AI-powered applications using modern frameworks and APIs.

---

## What I'm Learning

- **LLMs & Prompt Engineering** — Working with Claude, GPT, Groq, and open-source models
- **Embeddings & Semantic Search** — Sentence transformers, BM25, vector similarity
- **RAG (Retrieval-Augmented Generation)** — Building pipelines that combine search with generation
- **LangChain** — Chaining LLMs, tools, and memory for complex workflows
- **Fine-tuning & Transformers** — HuggingFace `transformers` and `datasets`
- **Multi-modal AI** — Image + text tasks with `torchvision` and `pillow`
- **Evaluation** — Benchmarking with MTEB

---

## Tech Stack

| Category | Libraries |
|---|---|
| ML / Math | `scikit-learn`, `numpy`, `scipy`, `torch`, `torchvision` |
| NLP | `transformers`, `sentence-transformers`, `gensim`, `nltk` |
| Retrieval | `rank-bm25`, `datasets`, `mteb` |
| LangChain Integrations | `langchain-anthropic`, `langchain-openai`, `langchain-groq`, `langchain-huggingface`, `langchain-ollama`, `langchain-openrouter`, `langchain_google_genai` |
| Utilities | `tenacity`, `pyyaml`, `pillow`, `ipykernel` |
| Language | Python 3.11 |

---

## Project Structure

```
FULL-STACK-GENAI-BOOTCAMP-1.0/
├── Class-03-29-Mar/       # Session notes and exercises
├── requirements.txt       # All dependencies
└── README.md
```

---

## Getting Started

**1. Clone the repository**
```bash
git clone <your-repo-url>
cd FULL-STACK-GENAI-BOOTCAMP-1.0
```

**2. Create and activate the virtual environment**
```bash
python3.11 -m venv .venv
source .venv/bin/activate
```

**3. Install dependencies**
```bash
pip install -r requirements.txt
```

---

## Environment Variables

Create a `.env` file in the root directory and add your API keys:

```env
ANTHROPIC_API_KEY=your_key_here
OPENAI_API_KEY=your_key_here
GROQ_API_KEY=your_key_here
GOOGLE_API_KEY=your_key_here
```

> Never commit your `.env` file. It is already listed in `.gitignore`.

---

## Progress

| Session | Topic | Status |
|---|---|---|
| Class 03 — 29 Mar | Getting started | In progress |

---

## Author

**Govind Singh Bora**
Learning GenAI one class at a time.
