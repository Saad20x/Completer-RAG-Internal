# 🧠 RAG Pipeline with Lightweight LLM (Qwen 0.6B)

A production-style **Retrieval-Augmented Generation (RAG)** system built using a lightweight open-source model (**Qwen 0.6B**) optimized for low-resource environments like Google Colab.

---

## 🚀 Project Overview

This project demonstrates how to build an end-to-end **RAG pipeline** that:

* Ingests and processes documents
* Converts text into embeddings
* Stores them in a vector database
* Retrieves relevant context
* Generates accurate answers using an LLM

Unlike heavy models (e.g., Mistral-7B), this implementation is optimized for **low RAM usage** while maintaining strong performance.

---

## 🛠️ Tech Stack

* **LLM:** Qwen 0.6B (lightweight, efficient)
* **Framework:** LlamaIndex / LangChain
* **Embeddings:** HuggingFace Embeddings
* **Vector Store:** FAISS
* **Environment:** Google Colab
* **Quantization:** 4-bit (BitsAndBytes)

---

## ⚡ Key Features

* ✅ Runs on low-resource machines 
* ✅ Fully open-source (no API costs)
* ✅ Efficient memory usage (no crashes like larger models)
* ✅ Clean modular pipeline (easy to extend)
* ✅ Production-style structure


---

## 🧪 How It Works

1. **Document Loading**

   * Load PDFs / text files

2. **Chunking**

   * Split text into manageable chunks

3. **Embedding**

   * Convert text → vectors using HuggingFace

4. **Storage**

   * Store vectors in FAISS

5. **Retrieval**

   * Fetch relevant chunks based on query

6. **Generation**

   * Use Qwen model to generate final answer

---
