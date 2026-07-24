# 🤗 AI Foundations #01 — Hugging Face Fundamentals

<div align="center">

# Learn Hugging Face from First Principles

*A comprehensive, beginner-friendly guide to understanding and using the Hugging Face ecosystem through theory, visual explanations, and hands-on implementation.*

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![PyTorch](https://img.shields.io/badge/Powered%20By-PyTorch-red)
![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow)
![License](https://img.shields.io/badge/License-MIT-green)
![Beginner Friendly](https://img.shields.io/badge/Level-Beginner-success)

</div>

---

## 📖 About the AI Foundations Series

Welcome to the **AI Foundations** series.

The goal of this series is not just to teach you how to use AI libraries, but to help you understand **how modern Large Language Models (LLMs) actually work**.

Instead of treating AI as a black box, we will gradually build our understanding from the ground up.

By the end of this series, you will understand concepts ranging from tokenization and embeddings to attention mechanisms, transformers, fine-tuning, Retrieval-Augmented Generation (RAG), LangChain, and production-ready AI applications.

Every repository focuses on one major concept and builds on the knowledge gained in previous repositories.

---

## 📚 Series Roadmap

| Repository | Topic | Status |
|------------|-------|--------|
| 01 | Hugging Face Fundamentals | ✅ Current |
| 02 | LLM Text Generation Pipeline | ⏳ Coming Soon |
| 03 | Embeddings & Word2Vec | ⏳ Coming Soon |
| 04 | Self-Attention Mechanism | ⏳ Coming Soon |
| 05 | Transformer From Scratch | ⏳ Coming Soon |
| 06 | Mini GPT Implementation | ⏳ Coming Soon |
| 07 | Fine-Tuning Transformers | ⏳ Coming Soon |
| 08 | Retrieval Augmented Generation (RAG) | ⏳ Coming Soon |
| 09 | LangChain Fundamentals | ⏳ Coming Soon |
| 10 | Production AI Chatbot | ⏳ Coming Soon |

---

# 🎯 Repository Overview

This repository serves as the foundation for the entire AI Foundations series.

If you're completely new to Hugging Face, Transformers, or Large Language Models, this repository is the best place to start.

Rather than immediately jumping into advanced topics like attention, embeddings, or transformers, we'll first understand the tools that power modern AI applications.

By the end of this repository, you'll be comfortable working with the Hugging Face ecosystem and understand the complete workflow of loading pretrained models, tokenizing text, generating outputs, and building simple AI applications.

---

# 🤔 Why Hugging Face?

Before Hugging Face existed, using state-of-the-art NLP models required downloading research papers, reproducing implementations, training models manually, and writing thousands of lines of code.

Today, Hugging Face provides a unified ecosystem where developers can:

- Discover thousands of pretrained models
- Download datasets
- Train and fine-tune models
- Share models with the community
- Build AI applications quickly
- Deploy models for production

It has become the de facto standard library for working with modern Transformer-based models.

Whether you're using GPT-2, BERT, T5, Llama, Mistral, Gemma, or any other popular open-source model, chances are you'll interact with it through Hugging Face.

---

# 🎯 Learning Objectives

After completing this repository, you will be able to:

### Knowledge

- Explain what Hugging Face is
- Understand the Hugging Face ecosystem
- Explain the role of tokenizers
- Understand pretrained Transformer models
- Understand Auto Classes
- Explain how text generation works

### Practical Skills

- Install the Transformers library
- Load pretrained models
- Load tokenizers
- Encode and decode text
- Generate text using GPT-2
- Use the Pipeline API
- Experiment with generation parameters

### Career Skills

- Explain Hugging Face during interviews
- Build simple AI applications
- Understand how Hugging Face fits into modern LLM development
- Prepare for deeper AI concepts covered later in the series

---

# 👨‍💻 Who is this repository for?

This repository is designed for:

- Software Engineers
- Frontend Developers
- Backend Developers
- Full Stack Developers
- Machine Learning Beginners
- AI Enthusiasts
- Students
- Professionals transitioning into AI Engineering

No prior AI knowledge is required.

Basic Python programming is enough to complete this repository.

---

# 🛠️ Prerequisites

To get the most from this repository, you should have:

- Basic Python knowledge
- Familiarity with functions and classes
- Python 3.10+
- Jupyter Notebook or Google Colab
- Basic understanding of machine learning terminology (optional)

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/<your-username>/ai-foundations-01-huggingface-fundamentals.git
```

Move into the project directory

```bash
cd ai-foundations-01-huggingface-fundamentals
```

Install the dependencies

```bash
pip install -r requirements.txt
```

Or install manually

```bash
pip install transformers
pip install datasets
pip install torch
pip install sentencepiece
pip install accelerate
```

Verify the installation

```python
from transformers import pipeline

generator = pipeline("text-generation", model="gpt2")

print(generator("Artificial Intelligence is", max_new_tokens=20))
```

If everything is installed correctly, you should see GPT-2 generate a continuation of the input text.

---

# 📂 Repository Structure

```text
ai-foundations-01-huggingface-fundamentals/

│── README.md
│── LICENSE
│── requirements.txt
│── .gitignore
│
├── notebooks/
│   ├── 01_Getting_Started.ipynb
│   ├── 02_Model_Hub.ipynb
│   ├── 03_Tokenizers.ipynb
│   ├── 04_Models.ipynb
│   ├── 05_Pipelines.ipynb
│   ├── 06_Text_Generation.ipynb
│   └── 07_Final_Project.ipynb
│
├── images/
│
├── assets/
│
└── src/
```

Each notebook focuses on one concept so that you can learn progressively rather than trying to understand everything at once.

---
